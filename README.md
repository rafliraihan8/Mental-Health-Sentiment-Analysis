# Mental-Health-Sentiment-Analysis
Proyek ini berfokus pada analisis sentimen yang terkait dengan isu kesehatan mental. Tujuan utamanya adalah mengklasifikasikan data teks ke dalam berbagai kategori kesehatan mental untuk lebih memahami sentimen publik dan mengatasi masalah kesehatan mental secara efektif.

### Steps :
1. Data Preparation 

Load Data : Import the dataset containing mental health-related texts and labels.
Clean Data : Handle missing values, remove unnecessary columns, and preprocess text.

2. Text Preprocessing 

Tokenization : Split text into words or tokens.
Stemming : Apply Porter Stemmer to reduce words to their root form.
Vectorization : Convert text data into numerical vectors using TfidfVectorizer.

3.Data Splitting 

Train-Test Split : Divide the dataset into training and testing sets.

4. Model Training 

Train Models : Use classifiers like RandomForest, AdaBoost, ExtraTrees, DecisionTree, and Logistic Regression to train the models on the training data.

5. Model Evaluation

Evaluate Performance : Use metrics such as accuracy and precision to assess model performance.

6. Model Saving 

Save Models : Use Joblib to save the trained models for future use.
