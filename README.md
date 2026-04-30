<img width="1536" height="1024" alt="ChatGPT Image Apr 30, 2026, 02_11_54 PM" src="https://github.com/user-attachments/assets/d24cf393-4078-4c16-9c1f-68d2039bfd9a" /># Materials-AI-Fatigue-Life-Prediction-Platform
End-to-end AI system integrating:  Physics-informed machine learning Fatigue life prediction SHAP explainability RAG-based literature intelligence REST API deployment

materials-ai-fatigue-life-prediction/
│
├── app/                        # Core application
│   ├── main.py                # Flask API entry point
│   ├── routes.py              # API routes (/predict, /rag, etc.)
│   ├── model.py               # ML model loading & prediction
│   ├── preprocessing.py       # Data cleaning & feature engineering
│   ├── explain.py             # SHAP explainability
│   ├── rag.py                 # RAG pipeline (FAISS + embeddings)
│   └── utils.py               # Helper functions
│
├── models/                    # Trained models
│   ├── rf_model.pkl
│   ├── scaler.pkl
│   └── feature_columns.json
│
├── data/                      # Dataset
│   ├── raw/                   # Raw extracted data
│   ├── processed/             # Cleaned dataset
│   └── sample_input.csv
│
├── notebooks/                 # Research & experiments
│   ├── EDA.ipynb
│   ├── model_training.ipynb
│   └── feature_engineering.ipynb
│
├── frontend/                  # Optional UI
│   ├── index.html
│   ├── styles.css
│   └── app.js
│
├── docker/                    # Deployment
│   ├── Dockerfile
│   └── docker-compose.yml
│
├── tests/                     # Unit tests
│   ├── test_api.py
│   └── test_model.py
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore



