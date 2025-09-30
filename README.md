# 💻 Laptop Price Prediction 

<img width="1005" height="553" alt="Laptop Price Prediction" src="https://github.com/user-attachments/assets/8c57cbaf-f6b0-47aa-919b-2c79e6f39e1f" />


This project predicts **laptop prices** using **machine learning**, leveraging a dataset of laptop specifications. The workflow includes extensive **data preprocessing**, **feature engineering**, **model evaluation**, and an **interactive prediction app** built with Streamlit.  

---

## 🚀 Features  

- **Input Specs**: Brand, Type, RAM, Weight, Touchscreen, IPS, Screen Size, Screen Resolution, CPU, HDD, SSD, GPU, OS.  
- **Feature Engineering**:  
  - Extracts features like **PPI** from resolution and screen size.  
  - Encodes and cleans categorical variables.  
- **Models Used**:  
  - Tested multiple regressors (Decision Tree, Random Forest, Gradient Boosting).  
  - Final model: **Random Forest pipeline**, achieving **high R²** and **low MAE**.  
- **Evaluation**:  
  - Metrics include **R² Score** and **MAE** for validation.  
- **App**:  
  - Interactive **Streamlit app** for predicting laptop price based on user-selected configuration.  

---

<img width="461" height="529" alt="Laptop Prediction Screenshot" src="https://github.com/user-attachments/assets/588b5ecf-ed63-4765-9b32-74b9a3ec87bd" />

 
## 🖥️ Usage  

### App Launch  
Run the following command to start the app:  
```bash
streamlit run app.py
