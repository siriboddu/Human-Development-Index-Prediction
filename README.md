**Human Development Index (HDI) Predictor
Overview**

The Human Development Index (HDI) Predictor is a Machine Learning-powered web application developed to estimate a country's Human Development Index (HDI) category using key socio-economic indicators. The application integrates data analysis, predictive modeling, and an intuitive web interface to provide meaningful insights into human development.

The project demonstrates the practical application of Machine Learning, Data Science, and Full-Stack Web Development by combining predictive analytics with an interactive dashboard.

**Key Features**
Machine Learning Prediction

**Predicts the Human Development Index based on the following indicators:**

Life Expectancy at Birth (Health Dimension)
Expected Years of Schooling (Education Dimension)
Mean Years of Schooling (Education Dimension)
Gross National Income (GNI) per Capita (Standard of Living Dimension)
**Interactive Dashboard**
Modern and responsive user interface
Real-time prediction results
Country-wise input selection
Interactive visualizations
Responsive design for desktop and mobile devices
**Exploratory Data Analysis (EDA)**

Provides comprehensive data visualizations including:

Correlation Heatmap
Feature Distribution Plots
Scatter Plots
Histogram Analysis
Box Plot Analysis
**Prediction Insights**

Displays:
Predicted HDI Category
Development Level
Indicator Summary
Graphical Progress Visualization
Policy Recommendation Insights

**Report Generation**
Export prediction reports
Download analysis results
Print-friendly report format

**Prediction History**

Stores previous prediction records locally to enable future comparison and analysis.

**Technology Stack**
Frontend
React.js
Vite
HTML5
CSS3
JavaScript
Tailwind CSS

**Backend**
Python
Flask

**Machine Learning**
Scikit-learn
Pandas
NumPy
Matplotlib
Seaborn

**Development Tools**
Git
GitHub
Visual Studio Code

**Project Architecture**
User
   │
   ▼
Frontend (React + Tailwind)
   │
   ▼
Flask REST API
   │
   ▼
Machine Learning Model
   │
   ▼
Prediction Engine
   │
   ▼
Prediction Result

**Project Structure**
Human-Development-Index-Prediction/
│
├── dataset/
├── models/
├── static/
├── templates/
├── src/
├── public/
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
└── .gitignore

**Installation**
git clone https://github.com/your-username/Human-Development-Index-Prediction.git

cd Human-Development-Index-Prediction

pip install -r requirements.txt

python train_model.py

python app.py

**Model Workflow**
Data Collection
Data Preprocessing
Exploratory Data Analysis
Feature Engineering
Model Training
Model Evaluation
Prediction
Web Deployment

**Future Enhancements**
Real-time UNDP data integration
Interactive world map visualization
Advanced model comparison
Cloud deployment
User authentication
AI-powered development recommendations

**Team**

**Team Lead**

Boddu Siri

**Team Members**
Valluru Pujitha

**Academic Information**

Department: Artificial Intelligence & Data Science

Project Type: SkillWallet Capstone Project

Domain: Healthcare | Machine Learning | Data Science

**Model Performance Characteristics**
Our trained Linear Regression model performs with the following statistical traits on unseen test indicators (80-20 partition):

**R-squared Coefficient (R2):** 99.47(Excellent fit relative to the mathematical index)
**Mean Absolute Error (MAE):** 0.0098
**Root Mean Squared Error (RMSE):** 0.0122

**License**

This project has been developed exclusively for academic and educational purposes as part of the SkillWallet Capstone Program.
