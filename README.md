# 🧪 Chlorophyll-a Prediction in Coastal Waters with Remote Sensing

This project simulates chlorophyll-a concentration data in coastal waters using synthetic remote sensing reflectance values and applies machine learning models to predict chlorophyll-a levels. It demonstrates environmental monitoring techniques commonly used in water quality and climate research.

---

## 🌍 Overview

Chlorophyll-a is a key indicator of phytoplankton biomass and coastal water quality. This project mimics remote sensing band data (blue, green, red, and NIR reflectance) and uses regression models to estimate chlorophyll-a concentrations.

---

## 📊 Features

- ✅ Synthetic reflectance dataset (150 samples)
- 🔁 Nonlinear chlorophyll-a computation with noise
- 🧠 Machine learning models:
  - Linear Regression
  - Random Forest Regressor
- 📉 Model evaluation using RMSE and R²
- 📈 Visual comparison of actual vs predicted values

---

## 🧰 Technologies Used

- Python 3
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

---

## 📁 Project Structure

.
├── synthetic_chlorophyll_a.csv # Generated synthetic dataset
├── chlorophyll_prediction.py # Main Python script
└── README.md # Project description and usage

yaml
Copy
Edit

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/chlorophyll-a-prediction.git
   cd chlorophyll-a-prediction
Install the dependencies:

bash
Copy
Edit
pip install numpy pandas scikit-learn matplotlib seaborn
Run the script:

bash
Copy
Edit
python chlorophyll_prediction.py
🧪 Sample Data Preview
Rrs_blue	Rrs_green	Rrs_red	Rrs_nir	Chlorophyll_a
0.0123	0.0214	0.0087	0.0042	3.547
0.0151	0.0253	0.0093	0.0061	3.994

📜 License
This project is licensed under the MIT License.

👨‍🔬 Author
Agbozu Ebingiye Nelvin
📧 nelvinebingiye@gmail.com
🔗 GitHub: nelvinebi
LinkedIn: https://www.linkedin.com/in/agbozu-ebi/
