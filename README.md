# Department-Wide Sales Prediction App

Welcome to the Department-Wide Sales Prediction App! This web application predicts department-wide sales for retail stores based on historical data. It utilizes a trained machine learning model to make predictions based on user input.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Retail businesses often face challenges in accurately forecasting sales, especially across different departments and stores. This project aims to address this challenge by developing a predictive model that can forecast department-wide sales based on various factors such as store size, type, location, economic indicators, and historical sales data.

### Features

- **Home Page**: Displays an overview of the project, problem statement, and features used in the model.
- **Basic Insights**: Provides basic insights about the data, including sample data, weekly sales distribution by store type and size, and line plots of weekly sales and markdown over the years.
- **Predict**: Allows users to input features and predicts department-wide sales using the trained machine learning model.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/chandana95siva/DS_Final_project.git
2. Install the required libraries:
   ```sh
   pip install -r requirements.txt
## Usage 
1. Run the Streamlit web application:
   ```sh
   streamlit run app.py
2. Access the application through the provided URL in your web browser.
## File Structure
The project directory structure is as follows:
.
├── app.py                    # Contains the main code for the Streamlit web application.
├── reg_model.pkl             # Pickled machine learning model for predicting sales.
├── sales_prediction.csv      # Sample dataset used for training the model.
├── README.md                 # Markdown file providing detailed information about the project.
└── requirements.txt          # List of required Python libraries.


## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements or additional features you'd like to see.
## License
This project is licensed under the MIT License - see the LICENSE file for details.
   

