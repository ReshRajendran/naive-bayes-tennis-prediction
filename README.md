# Tennis Play Prediction using Naive Bayes

A beginner-friendly machine learning project that predicts whether a tennis match will be played based on weather conditions, using the Naive Bayes algorithm.

📌 Overview

This classic classification problem uses weather attributes — outlook, temperature, humidity, and wind — to predict whether tennis will be played (yes/no) on a given day.

🛠️ Tech Stack
* Python
* Scikit-learn (LabelEncoder, MultinomialNB)

🔍 Workflow
* Created a small weather dataset with 14 samples
* Encoded categorical features (outlook, temperature, humidity, wind) using LabelEncoder
* Combined encoded features into a single feature set
* Trained a Multinomial Naive Bayes classifier
* Tested the model with custom weather inputs to predict the outcome

📊 Result

The model successfully predicts play/no-play outcomes based on encoded weather conditions, demonstrating the core logic of Naive Bayes classification on categorical data.

🚀 How to Run
* Clone this repository
* Install dependencies: pip install scikit-learn
* Open the notebook and run all cells

