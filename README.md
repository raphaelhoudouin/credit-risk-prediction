#  Credit Risk Prediction

## Table of Contents
- [About The Project](#about-the-project)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Usage and Configuration](#usage-and-configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## About The Project

Leveraging repository presents a Loan and Credit Risk Analysis Tool developed using machine learning and Streamlit. The tool is designed to predict the probability of loan default, assign credit scores, and categorize risk ratings into distinct levels: Poor, Average, Good, or Excellent.

By harnessing logistic regression and advanced feature engineering techniques, this app delivers highly accurate and interpretable predictions for:

- Probability of Loan Default
- Credit Score
- Risk Rating (Poor, Average, Good, Excellent)


### Live App
Explore the app via this URL: [Credit Risk Analyzer](https://raphaelhoudouin-credit-risk-prediction.streamlit.app/).

## Features
- User-friendly input forms.
- Interactive and easy-to-use interface.

![Streamlit App Screenshot](https://github.com/raphaelhoudouin/credit-risk-prediction/blob/main/screenshots/credit_risk_prediction_app_screenshot.png)

## Key Features

1. **Machine Learning Model:**
   - Logistic regression model optimized for accuracy.
   - Predicts loan default probability, credit score, and risk ratings.

2. **Data Preprocessing:**
   - Feature engineering techniques including:
     - Variance Inflation Factor (VIF)
     - Correlation Analysis
     - Weight of Evidence (WOE)
     - Information Value (IV)
   - Scalable preprocessing pipeline with one-hot encoding and scaling.

3. **User-Friendly Interface:**
   - Intuitive sliders and input fields for data entry.
   - Real-time predictions displayed dynamically.

## Technology Stack

- **Machine Learning:** Scikit-learn, NumPy, Pandas
- **Web Framework:** Streamlit
- **Model Persistence:** Joblib

## Getting Started

To get started with this project locally, you’ll need Python 3.8+ installed on your machine along with some necessary Python packages. You can either clone the repository and install dependencies manually or use Docker for an isolated environment.

### Installation Steps

#### Option 1: Installation from GitHub

1. Clone the repository:
   ```bash
   git clone https://github.com/rhoudouin/Loan_Default_Risk_Prediction.git
   ```

2. Create a Virtual Environment (Optional):
   ```bash
   conda create -p <Environment_Name> python==3.8 -y
   ```

3. Activate the Virtual Environment (Optional):
   ```bash
   conda activate <Environment_Name>/
   ```

4. Install Dependencies:
   ```bash
   cd [project_directory]
   pip install -r requirements.txt
   ```

5. Run the Project:
   ```bash
   streamlit run app.py
   ```

6. Access the Project:
   Visit `http://localhost:8501` in your browser to use the app.

#### Option 2: Installation from DockerHub

1. Pull the Docker image from DockerHub:
   ```bash
   docker pull rhoudouin/loan-default-risk-prediction
   ```

2. Run the app inside the container:
   ```bash
   docker run -p 8501:8501 rhoudouin/loan-default-risk-prediction
   ```

3. Access the Project:
   Visit `http://localhost:8501` in your browser to use the app.

## Usage and Configuration

### Web App Usage:
1. **Enter Financial Information:** Input fields for financial metrics and customer details.
2. **Click "Predict Risk":** After entering the data, click the prediction button to view loan default probability, credit score, and risk rating.
3. **Prediction Results:** The app will display the predictions dynamically with explanations of each metric.

### Configuration:
You can modify the `artifacts/` directory to point to your own trained models, encoders, and scaler files. Ensure that the models and encoders are trained and saved in compatible formats (e.g., `.pkl`).

## Contributing

We welcome contributions to improve this project! Whether you are fixing bugs, adding features, or improving documentation, feel free to fork the repository and submit a pull request.

### Steps to Contribute:
1. Fork the repo.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes.
4. Commit your changes:
   ```bash
   git commit -am 'Add feature'
   ```
5. Push to your branch:
   ```bash
   git push origin feature-name
   ```
6. Create a new Pull Request.

## License

Distributed under the GNU General Public License (GPL). See LICENSE for more information.

## Acknowledgements

- **Scikit-learn:** For providing machine learning algorithms and utilities.
- **Streamlit:** For creating the interactive web application.
- **NumPy & Pandas:** For preprocessing and numerical computation.
- **Joblib:** For model serialization and deployment.

## Contact

For any questions or feedback, please contact the project maintainer: **raphaelhoudouin**.  
GitHub: [raphaelhoudouin](https://github.com/raphaelhoudouin)



