# World Football Match Outcome Predictor
This project uses real-world FIFA match data and team rankings to predict international football match outcomes (Win/Draw/Loss) using a Random Forest model.

## 🧠 Features Used
- Team FIFA ranks and points
- Recent form (last 5 matches)
- Goals scored/conceded averages
- Tournament type weighting
- Head-to-head win percentage
- Match metadata (city, date, neutral field)

## 📊 Model Performance
- Accuracy: 58.21%
- Precision per class: [Win: 56.58%, Draw: 30.67%, Loss: 59.35%]

## 💻 Tech Stack
- Python, pandas, scikit-learn, seaborn, matplotlib, datetime

## 📁 Dataset
- [`results.csv`](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017)
- [`fifa_ranking`](https://www.kaggle.com/datasets/cashncarry/fifaworldranking)

## Future Steps
- Create a frontend for the predicitions
- Incorporate linear regression
- Increase the accuracy 
