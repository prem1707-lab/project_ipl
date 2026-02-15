🏏 Cricket Deliveries Analysis & Machine Learning

This project explores ball-by-ball cricket match data and applies machine learning techniques to model match events and scoring patterns.

The dataset contains detailed delivery-level information including overs, ball numbers, players involved, runs scored, extras, and wicket events. Using this granular data, the project demonstrates how predictive models can be built for sports analytics.

📊 Dataset

The dataset consists of delivery-level cricket data, where:

Each row represents one ball bowled

Features describe match context, players, and outcomes

Suitable for classification and regression tasks

Example attributes include:

Match & innings context (match_id, inning, over, ball)

Teams (batting_team, bowling_team)

Players (batter, bowler, non_striker)

Outcomes (batsman_runs, extra_runs, total_runs, is_wicket)

🎯 Project Objectives

This project focuses on applying ML models to cricket data, such as:

✔ Predicting runs scored per delivery (Regression)
✔ Predicting wicket occurrence (Classification)
✔ Understanding scoring patterns & match dynamics

🤖 Machine Learning Approach

Depending on the task:

Regression Task

Predicting total_runs using match context features.

Models explored:

Linear Regression (baseline)

Potential extensions: Random Forest, XGBoost

Classification Task

Predicting is_wicket (whether a wicket falls on a delivery).

Models explored:

Logistic Regression (baseline)

Potential extensions: Tree-based models

🛠️ Tech Stack

Python

Pandas – Data manipulation

Scikit-learn – Machine learning models

NumPy – Numerical operations

📈 Key Learnings

Handling structured sports data

Avoiding data leakage in ML

Feature selection & preprocessing

Model evaluation for regression vs classification

🚀 Future Improvements

Planned enhancements:

Advanced feature engineering

Handling class imbalance for wicket prediction

More powerful models (Random Forest / XGBoost)

Visualizations & EDA

Player-level performance metrics
