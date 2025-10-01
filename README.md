# World Important Events – Data Analysis & Classification

This project analyzes a Kaggle dataset of **major world events** (ancient to modern) to explore their global impact.  
The work combines **data preprocessing, feature engineering, sentiment analysis, and machine learning** to uncover patterns and predict event outcomes.

## Project Highlights
- Cleaned and imputed missing values (affected and total population).  
- Engineered an **Impact Score** = (Population Affected ÷ Total Population).  
- Applied **VADER sentiment analysis** on event descriptions.  
- Built visualizations: event frequency by country, top affected populations, word clouds, log–log scatter plots.  
- Compared ML models: Logistic Regression, SVM, Decision Tree, KNN, and Random Forest.  
- Tuned Random Forest with **GridSearchCV**; evaluated using accuracy, precision, recall, F1, and ROC-AUC.  
- Documented dataset imbalance as a limitation.

## Results
- Random Forest achieved the best balanced performance after tuning.  
- Weak correlations found between Impact ↔ Outcome, Sentiment ↔ Outcome, and Impact ↔ Sentiment.  

## Tech Stack
- Python (Pandas, NumPy, scikit-learn, NLTK, Matplotlib, Seaborn, WordCloud)  
- Jupyter Notebook    

## Installation
Clone this repo and install dependencies:
```bash
git clone https://github.com/<your-username>/world-important-events.git
cd world-important-events
pip install -r requirements.txt
