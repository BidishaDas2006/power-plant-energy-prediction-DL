# ⚡ Power Plant Energy Production Prediction using Deep Learning

This project implements a **Deep Learning regression model** to predict the **energy output of a Combined Cycle Power Plant** using environmental parameters.

The model learns the relationship between atmospheric conditions and power plant energy production.

---

## 📊 Problem Statement

Power plants are affected by environmental conditions such as:

- Temperature
- Ambient Pressure
- Relative Humidity
- Exhaust Vacuum

The goal of this project is to train a **Deep Neural Network (DNN)** that can accurately predict the **net hourly electrical energy output** of the plant.

---

## 📂 Dataset

The dataset contains operational measurements of a power plant including:


| Feature | Description |
| Temperature (AT) | Ambient temperature |
| Exhaust Vacuum (V) | Steam turbine exhaust vacuum |
| Ambient Pressure (AP) | Atmospheric pressure |
| Relative Humidity (RH) | Humidity level |
| Energy Output (PE) | Net hourly electrical energy output |

⚠️ Note: The dataset used in this project is relatively **small**, which may limit model generalization.

---

## 🧠 Model Architecture

The neural network was implemented using **PyTorch**.

Architecture:

Input Layer → 4 features  
Hidden Layer 1 → 6 neurons (ReLU)  
Hidden Layer 2 → 6 neurons (ReLU)  
Output Layer → 1 neuron (Energy Output)


Loss Function: **Mean Squared Error (MSE)**  
Optimizer: **Adam**

---

## ⚙️ Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## 📈 Model Performance

Evaluation metric used:

- **Mean Squared Error (MSE)**
- **R2 Score**

The trained model was able to learn the relationship between environmental conditions and power output despite the small dataset.

---

## 🚀 Future Improvements

Possible improvements include:

- Training on **larger datasets**
- Feature engineering
- Hyperparameter tuning
- Trying advanced models (XGBoost, Random Forest)
- Using deeper architectures

---

**Result**
**Training MSE: 20.52**
**Testing MSE: 18.76**
**R2 score: 0.934**

## 📌 Author

Bidisha Das

AI / Machine Learning Enthusiast
