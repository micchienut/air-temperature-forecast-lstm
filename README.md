# Air Temperature Forecasting with LSTM 🌡️  
This project was developed as part of my Deep Learning final exam. The goal is to predict air temperature (AT) one hour into the future, using the previous five hours of air quality and meteorological data.  

## ✨ Project Overview  
- **Dataset**: Rich air quality dataset spanning 5+ years, recorded hourly, with 24 features (pollutants + meteorological data).  
- **Objective**: Forecast AT (Air Temperature) one step ahead using multivariate time series analysis.  
- **Models**:  
  - LSTM Baseline  
  - LSTM Modified  
  - LSTM Baseline Tuned (best performance)  
- **Key Insight**: Forecasting air temperature is vital for public health and energy management.  

## 📊 Key Findings  
- Treating the task as a multivariate time series problem was effective.  
- All models performed reasonably well, with the LSTM Baseline Tuned model being the best.  
- Proper preprocessing (e.g., cyclical encoding for time features, RobustScaler, sliding window sequences) significantly improved results.  
- Complex architectures were not necessary — simple LSTM structures with tuning achieved strong performance.  

## 🛠️ Tech Stack  
- Python  
- TensorFlow / Keras  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib & Seaborn  

## 🚀 Future Improvements  
- Experiment with other architectures (e.g., GRU, BiLSTM, Transformer-based models).  
- Extend prediction horizon (not only 1-hour ahead).  
- Explore additional preprocessing for outliers and skewed data.  

## 📂 Folder
More files such as PPT and video explanation can be seen [here](https://drive.google.com/drive/folders/1ErWOePgLHA9nuXIPBvPHtf-nEhSO1GZO?usp=drive_link)

## 📷 Example Results  
<img width="1209" height="505" alt="image" src="https://github.com/user-attachments/assets/c7a8acd9-d8e8-4301-96dc-e042e4d296b9" />

## 👩‍💻 Author  
**Michelle Nathania**  
Data Science student at BINUS University | Passionate about Machine Learning, Deep Learning, and applying AI to real-world challenges  

---
