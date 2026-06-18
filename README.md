# titanic-ml-project
Titanic survival prediction using Machine Learning
# 🚢 Titanic Survival Prediction

A complete end-to-end Machine Learning project predicting Titanic passenger survival.

## 📊 Results
| Model | Accuracy |
|---|---|
| Logistic Regression | 81.56% |
| Random Forest | 80.45% |
| Gradient Boosting | 83.24% |
| SVM | 82.68% |
| XGBoost | 81.01% |
| **Voting Classifier (Best)** | **84.36%** |

## 🛠️ Features Engineered
- `Title` — extracted from passenger name (most important feature!)
- `FamilySize` — SibSp + Parch + 1
- `IsAlone` — travelling alone or not
- `Fare_log` — log transform of Fare
- `AgeBand` — age grouped into bands

## 📁 Project Structure
titanic-ml/

├── data/          # train.csv and test.csv

├── notebooks/     # Jupyter analysis notebook

├── outputs/       # Charts, submission file, summary

└── README.md

## 🔑 Key Insights
- females had 74% survival rate vs 20% for males
- 1st class passengers survived at much higher rates
- Title was the most important feature at 46.4% importance
- Voting Classifier combining GB + RF + SVM gave best results

## 🚀 How to Run
1. Clone the repository
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm`
3. Open `notebooks/titanic_analysis.ipynb`
4. Run all cells

## 📈 Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
