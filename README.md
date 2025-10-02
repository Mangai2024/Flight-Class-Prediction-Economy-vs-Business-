✈️ **Flight Class Prediction (Economy vs Business)**
📌 **Project Overview**

This project predicts whether a passenger will book an Economy class ticket or a Business class ticket, based on flight-related features such as airline, source city, destination city, departure time, stops, duration, and days left before departure.

📊 **Dataset**

Rows: ~300,000

Columns: 10

**Features include:**

airline, source_city, destination_city, departure_time, arrival_time, stops

duration, days_left, price

Target variable: class (Economy = 0, Business = 1)

⚙️ **Steps Followed**

Data Understanding → Checked dataset structure and target distribution.

Preprocessing → Dropped unwanted columns, encoded target using Label Encoding, applied One-Hot Encoding for categorical features.

Train-Test Split → Divided dataset into 80% training and 20% testing sets.

Model Training → Used Logistic Regression and Random Forest Classifier.

Evaluation → Compared models using Accuracy, Precision, Recall, and F1-score.

📈** Model Performance**

**Logistic Regression**

Accuracy: ~99.95%

Precision, Recall, F1-score: 1.00 for both classes

**Random Forest Classifier
**
Accuracy: **~99.98%**

Precision, Recall, F1-score: 1.00 for both classes

✅ Both models achieved near-perfect accuracy, showing that the dataset features are highly predictive of ticket class.

🚀 **Future Improvements**

Apply cross-validation to further confirm results.

Try advanced models like XGBoost Classifier.

Deploy the model with Streamlit for real-time class prediction.

🏆 Key Takeaway

This project demonstrates how machine learning can accurately predict whether a passenger will book Economy or Business class, providing airlines with valuable insights for customer segmentation and targeted strategies.
