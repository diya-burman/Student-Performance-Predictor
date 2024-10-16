# The Student Performance Predictor

## Project Overview
The **Performance Predictor** is a web application designed to predict student exam performance based on demographic factors and previous exam scores. This project employs machine learning techniques to provide insights into potential academic outcomes, enabling students and educators to make informed decisions.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgments)

## Technologies Used
- **Programming Language:** Python
- **Web Framework:** Flask
- **Machine Learning Libraries:** Scikit-learn, Pandas, NumPy
- **Frontend Technologies:** HTML, CSS, JavaScript
- **Data Handling:** Pandas for data manipulation and preprocessing

## Features
- **User-Friendly Interface:** A clean and intuitive web interface that allows users to input demographic data and previous exam scores effortlessly.
- **Real-Time Predictions:** The application provides instant predictions of math scores based on user inputs, making it a practical tool for students and educators.
- **Robust Machine Learning Model:** Trained on comprehensive student performance data, ensuring reliable predictions.
- **Custom Data Ingestion and Preprocessing:** Tailored data handling processes that optimize the input data for better prediction accuracy.
- **Model Performance Metrics:** Achieves an R² (R-squared) accuracy of 88.04%, indicating a strong correlation between predicted and actual scores.

## Installation
To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/vtandon1204/The-Performance-Predictor.git
   cd The-Performance-Predictor
2. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
3. **Run the application:**
   ```bash
   python app.py
4. **Access the application:** Open your web browser and navigate to the local host URL shown in the terminal after running the file.


## Usage
1. **Input Data:** On the homepage, select the student's gender, ethnicity, parental education level, lunch type, and test preparation course from the dropdown menus.
2. **Enter Scores:** Input the reading and writing scores (out of 100) in the designated fields.
3. **Make a Prediction:** Click on the "Predict" button to generate the predicted math score.
4. **View Results:** The predicted score will be displayed on the same page along with the input features.

## Model Performance
The performance of the machine learning model is evaluated using R² (R-squared) accuracy, achieving a value of 88.04. This high accuracy indicates 
a strong correlation between predicted and actual scores, demonstrating the effectiveness of the model in making reliable academic predictions.

## Contributing
Contributions to this project are welcomed! If you have suggestions for improvements or bug fixes, please feel free to open issues or submit pull 
requests. Together, we can enhance the functionality and user experience of the Performance Predictor.

## Acknowledgments
- [Flask](https://flask.palletsprojects.com/) - A lightweight WSGI web application framework in Python.
- [Scikit-learn](https://scikit-learn.org/) - A machine learning library for Python that features various classification, regression, and clustering algorithms.
- [Pandas](https://pandas.pydata.org/) - A fast, powerful, flexible, and easy-to-use open-source data analysis and data manipulation library for Python.
