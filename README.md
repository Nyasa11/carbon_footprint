# 🌱 AI-Powered Carbon Footprint Tracker

Estimate and reduce your carbon footprint using machine learning. This web app uses advanced models (including TabGNN) to analyze lifestyle inputs and provide actionable recommendations to minimize CO₂ emissions.

## 🔧 Tech Stack

- **Frontend**: Streamlit  
- **Backend**: Flask, Python  
- **ML Models**: TabGNN, CNN, LSTM, GRU, Bi-LSTM, Attention  
- **Database**: PostgreSQL / MongoDB  
- **Libraries**: Scikit-learn, TensorFlow, Pandas, NumPy

## 📌 Features

- Estimate CO₂ based on transport, energy, diet, and shopping habits  
- Tabular Graph Neural Network (TabGNN) model for accurate predictions  
- Compare model performance against deep learning baselines  
- Real-time dashboard with emission trends and reduction tips  
- Scalable design for IoT, smart meters, and carbon credit systems

## 👩‍💻 Setup

```bash
git clone https://github.com/19-aadya/carbon_foorprint.git
cd carbon_foorprint
pip install -r requirements.txt
streamlit run app.py
