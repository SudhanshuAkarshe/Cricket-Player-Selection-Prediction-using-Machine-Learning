# Cricket-Player-Selection-Prediction-using-Machine-Learning

Here's a well-structured **README.md** file for your GitHub project:  

---

# **Cricket Player Performance Prediction**  

## **Overview**  
This project leverages **machine learning models** to analyze and predict the performance of **batsmen and bowlers** based on historical ODI data. The models are trained separately using two datasets:  

- `batters_odi.csv` – Contains performance metrics for batsmen.  
- `bowler.csv` – Contains performance metrics for bowlers.  

The results are displayed on a **Django-powered web application**, allowing users to input player data and receive predictions.  

## **Project Structure**  

- **`batter_choose.ipynb`** – Trains and evaluates the **batsmen performance prediction model** using `batters_odi.csv`.  
- **`bowling.ipynb`** – Trains and evaluates the **bowlers performance prediction model** using `bowler.csv`.  
- **Django Backend** – Hosts the trained models and serves predictions via a web interface.  

## **Backend Integration**  
The trained machine learning models for **batsmen and bowlers** are seamlessly integrated into the **Django backend**. When users submit player data through the web interface, the backend processes the input and utilizes the appropriate model to generate predictions. The results are then displayed on the **localhost web application**.  


### **Prerequisites**  
Ensure you have the following installed:  

- Python (≥ 3.8)  
- Django  
- Pandas  
- Scikit-Learn  
- Jupyter Notebook  

