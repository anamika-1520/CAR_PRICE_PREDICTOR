![Screenshot 2025-07-04 022258](https://github.com/user-attachments/assets/4fdf602b-c852-41d8-bab4-64c4167c150a)# 🚗 Car Price Predictor
A machine‑learning web app that predicts the resale price of a car based on its features (company,kms_driven, model, year, fuel type,  etc.).  
Built with Python, Pandas, Scikit‑learn, and Streamlit.

---

## 📸 Demo
*(Adding  a short GIF or screenshot showing a user filling the form and getting a predicted price.)*
![Screenshot 2025-07-04 022258](https://github.com/user-attachments/assets/05adde4c-6ad7-4999-92ab-8b12b51aaa03)


---

## 🚀 Features
- **Interactive form** to input car details  
- **Real‑time price prediction** with a trained Gradient Boosting Regressor  
- **Model explainability** — SHAP feature‑importance plot  
- **Simple, responsive UI** via Streamlit  
- Clean, modular code and **config‐driven training** (YAML)

---

## 🔧 Installation

```bash
# 1. Clone the repo
git clone https://github.com/<anamika-1520>/CAR_PRICE_PREDICTOR.git
cd CAR_PRICE_PREDICTOR

# 2. Create venv & install deps
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt

# 3. Launch the web app
streamlit run app.py
