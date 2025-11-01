# 📱 Mobile Price Range Prediction App

This project is a simple **Streamlit web application** that predicts the **price range of a mobile phone** based on its specifications.
The trained machine learning model (`best_model.pkl`) classifies phones into one of four categories:
- **0** → 💰 Low Cost
- **1** → 💵 Medium Cost
- **2** → 💎 High Cost
- **3** → 🏆 Very High Cost

Project Link : [📱 Mobile Price Range Prediction App](https://mobilepriceclassificationmodel-3onudt2fve8agn9plt5azx.streamlit.app/)
---

## 🚀 Features
- Interactive UI built with **Streamlit**
- Takes multiple phone specifications as input
- Predicts price range instantly
- Uses a pre-trained ML model (`best_model.pkl`)

---

## 🧠 Model Input Features
The model expects the following features:
`battery_power`, `blue`, `clock_speed`, `dual_sim`, `fc`, `four_g`, `int_memory`, `m_dep`, `mobile_wt`, `n_cores`, `pc`, `px_height`, `px_width`, `ram`, `sc_h`, `sc_w`, `talk_time`, `three_g`, `touch_screen`, `wifi`

---

## 🛠️ Installation & Setup

### 1. Clone the Repository
```bash
git clone [https://github.com/yourusername/mobile-price-predictor.git](https://github.com/yourusername/mobile-price-predictor.git)
cd mobile-price-predictor
````

### 2\. Install Dependencies

Make sure you have Python 3.8+ installed, then run:

```bash
pip install -r requirements.txt
```

### 3\. Add Your Model File

Place your trained model file `best_model.pkl` inside the project folder.

### 4\. Run the Streamlit App

```bash
streamlit run app.py
```

-----

## 📊 Usage

1.  Open the Streamlit web interface (it should automatically open in your browser).
2.  Enter the mobile specifications in the input fields.
3.  Click **Predict Price Range** to get the prediction.

**Example prediction output:**

> Predicted Price Range: 💵 Medium Cost

-----

## 🧩 Project Structure

```
mobile-price-predictor/
│
├── app.py                # Streamlit web app
├── best_model.pkl        # Trained ML model (add your own)
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

-----

## 🧰 Tech Stack

  - Python
  - Streamlit
  - scikit-learn
  - NumPy

----
