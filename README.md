# 🚗 Car Price Predictor
A machine‑learning web app that predicts the resale price of a car based on its features (make, model, year, mileage, fuel type, transmission, owner count, etc.).  
Built with Python, Pandas, Scikit‑learn, and Streamlit.

---

## 📸 Demo
![App Preview](images/demo.gif)

*(Add a short GIF or screenshot showing a user filling the form and getting a predicted price.)*

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
git clone https://github.com/<your‑username>/car‑price‑predictor.git
cd car‑price‑predictor

# 2. Create venv & install deps
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt

# 3. Train the model (optional — pre‑trained model is included)
python src/train.py --config configs/gb.yml

# 4. Launch the web app
streamlit run app.py
