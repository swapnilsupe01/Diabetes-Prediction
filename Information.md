🧠 Type of Model Used in the Diabetes Prediction Website
➤ 1️⃣ Nature of the Problem

The goal is to predict whether a person is likely diabetic or not, based on input features such as:

Age

BMI

Glucose level

Insulin

Blood Pressure

Pregnancies, etc.

So the output (target variable) has only two possible values:

1 → Diabetic

0 → Non-Diabetic

That means it’s not a regression problem (which predicts continuous values),
but a classification problem (predicts categories).

🧩 2️⃣ Model Type (According to Data Mining Concepts)
Category	Example Algorithms	Purpose
Classification ✅	Logistic Regression, Decision Tree, Random Forest, SVM, KNN	To predict categorical outcomes like diabetic or not
Regression	Linear Regression, Polynomial Regression	To predict continuous numeric outcomes (e.g., blood sugar level)
Clustering	K-Means, Hierarchical	To group similar patients (not for direct prediction)
Association Rule Mining	Apriori, FP-Growth	To find relationships between health attributes
Dimensionality Reduction	PCA	To reduce feature complexity

So, your Diabetes Prediction Website uses a Classification Model.

⚙️ 3️⃣ Typical Model Used

Most open-source diabetes prediction systems (like yours) use one or more of these models:

Logistic Regression (most common for binary outcomes)

Random Forest Classifier (for higher accuracy and robustness)

Support Vector Machine (SVM) (good for small-to-medium datasets)

K-Nearest Neighbors (KNN) (simple and interpretable)

If the dataset used is Pima Indians Diabetes Dataset, logistic regression or random forest are the usual top performers.

🧮 4️⃣ Example Conceptual Workflow (as per Data Warehousing & Mining)
Step	Data Mining Concept	Description
1️⃣ Data Collection	Data Warehouse	Collect health data (age, glucose, BMI, etc.)
2️⃣ Data Cleaning & Transformation	ETL Process	Handle missing values, scale data
3️⃣ Data Splitting	Model Preparation	Split into training/testing sets
4️⃣ Model Training	Classification Algorithm	Train using Logistic Regression / Random Forest
5️⃣ Evaluation	Model Assessment	Use Accuracy, Precision, Recall, F1-score
6️⃣ Deployment	Predictive Application	Flask backend + React frontend for user predictions
✅ Final Answer:

Your Diabetes Prediction Website uses a Classification Model (usually Logistic Regression or Random Forest) — based on Data Mining concepts of supervised learning, where the goal is to classify users as diabetic (1) or non-diabetic (0).