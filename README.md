# Car Purchasing Data Project

This project aims to develop an **Artificial Neural Network (ANN)** model to predict whether a customer will purchase a car and estimate the expected purchase amount, using customer data such as demographics, financial profile, and credit status. By analyzing historical data, the goal is to create a model that can effectively classify customers who are likely to purchase a car and predict the estimated purchase amount. This project serves both as an exercise in applying machine learning techniques, particularly neural networks, and as a practical example of how data science can be used to understand consumer behavior.

## Key Features and Objectives

- **Customer Data Analysis**: This project explores how customer features, such as **gender**, **age**, **annual salary**, **credit card debt**, and **net worth**, influence the decision to purchase a car.
  
- **ANN Model Development**: The project involves creating and training an **Artificial Neural Network (ANN)** that can predict customer car purchase decisions and estimate the amount spent on the car.
  
- **Model Optimization**: In addition to developing the ANN, the project includes optimizing the model to minimize errors and improve prediction accuracy. Various techniques, such as **backpropagation** and different **activation functions**, are used for model optimization.

- **Evaluation**: The model's performance will be evaluated through key metrics such as **training and validation loss**. These losses help gauge how well the model is learning and generalizing from the data.

- **Real-World Insights**: The final model aims to provide valuable insights into customer purchase behavior, offering a deeper understanding of the factors that influence car-buying decisions. By utilizing this model, businesses can target the right customers and offer tailored products or services.

## Files in this Repository

This repository includes the following files essential for the development and training of the model:

- **Car Purchase Amount Model using ANN.ipynb**: This Jupyter notebook contains the core code for the Artificial Neural Network (ANN) implementation. It covers all aspects of the machine learning pipeline, including:
  - Data preprocessing and feature engineering.
  - Model architecture definition using Keras/TensorFlow.
  - Training the ANN using customer data.
  - Evaluation of model performance based on training and validation loss.
  
  The notebook also includes detailed comments and visualizations to help understand the model’s performance and training process.

- **Car_Purchasing_Data.csv**: This CSV file contains historical customer data, including demographics, financial information, and purchase behavior. It is used to train and test the ANN model. The dataset includes the following columns:
  - **Gender**: Customer’s gender.
  - **Age**: Customer’s age.
  - **Annual Salary**: Customer’s annual income.
  - **Credit Card Debt**: Amount of credit card debt the customer holds.
  - **Net Worth**: Customer’s total net worth.
  - **Purchased**: Whether the customer purchased a car (target variable for classification).
  - **Purchase Amount**: The expected amount the customer would spend on a car (target variable for regression).

## How to Use

1. **Clone the Repository**: First, clone this repository to your local machine:

   ```bash
   git clone https://github.com/nurulasyrifah/Car_Purchasing_Data.git
   ```

2. **Install Dependencies**: The project requires the following Python libraries:
   - TensorFlow/Keras
   - pandas
   - numpy
   - matplotlib
   - seaborn

   You can install the dependencies by running:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**: Open the `Car Purchase Amount Model using ANN.ipynb` notebook in Jupyter or any other notebook interface. Follow the steps in the notebook to train and evaluate the model.

4. **Analyze the Results**: The notebook will guide you through analyzing the model’s performance, including how well it predicts car purchases and estimates the purchase amount. You will also see how training and validation losses evolve over the epochs.
