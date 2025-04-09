# 🌡️ IoT Predictive Maintenance ML Model

This project uses synthetic IoT sensor data to build a machine learning model that predicts whether a device is likely to fail. The goal is to simulate real-world predictive maintenance scenarios using temperature, vibration, humidity, voltage, and runtime data.

## 📊 Dataset

The dataset (`sensor_data.csv`) was generated with 1000 samples and includes the following features:

- `temperature` (°F)
- `vibration` (m/s²)
- `humidity` (%)
- `runtime_hours`
- `voltage` (V)
- `failure` (0 = healthy, 1 = failure)

## 📈 ML Approach

- **Model Used**: Random Forest Classifier
- **Steps**:
  - Exploratory Data Analysis (EDA)
  - Train/test split
  - Model training
  - Evaluation with confusion matrix and classification report

## 🧪 Results

The model effectively classifies failure vs. non-failure with high accuracy, even on imbalanced data. Results are evaluated using precision, recall, F1-score, and confusion matrix.

## 📁 Files Included

- `sensor_data.csv` – dummy IoT sensor dataset
- `iot_model.ipynb` – Jupyter Notebook with full pipeline
- `README.md` – Project documentation

## 🚀 Future Work

- Deploy as a web app using Streamlit or Flask
- Add data preprocessing and tuning (GridSearchCV)
- Use real-world IoT datasets for improved realism

## 👩🏽‍💻 Author

**Ruth Ondiere**  
[LinkedIn](https://www.linkedin.com/in/ruth-ondiere-254009198) • [GitHub](https://github.com/BONAONDIERE) • bonareriondiere@gmail.com

---

> “Predictive maintenance saves time, money, and lives. This is where AI meets the real world.”

