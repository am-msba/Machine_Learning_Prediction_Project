[**Home**](https://am-msba.github.io/Portfolio/) | [**MIP Optimizer**](https://am-msba.github.io/MIP_Optimization_Solver/)

# Predicting Flu Vaccination Likelihood 💉

## Background
In this project, I took a deep dive into the **National 2009 H1N1 Flu Survey** dataset. The goal was simple: use predictive modeling to figure out how likely someone was to get the **2009 H1N1 flu vaccine** and the **seasonal flu vaccine**. By analyzing survey responses, I wanted to see if we could spot the patterns behind why people choose to get vaccinated during a public health crisis.

---

## Methods
Getting the data ready was a huge part of the process. I built a solid preprocessing pipeline that handled missing values, scaled numeric data, and used binary encoding for categorical features so the models could run efficiently.

Once the data was prepped, I tested out four different modeling approaches:
* **Logistic Regression**
* **Random Forest Classification**
* **XGBoost (Extreme Gradient Boosting)**
* **Random Forest Modeling**

To get the best possible results, I used **Grid-Search Cross-Validation**. This allowed me to fine-tune the hyperparameters for each model, making sure they weren't just accurate, but also computationally efficient.

---

## Results
The tuning definitely paid off. By focusing on the **ROC_AUC** score, I was able to maximize how well the models could tell the difference between people who got vaccinated and those who didn't. The final models strike a great balance between high predictive power and smart resource management.
