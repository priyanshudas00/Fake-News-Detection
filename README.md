# Fake-News-Detection-Machine-Learning

📰 Fake News Detection Using Machine Learning
A Streamlit-based web application that detects whether a news headline is fake or real using Natural Language Processing (NLP) and Logistic Regression. Built using Python, this project combines machine learning with an interactive UI for real-time predictions.

🚀 Project Features
✅ Real-time fake news detection

🧠 Logistic Regression ML model

🧹 Data cleaning, stemming, and vectorization

📊 TF-IDF based text representation

🌐 Simple and elegant web interface (Streamlit)

📁 Uses Kaggle’s fake news dataset (train.csv)

🗂️ Project Structure
bash
Copy
Edit
Fake-News-Detection-main/
│
├── app.py                         # Main Streamlit application
├── train.csv                     # Dataset used for training
├── Fake News Detector.ipynb      # Exploratory Data Analysis + Model
├── Scam Detection.ipynb          # Similar project variation (scam detection)
├── Face News Prediction Model.ipynb  # Additional modeling notebook
└── README.md                     # Project documentation
📦 Installation & Setup Instructions
Clone the Repository


git clone https://github.com/your-username/Fake-News-Detection.git
cd Fake-News-Detection-main
Install Dependencies
Make sure you have Python 3.7+ installed. Then install required packages:


pip install -r requirements.txt
Or manually install:


pip install streamlit pandas scikit-learn nltk
Download NLTK Resources


import nltk
nltk.download('stopwords')
Run the App


streamlit run app.py

📚 Dataset Information
Source: Kaggle Fake News Dataset

Columns used:

label (0 = Real, 1 = Fake)

**🧠 Model Details**
Preprocessing:

Combine author and title

Remove punctuation and stopwords

Apply stemming using PorterStemmer

Feature Extraction:

TF-IDF Vectorization

**Model:**

Logistic Regression

Evaluated with accuracy_score



**🛠️ Future Improvements**
Add support for multiple ML models (Random Forest, SVM, BERT)

Improve UI/UX with more advanced design

Implement API integration for live news detection

Add user feedback and explainability features

**🤝 Contributing**
Feel free to fork and enhance the model or web UI. Pull requests are welcome!

**📄 License**
This project is licensed under the MIT License.
