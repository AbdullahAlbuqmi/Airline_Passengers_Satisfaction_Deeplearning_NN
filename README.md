# ✈️ Airline Passenger Satisfaction Prediction (Deep Learning)

This project uses **Neural Networks** to predict whether an airline passenger is **satisfied or dissatisfied** based on travel experience ratings and flight-related metrics.

---

## 📊 Dataset

- **Source:** Kaggle – Airline Passenger Satisfaction  
- **Rows:** 89,127  
- **Features:** 23 (Gender, Age, Class, Wi-Fi Service, Cleanliness, Delay Minutes, etc.)  
- **Target:** `Satisfaction` (0 = Not Satisfied, 1 = Satisfied)

---

## 🧠 Model Overview

| Model Type | Architecture | Optimizer | Best Accuracy |
|------------|--------------|-----------|---------------|
| Neural Network (Dense) | 4 Hidden Layers + BatchNorm + Dropout | Adam | ~96% |

Key techniques used:
- Label Encoding & Scaling
- Dropout & Batch Normalization
- Custom Keras Callback for Fit Monitoring

---

## 🚀 How to Run

```bash
# 1. Clone Repository
git clone https://github.com/yourusername/airline-satisfaction-dl.git
cd airline-satisfaction-dl

# 2. Install Dependencies
pip install -r requirements.txt

# 3. Train Model
python Airline_Passenger_Satisfaction_NN.py
