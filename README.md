# 📈 Stock Price Prediction Using LSTM Neural Network and Deep Learning Techniques

## 📌 Project Overview
This project demonstrates the use of **Long Short-Term Memory (LSTM)** neural networks to forecast the closing prices of **Tata Motors Ltd.** and **Mahindra & Mahindra Ltd.**, two major stocks listed on the **National Stock Exchange (NSE)**.  
The goal is to help investors and analysts make informed decisions by predicting future stock prices and visualizing trends.

---

## 🗂️ Dataset
- **Source:** Historical daily closing prices and additional features collected from Yahoo Finance.
- **Features:**  
  - Closing Price  
  - Trading Volume  
  - Daily High & Low Prices  
  - Technical Indicators (optional)

- **Period:** Approximately 5 years of daily stock data.  
- **Preprocessing:**  
  - Missing values handled.  
  - Data normalized using **MinMaxScaler**.  
  - Split into:  
    - **Training:** ~80%  
    - **Testing:** ~20%

---

## 🧠 Model Architecture
- **Model:** 3-layer stacked LSTM
  - Layer 1: 60 units
  - Layer 2: 50 units
  - Layer 3: 50 units
- **Dropout:** 0.2 after each LSTM layer to prevent overfitting.
- **Optimizer:** Adam
- **Batch Size:** 32
- **Time Step:** 100-day rolling window
- **Early Stopping & Learning Rate Scheduler:** Included to optimize training efficiency.

---

## ✅ Evaluation Metrics
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **R² Score (Coefficient of Determination)**

| Stock                  | RMSE  | MAE   | R²   |
|------------------------|-------|-------|------|
| Tata Motors            | 32.52 | 25.51 | 0.772 |
| Mahindra & Mahindra    | 61.63 | 50.00 | 0.164 |

---

## ⚙️ Key Features
- Combines **two stocks** into a single prediction pipeline.
- Accepts **user input** for start date and prediction horizon (**30 or 90 days**).
- Generates future closing price forecasts for both stocks.
- Visualizes **actual vs predicted prices** for comparison.
- Provides a clear **investment suggestion** based on forecast trends.

---

## 📊 Visual Output
- Time series plots comparing actual and predicted prices.
- Easy-to-interpret evaluation of model performance.

---

## 📝 Research Publication

This project is part of the research paper:  
**"Stock Price Prediction Using LSTM Neural Network and Deep Learning Techniques"**  
presented at **ICDSAI-2024** and indexed in **Scopus**.

---

## 📚 Author
**Developed by:** Omkar Bhosale

## 📫 Contact
- 📧 **Email:** omkarbhosale1623@gmail.com
- 🔗 **LinkedIn:** [linkedin.com/in/omkar-bhosale-75a18122a](https://www.linkedin.com/in/omkar-bhosale-75a18122a/)
- 💻 **GitHub:** [github.com/omkarbhosale1623](https://github.com/omkarbhosale1623)
