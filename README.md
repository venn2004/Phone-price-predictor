<h1 align="center">📱 SmartPrice: Mobile Value Estimator</h1>

<p align="center">
  Predict mobile phone prices based on technical specs using machine learning regression models with a real-time Gradio web app.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python">
  <img src="https://img.shields.io/badge/Machine%20Learning-Regression-orange?logo=scikit-learn">
  <img src="https://img.shields.io/badge/Frontend-Gradio-20c997?logo=gradio">
  <img src="https://img.shields.io/badge/License-MIT-green.svg">
</p>

---

## 📌 Overview

**SmartPrice** is a machine learning-based mobile price prediction system. It estimates mobile phone prices based on core specifications like RAM, battery, cameras, and more. Users can interactively test it using a sleek **Gradio web interface**.

---

## 📂 Table of Contents

- [✨ Features](#-features)
- [📊 Dataset](#-dataset)
- [⚙️ Installation](#-installation)
- [💻 Usage Guide](#-usage-guide)
- [📈 Results](#-results)
- [🌐 Gradio UI Preview](#-gradio-ui-preview)
- [🧾 License](#-license)
- [📬 Contact](#-contact)

---

## ✨ Features

- ✅ Clean and preprocess raw mobile spec data
- ✅ Explore feature correlation & detect outliers
- ✅ Train & compare multiple regression models
- ✅ Tune hyperparameters using GridSearchCV
- ✅ Evaluate using RMSE, MAE, and R² metrics
- ✅ Launch interactive Gradio-based prediction app

---

## 📊 Dataset

- **File:** `final_mobile_price_data.csv`
- **Description:** Contains mobile phone specs and corresponding market prices
- **Features:** RAM, ROM, Battery, Front/Rear Camera, Processor Speed, Display Size
- **Source:** Public datasets & Kaggle

---

## ⚙️ Installation

> 📌 Recommended: Use a virtual environment

```bash
# Clone the repository
git clone https://github.com/yourusername/smartprice-estimator.git
cd smartprice-estimator

# Create virtual environment
python -m venv venv

# Activate environment
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt



💻 Usage Guide
Open Final_model_predictor.ipynb in Jupyter, Colab, or VS Code

Run all cells in order to:

Load and explore data

Preprocess and scale features

Train and evaluate ML models

Launch the Gradio prediction interface

💡 Tip: Use Google Colab with GPU for better performance.

📈 Results
Model	RMSE	MAE	R² Score
Linear Regression	6608.60	5277.82	0.84
Random Forest Regressor	5716.11	4226.80	0.88
Gradient Boosting	5934.55	4602.22	0.87

📊 Visual Outputs:
🔥 Correlation Heatmap

📦 Outlier Analysis (Boxplots)

⭐ Feature Importance (for tree-based models)

🌐 Gradio UI Preview
A clean, minimalistic UI that allows users to predict mobile prices by entering key specifications.

📝 Inputs:
RAM (GB)

ROM (GB)

Battery Capacity (mAh)

Rear Camera (MP)

Front Camera (MP)

Processor Speed (GHz)

Screen Size (inches)

💸 Output:
Predicted mobile phone price displayed instantly.

⚡ Highlights:
Real-time predictions

User-friendly interface

No page reload required


