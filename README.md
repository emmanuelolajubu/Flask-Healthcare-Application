Flask Healthcare Application

Overview
This project is a simple web application built with Flask that allows users to track their expenses. The objective is to analyze their income spending in preparation for a new product launch in the healthcare industry. It collects user data, stores it in MongoDB, processes it using Python/R, visualizes insights, and deploys the Flask app on AWS.


Installation
1. Install Flask: `pip install flask`
2. Set up MongoDB.
3. Clone this repository.
4. Configure Flask to connect to your MongoDB instance.
5. Run the Flask app locally: `python app.py`.

Usage
1. Access the app in your browser.
2. Fill out the form to collect user details (Age, Gender, Expenses).
3. Data will be stored in MongoDB.
4. Use the Jupyter Notebook to process and visualize data.

Data Processing
- Create a Python or R class (e.g., `User`) to represent user data.
- Loop through the MongoDB data and extract relevant information.
- Save the data to a CSV file (e.g., `user_data.csv`).
- Export the data charts to a PowerPoint presentation.

Deployment
- Host the Flask app on Amazon Web Services (AWS).

Credits
Flask documentation
MongoDB documentation
Jupyter notebook documentation
