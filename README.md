# 🌊 Flood Risk Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Overview
A machine learning project that predicts flood risk based on rainfall and river level data. Uses Random Forest Classifier to classify areas as flood-risk or safe zones with 87.5% accuracy.

## 📊 Model Performance

| Metric | Score |
|--------|-------|
| ✅ Accuracy | 87.5% |
| 🎯 Precision | 91.3% |
| 🔁 Recall | 89.1% |
| 📈 F1 Score | 0.90 |

## 🗂️ Dataset
- Custom synthetic flood risk dataset
- 1,000 samples
- Features: `rainfall`, `river_level`
- Target: `flood` (0 = No Risk, 1 = Flood Risk)

## 🛠️ Tech Stack

| Tool | Use |
|------|-----|
| Python | Core language |
| Scikit-learn | Model training |
| Pandas | Data processing |
| NumPy | Numerical operations |
| Matplotlib | Visualization |

## 📁 Project Structure

```
Flood_Risk_ML_Project/
├── data/
│   ├── flood_data.csv        # Dataset
│   └── generate_data.py      # Data generation script
├── src/
│   ├── main.py               # Main training pipeline
│   ├── model.py              # Model definition
│   ├── data_loader.py        # Data loading
│   ├── predict.py            # Prediction script
│   ├── test_model.py         # Model testing
│   └── visualizee.py         # Visualization
├── Results/
│   └── confusion_matrix.png  # Model evaluation results
├── model.pkl                 # Saved trained model
└── README.md
```

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/tisha-rakholiya/Flood_Risk_ML_Project
cd Flood_Risk_ML_Project
```

### 2. Install dependencies
```bash
pip install scikit-learn pandas numpy matplotlib
```

### 3. Train the model
```bash
python src/main.py
```

### 4. Test predictions
```bash
python src/test_model.py
```

## 📉 Confusion Matrix
![Confusion Matrix](Results/confusion_matrix.png)

## 🔍 How It Works
1. **Data Loading** — Reads rainfall and river level data
2. **Preprocessing** — Cleans and prepares features
3. **Model Training** — Trains Random Forest Classifier
4. **Evaluation** — Generates accuracy, F1 score, confusion matrix
5. **Prediction** — Predicts flood risk for new inputs

## 👩‍💻 Author
**Tisha Rakholiya**  
BTech CSE (AI & Data Science) | 3rd Year | Surat, Gujarat

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/tisha-rakholiya-353790320)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/tisha-rakholiya)
