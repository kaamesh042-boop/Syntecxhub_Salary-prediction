Salary Prediction Dashboard using Multiple Linear Regression
Overview

The Salary Prediction Dashboard is an interactive web-based machine learning application designed to demonstrate the implementation of Multiple Linear Regression for salary estimation. The project analyzes the relationship between employee salary and key influencing factors such as work experience, test performance, and educational qualifications.

Built entirely using HTML, CSS, and JavaScript, the application performs data generation, model training, evaluation, and prediction directly within the browser, providing a seamless and engaging user experience without requiring any backend infrastructure.

Key Features
Machine Learning Implementation
Multiple Linear Regression model developed in pure JavaScript
Comparison between Simple Linear Regression and Multiple Linear Regression
Automatic train-test dataset splitting (80:20)
Performance evaluation using RMSE and R² metrics
Interactive Analytics Dashboard
Real-time salary prediction
Dynamic visualizations powered by Chart.js
Model coefficient analysis
Actual vs Predicted comparison
Residual error analysis
Data Exploration
Synthetic dataset generation
Feature distribution analysis
Correlation visualization
Education-level salary insights
Modern User Interface
Professional dark-themed dashboard
Fully responsive design
Interactive charts and controls
Clean and intuitive user experience
Technologies Used
Technology	Purpose
HTML5	Structure and layout
CSS3	Styling and responsive design
JavaScript (ES6)	Data processing and machine learning logic
Chart.js	Interactive data visualization
Machine Learning Workflow
1. Data Generation

A synthetic dataset is generated containing:

Years of Experience
Test Score
Education Level
Salary
2. Data Preprocessing
Education categories encoded numerically
Dataset split into training and testing sets
Feature matrix construction
3. Model Training

Two regression models are trained:

Model A – Simple Linear Regression

Uses only Experience as the predictor variable.

Model B – Multiple Linear Regression

Uses:

Experience
Test Score
Education Level
4. Model Evaluation

The models are evaluated using:

Root Mean Square Error (RMSE)
Coefficient of Determination (R²)
5. Salary Prediction

The best-performing model is used to provide real-time salary predictions based on user-selected inputs.

Dashboard Components
Dataset Overview

Provides a summary of:

Total records
Number of features
Average salary range
Sample Dataset Table

Displays the first few records of the generated dataset for inspection.

Feature Analysis

Visual representations of:

Salary vs Experience
Salary vs Test Score
Salary Distribution
Education Category Distribution
Model Comparison

Side-by-side comparison of:

Training Performance
Testing Performance
RMSE
R² Score
Coefficient Analysis

Visual interpretation of feature importance and model coefficients.

Actual vs Predicted Visualization

Compares actual salary values with model predictions on the test dataset.

Residual Analysis

Evaluates prediction errors and model reliability.

Live Salary Predictor

Allows users to:

Select experience level
Adjust test score
Choose education qualification
Instantly generate salary predictions
Installation and Usage
Clone the Repository
git clone https://github.com/your-username/salary-prediction-dashboard.git
Navigate to the Project Directory
cd salary-prediction-dashboard
Run the Application

Simply open:

salary_prediction.html

in any modern web browser.

No server setup or external dependencies are required.

Project Structure
salary-prediction-dashboard/
│
├── salary_prediction.html
├── README.md
│
└── assets/
    └── screenshots (optional)
Educational Objectives

This project serves as a practical demonstration of:

Linear Regression Fundamentals
Multiple Linear Regression
Data Visualization Techniques
Statistical Model Evaluation
Browser-Based Machine Learning
Interactive Dashboard Development

It is particularly suitable for academic projects, machine learning demonstrations, portfolio development, and educational purposes.

Future Enhancements
CSV Dataset Upload Support
Real-World Dataset Integration
Additional Regression Algorithms
Feature Importance Analysis
Exportable Prediction Reports
Backend Integration with Python/Flask
Model Persistence and Retraining
Author

License

This project is released under the MIT License.

You are free to use, modify, and distribute this project for educational and professional purposes.

Project Highlights

✔ Browser-Based Machine Learning
✔ Multiple Linear Regression Implementation
✔ Interactive Data Visualizations
✔ Real-Time Salary Prediction
✔ Professional Dashboard Design
✔ No Backend Required
✔ Educational and Portfolio Ready
