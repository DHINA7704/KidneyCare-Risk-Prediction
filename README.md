# KidneyCare-Risk-Prediction
A machine learning project that predicts the risk of chronic kidney disease (CKD) using patient health records. The model analyzes medical attributes such as blood pressure, sugar levels, and blood cell counts to identify early signs of CKD. Built with RandomForestClassifier to deliver accurate risk assessment.

📊 Dataset

The dataset includes medical details such as:

Blood pressure

Blood sugar levels

Red blood cell count

And several other health indicators

For this project, the dataset file is named CKD_dataset.csv.

🔎 Approach
1. Data Preparation

Load dataset using Pandas

Handle missing values (mean/mode imputation)

Encode categorical values with Label Encoding

2. Feature Engineering (optional)

Create additional features to capture new relationships

Add slight random noise (via NumPy) to test model robustness

3. Model Training

Split data into training & testing sets

Train a RandomForestClassifier

Evaluate results using accuracy and other metrics

✅ Results

The trained model achieved an accuracy of:
Insert accuracy score here

⚙️ Requirements

Python 3.x

pandas

numpy

scikit-learn

▶️ How to Run

Upload the dataset (CKD_dataset.csv) into your environment (e.g., Jupyter or Google Colab).

Run the notebook cells in order.

Tune hyperparameters and try different features to improve accuracy.

🤝 Contributions

You’re welcome to contribute by:

Enhancing preprocessing steps

Trying out alternative ML algorithms

Adding visualizations for insights

Suggesting improvements
