#  Polynomial Regression on Insurance Dataset

This project demonstrates how to use **Polynomial Regression** in Python to model and predict insurance charges based on demographic and health-related attributes. The goal is to capture potential non-linear relationships between features such as age, BMI, and smoking status, and the target variable, `charges`.

---

##  Dataset

The dataset used is `Insurance.csv`, which contains the following features:

- `age`: Age of the policyholder  
- `sex`: Gender of the policyholder  
- `bmi`: Body Mass Index  
- `children`: Number of children covered by insurance  
- `smoker`: Smoking status (yes/no)  
- `region`: Residential area (e.g., southeast, northwest)  
- `charges`: Annual medical insurance charges (target variable)

---

##  Tools & Libraries

- Python- Jupyter Notebook 
- Pandas   
- Scikit-learn

---

##  Project Workflow

1. **Data Loading**  
   Loaded the `Insurance.csv` file using Pandas.

2. **Data Preprocessing**  
   - Checked for null values, unique values. 
   - Converted categorical variables.
   - Normalized or scaled numerical features if needed  

3. **Feature Engineering**  
   - Selected relevant features for regression  
   - Applied polynomial transformation to capture non-linear patterns

4. **Model Building**  
   - Trained a Polynomial Regression model using Scikit-learn  
   - Split data into training and testing sets  
   - Fitted the model on training data

5. **Model Evaluation**  
   - Calculated Mean Squared Error (MSE). 

---

##  Results

The Polynomial Regression model performed better than a linear regression model by capturing more complex relationships between features and the insurance charges. I got approximately close error value of actual charges & predicted charges.  .

---

