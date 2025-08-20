# 📊 Ice Cream Revenue Prediction using Simple Linear Regression

This project is about predicting **ice cream revenue** based on **temperature** using a simple linear regression model.  

We used the dataset from Kaggle:  
👉 [Ice Cream Revenue Dataset](https://www.kaggle.com/datasets/vinicius150987/ice-cream-revenue)

---

## 🚀 Project Steps

1. **Importing Libraries**  
   - Imported the required Python libraries for data handling, visualization, and machine learning.  

2. **Loading the Dataset**  
   - Brought in the dataset and checked its structure.  
   - No missing values or duplicates were found.  

3. **Data Visualization**  
   - Plotted the data points to see the relationship between temperature and revenue.  
   - The scatter plot showed a **clear linear relationship** — perfect for linear regression.  

4. **Splitting the Data**  
   - Used **train-test split (80:20)** to divide the dataset.  

5. **Building the Model**  
   - Applied **Simple Linear Regression** from `sklearn`.  
   - Fitted the model on training data and made predictions on test data.  

6. **Visualizing the Best Fit Line**  
   - Plotted the regression line over the data points to confirm the fit.  

7. **Model Evaluation**  
   - **Coefficient (Slope):** Found  
   - **Intercept:** Found  
   - **Mean Absolute Error (MAE):** `19.14`  
   - **Mean Squared Error (MSE):** `635.15`  
   - **Root Mean Squared Error (RMSE):** `25.22`  
   - **R² Score:** `0.97`  
   - **Adjusted R² Score:** `0.97`  

   ✅ The model shows a **very strong fit** with low error values.  

---

## 📈 Results

- The regression model explains **97% of the variance** in revenue based on temperature.  
- Error values are small, making this model highly reliable for prediction.  

---

## 🛠️ Tech Stack

- **Python**  
- **Pandas**  
- **NumPy**  
- **Matplotlib / Seaborn**  
- **Scikit-Learn**  

---

## 📌 Conclusion

This project demonstrates how temperature directly affects ice cream sales.  
A simple linear regression model was enough to capture this relationship with very high accuracy.  

---
