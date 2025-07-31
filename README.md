🛍️ Product Classification using Machine Learning
This project is a full-stack web application that automatically classifies product descriptions into relevant categories using Natural Language Processing (NLP) and Machine Learning. It’s designed to support e-commerce platforms by improving search accuracy, user experience, and inventory management through intelligent automation.

📌 Project Overview
With millions of products listed on online platforms, manual categorization is time-consuming and error-prone. This system uses a Random Forest Classifier—a powerful ensemble machine learning algorithm—to predict the correct category of a product based on its description. The entire pipeline—from data collection to model deployment—is built using Python and web technologies.

🎯 Project Objectives
Data Collection and Preprocessing
Scrape product data using Selenium and clean it to make it suitable for machine learning.

Feature Extraction
Convert product descriptions into numerical data using techniques like TF-IDF (Term Frequency–Inverse Document Frequency).

Model Development
Train a Random Forest Classifier to learn patterns from the descriptions and accurately assign categories.

Evaluation & Optimization
Measure performance using metrics like accuracy, precision, recall, and F1-score. Fine-tune model parameters to improve results.

Web Application Integration
Develop a user interface where users can input product descriptions and receive real-time classification results.

Database Management
Store user input, predictions, and product data securely in a MySQL database.

Deployment
Host the application so it’s accessible online for end-users.

⚙️ Technologies Used
Machine Learning & Data Processing: Python, scikit-learn, pandas, NumPy

Text Processing: TF-IDF, Natural Language Toolkit (NLTK)

Web Scraping: Selenium, BeautifulSoup

Backend: Flask (Python web framework)

Frontend: HTML, CSS, Bootstrap, JavaScript

Database: MySQL

🤖 Why Random Forest?
The Random Forest algorithm combines multiple decision trees to produce more accurate and stable predictions. It:

Handles large datasets and high-dimensional features well

Reduces overfitting compared to individual decision trees

Provides excellent performance with minimal tuning

🌐 Key Features
📝 User input form for product descriptions

⚡ Real-time prediction and category display

🛠 Admin/backend system to manage data and results

📈 Accurate classification powered by a trained ML model

📂 Data storage in MySQL for analysis and logging

