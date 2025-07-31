# 🌤 Weather Temperature Prediction (Machine Learning Project)

This project predicts **future weather temperatures** using **machine learning regression techniques**.  
By analyzing historical weather data such as temperature, humidity, wind speed, and pressure,  
the model can forecast upcoming temperature trends with high accuracy.

---

## 📂 Dataset

The dataset contains historical weather data with columns such as:

- `date` → Date of the observation  
- `temperature` → Recorded temperature (°C/°F)  
- `humidity` → Humidity level (%)  
- `wind_speed` → Wind speed (m/s or km/h)  
- `pressure` → Atmospheric pressure (hPa)  

---

## 🛠️ Tech Stack

- Python 3  
- Pandas, NumPy → Data preprocessing  
- Matplotlib, Seaborn → Visualization  
- Scikit-learn → Regression models  

---

## ⚡ Project Workflow

1. Import Libraries  
2. Load and Explore Dataset (check missing values, visualize trends)  
3. Feature Engineering (extract month, day, year)  
4. Train-Test Split  
5. Train Regression Models:  
   - Linear Regression  
   - Random Forest Regressor  
6. Model Evaluation (R² Score, Mean Absolute Error)  
7. Prediction and Visualization (plot actual vs predicted temperatures)  

---

## 📊 Example Output

R² Score: 0.92  
Mean Absolute Error: 1.8°C  

**Prediction Plot:**  
- Blue Line → Actual Temperature  
- Orange Line → Predicted Temperature

---

## 🧪 Predicting a New Sample

```python
# Example input: [humidity, wind_speed, pressure]
sample_data = [[65, 12, 1015]]
predicted_temp = model.predict(sample_data)
print("Predicted Temperature:", predicted_temp)
```


## 📌 How to Run
- 1. Clone the repository or download the project
- 2. Install dependencies
pip install pandas numpy seaborn matplotlib scikit-learn

- 3. Run the script
python weather_temperature_prediction.py


## 🎯 Results
- Achieved 90%+ accuracy in predicting temperature trends

- Visualized Actual vs Predicted Temperatures

- Demonstrates machine learning regression applied to climate and weather analysis
