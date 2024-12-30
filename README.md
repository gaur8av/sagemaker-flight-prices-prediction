# Flight price Prediction:End-to-End machine learning project using AWS sagemaker

Welcome to the **Flight Price Prediction** project! This repository hosts a machine learning-based solution for predicting flight ticket prices, providing insights into trends and factors affecting airline fares. The project uses Amazon SageMaker for model development and a user-friendly web interface is deployed using Streamlit Cloud.

### About XGBoost Model
The core of this project is the **XGBoost (Extreme Gradient Boosting)** model, which is a powerful and efficient implementation of gradient boosting algorithms. XGBoost is known for:

- **High Performance**: Optimized for speed and accuracy with parallel computation and tree pruning.
- **Feature Handling**: Capable of handling sparse data and missing values effectively.
- **Regularization**: Includes L1 and L2 regularization, reducing overfitting and improving generalization.
- **Scalability**: Suitable for large-scale datasets and complex prediction tasks.

By leveraging XGBoost, this project achieves accurate and reliable predictions for flight prices, ensuring users gain actionable insights into fare trends.

## Key Features

- **Machine Learning Model**: Predicts flight prices based on various features like departure time, arrival time, duration, airline, source, destination, and date.
- **Algorithm**: Utilizes the XGBoost regression model for accurate price prediction.
- **Cloud Deployment**: Built using Amazon SageMaker and deployed on Streamlit Cloud for user accessibility.
- **User Interface**: Streamlit web app for seamless user interaction.

## How It Works

### Workflow
1. **Data Collection**: 
   - Raw data on flight details is gathered.

2. **Data Cleaning and Preprocessing**: 
   - Extensive preprocessing ensures clean and consistent datasets.
   - Missing values are handled, and features are scaled or transformed as necessary.

3. **Exploratory Data Analysis (EDA)**: 
   - Insights into data distribution, trends, and correlations are obtained to understand key patterns.

4. **Feature Engineering**: 
   - Relevant features affecting ticket prices are identified and created to improve model performance.

5. **Model Development**: 
   - Key factors affecting ticket prices are used for training.
   - The XGBoost algorithm, known for its efficiency and accuracy, is used.

6. **Web App Deployment**:
   - A Streamlit app is deployed on Streamlit Cloud to interact with the model in real time.
   - Users can input flight details and obtain instant price predictions.

## Technologies Used

- **Amazon SageMaker**: For model training and development.
- **XGBoost**: The core algorithm used for regression tasks.
- **Streamlit**: To create and deploy the front-end web application.
- **Python**: For coding, including libraries such as pandas, numpy, and sklearn for preprocessing and analysis.

## Setup Guide

### Prerequisites
- Python 3.7 or higher
- Basic knowledge of machine learning

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flight-price-prediction.git
   cd flight-price-prediction
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

### Deploying with SageMaker
- Follow Amazon SageMaker’s guidelines to train and host your model.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- **Amazon Web Services** for providing an excellent ML hosting platform.
- **Streamlit Community** for the support in creating an intuitive UI.
- Contributors and testers for valuable feedback.

---




