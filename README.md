# 🏎️ F1 Williams Predictive Model

This project predicts Formula 1 drivers' race finishing positions using historical data from 2015 to 2025.

## 📥 Data Source
[Kaggle F1 Dataset](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020). Place CSVs in the `data/` folder.

## 🚀 Setup

``bash
pip install -r requirements.txt
python scripts/data_import.py
python scripts/feature_engineering.py
python scripts/train_model.py
