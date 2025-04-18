# Customer_Churn_Classification__202401100400088
This project is a machine learning pipeline that classifies whether telecom customers are likely to churn based on their usage patterns. It uses a Random Forest Classifier, evaluates performance with key metrics, and saves the trained model for future use.
🚀 Features

    Upload your own dataset (.csv format)

    Auto-detects and converts Churn column to a binary Class target

    Handles preprocessing and scaling

    Trains a RandomForestClassifier

    Displays evaluation metrics (Accuracy, Precision, Recall)

    Shows a confusion matrix heatmap

    Saves trained model and scaler using joblib

🛠️ Technologies Used

    Python 3.x

    Pandas

    Scikit-learn

    Matplotlib

    Seaborn

    Joblib

    Google Colab (for demo/run)

📂 How to Use

    Clone the repository

git clone https://github.com/your-username/churn-classifier.git
cd churn-classifier

    Open in Google Colab

    Open churn_classifier.ipynb in Google Colab

    Upload Your Dataset

    Click the file upload prompt in Colab

    Ensure your dataset includes a Churn or Class column

    Run the Notebook

    Step through the cells

    Review metrics and confusion matrix

    Saved files:

        churn_classifier_model.pkl (trained model)

        scaler.pkl (fitted scaler)

🧪 Dataset Requirements

Your dataset should be a .csv file with:

    A target column named either:

        Churn (values: Yes/No)

        Class (values: 1/0)

    Numeric features (non-numeric columns will be ignored in this simplified version)

📈 Example Output

✅ Accuracy: 0.8342
✅ Precision: 0.7520
✅ Recall: 0.6301

📊 Classification Report:
              precision    recall  f1-score   support
           0       0.85      0.90      0.87       798
           1       0.75      0.63      0.68       292

Confusion Matrix heatmap is also generated.
📥 Output Files

    churn_classifier_model.pkl - Trained model

    scaler.pkl - StandardScaler for inference

📃 License

MIT License © [Divyanshi Verma]
