# Quantitative Stock Return Prediction

This project predicts the **5-day future return direction** of **Volkswagen AG (VOW3.DE)** stock
using machine learning models based on its own and its key suppliers' past returns.

## 📈 Objective
Predict whether Volkswagen's stock price will **increase (1)** or **decrease (0)** after 5 days,
based on the 5-day rolling returns of:
- Volkswagen AG (`VOW3.DE`)
- Continental AG (`CON.DE`)
- Infineon Technologies AG (`IFX.DE`)

## 🧰 Tools and Libraries
- Python 3.x  
- pandas, numpy  
- yfinance  
- scikit-learn  
- matplotlib / seaborn  
- jupyter

## 🧠 Models Implemented
1. Logistic Regression  
2. K-Nearest Neighbors (k=5)  
3. Support Vector Machine (Linear Kernel)  
4. Decision Tree  
5. Random Forest

## ⚙️ Workflow
1. Data downloaded via `yfinance`
2. 5-day rolling returns calculated for each stock
3. Binary target created for Volkswagen’s 5-day price direction
4. Models trained and evaluated on accuracy, precision, recall, F1, and ROC-AUC
5. Feature importance analyzed from Random Forest

## 📊 Expected Results
Typical accuracy: **55–60%** (realistic for financial prediction tasks)

## 📝 Project Structure
See folders `src/`, `notebooks/`, and `reports/` for detailed code and outputs.

## 📄 License
This project is for educational purposes.
