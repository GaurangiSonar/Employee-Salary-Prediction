# Employee-Salary-Prediction
## **Employee Salary Prediction using Supervised Machine Learning Algorithms**

This project demonstrates the practical use of supervised machine learning models (**Linear Regression** and **Random Forest Regressor)** to estimate employee salaries based on experience, education, job role, department, and performance. The project features an intuitive **Streamlit web app** with real-time predictions, interactive visualizations (radar charts, bar charts, and model comparisons), and downloadable PDF reports.

---

## Key Features

- **Automated Salary Prediction**: Uses supervised machine learning algorithms for accurate predictions.
- **Two ML Models**: Choose between **Linear Regression** and **Random Forest Regressor**.
- **Interactive Web App (Streamlit)**:
    - User-friendly input form for employee details
    - Radar chart of numeric attributes
    - Bar chart of feature breakdown
    - Model comparison chart
- **PDF Report Generation**: Downloadable salary prediction reports for record-keeping.
- **Reusable Models**: Models and preprocessing encoders saved using `joblib`.

---

## Files in This Repo

- `Employee Salary Prediction Project.ipynb` – Main Jupyter notebook for model building and evaluation.
- `complex_employee_data.csv` – Dataset used for training

---

## How to Run (Google Colab with ngrok)

1. **Open the Notebook:**
    
    Upload and open `Employee_Salary_Prediction.ipynb` in **Google Colab**.
    
2. **Upload the Dataset:**
    
    Run the cell that asks for file upload:
    
    ```python
    from google.colab import files
    uploaded = files.upload()
    ```
    
    and upload `complex_employee_data.csv`.
    
3. **Run All Cells:**
    
    Click **Runtime → Run all**.
    
    - This will train the models (**Linear Regression** & **Random Forest Regressor**)
    - Save all required files
    - Generate the `app.py` file
4. **Launch the Web App:**
    
    The last cell will run the **Streamlit app** and create a public URL using **ngrok**.
    

---

## Sample Output

- Predicted salary for uploaded employee data
- Radar Chart – Employee Input Overview
- Bar Chart – Filtered Feature Breakdown
- Model Comparison – Linear vs Random Forest
- Downloadable report in PDF format
