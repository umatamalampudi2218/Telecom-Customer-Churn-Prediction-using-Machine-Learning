
### README

## Telecom Customer Churn Prediction

### Description
This project aims to build a predictive model to address the issue of high customer churn in a telecommunications company. The model uses machine learning techniques to predict whether a customer is likely to churn based on features such as contract type, tenure, monthly charges, internet service type, and customer demographics.

### Prerequisites
Before you begin, ensure you have met the following requirements:
- **Python 3.7** or higher installed
- **Jupyter Notebook**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **Scikit-learn** libraries installed

### Installation and Setup
To install and set up the project, follow these steps:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/telecom-customer-churn.git
   cd telecom-customer-churn
   ```

2. **Set up the Python Environment:**
   Create a virtual environment and install the required libraries:
   ```sh
   python -m venv env
   source env/bin/activate
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebook:**
   ```sh
   jupyter notebook Telecom_Customer_Churn.ipynb
   ```

### Using the Project
Once the Jupyter Notebook is open, you can run the cells to execute the following steps:

1. **Data Cleaning:**
   - Convert 'TotalCharges' to numeric type and handle missing values.

2. **Data Preprocessing:**
   - Standardize categorical variables.
   - One-hot encode categorical features.
   - Scale features using MinMaxScaler.

3. **Exploratory Data Analysis:**
   - Analyze numerical features and detect outliers.
   - Correlate churn with other variables such as gender, contract type, and dependents.
   - Visualize data trends using graphs.

4. **Feature Engineering:**
   - Create new features like "HighTenureHighMonthly" to improve model performance.

5. **Model Development:**
   - Split data into training (70%) and testing (30%) sets.
   - Train Logistic Regression and Random Forest models.
   - Evaluate models using accuracy and F1-score.

### Results Analysis and Interpretation
- Logistic Regression achieved an accuracy of 80%.
- Random Forest also showed similar accuracy but lower recall.
- Both models identified contract type, tenure, and total charges as key predictors of churn.

### Contributing to the Project
To contribute, follow these steps:
1. **Fork the repository.**
2. **Create a branch:** 
   ```sh
   git checkout -b <branch_name>
   ```
3. **Make your changes and commit them:**
   ```sh
   git commit -m '<commit_message>'
   ```
4. **Push to the original branch:**
   ```sh
   git push origin <project_name>/<location>
   ```
5. **Create a pull request.**

### License
This project is licensed under the @2023 Surya Kiran Varma Vegesna.

### Contact
If you have any questions or want to contribute, please email us at surya@example.com.
