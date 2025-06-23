# 📧 Email/SMS Spam Classifier

A simple yet effective **Spam Classifier Web App** built using **Machine Learning** and **Streamlit**. This app can detect whether a given message is **Spam** or **Not Spam** using Natural Language Processing (NLP) techniques.

🔗 **Live Demo**: [Click here to try it out!](https://builtbypurva-spam-classifier.streamlit.app/)

---

## 🚀 Features

- 🔤 Input any email or SMS text.
- 🧹 Cleans and processes the text using NLP (tokenization, stopword removal, stemming).
- 📊 Transforms the text using **TF-IDF vectorization**.
- 🤖 Predicts if the message is **Spam** or **Not Spam** using a trained **Naive Bayes** model.
- 🌐 Deployed on **Streamlit Community Cloud**.

---

## 🛠️ Tech Stack

- **Python 3.11**
- **Streamlit** – UI
- **Scikit-learn** – Model building
- **NLTK** – Text preprocessing
- **Pickle** – Model & vectorizer storage

---

## 📂 Project Structure

📦 spam-classifier/
├── app.py # Main Streamlit application
├── model.pkl # Trained Naive Bayes model
├── vectorizer.pkl # TF-IDF vectorizer
├── requirements.txt # List of dependencies
└── runtime.txt # Python version for deployment


---

## 🧠 How It Works

1. User inputs a message.
2. The message is preprocessed:
   - Lowercased
   - Tokenized
   - Punctuation and stopwords removed
   - Words stemmed
3. The cleaned text is converted into a numerical vector using TF-IDF.
4. The trained Naive Bayes model predicts whether the message is spam.

---

## 🔧 Installation & Usage

### Step 1: Clone the Repository
git clone https://github.com/BuiltByPurva/Spam-Classifier.git
cd Spam-Classifier

### Step 2: Set Up the Environment
python -m venv venv
venv\Scripts\activate   # For Windows

### Step 3: Install Dependencies
pip install -r requirements.txt

### Step 4: Step 5: Run the App Locally
streamlit run app.py


## 🌐 Live Demo
Your project is deployed on Streamlit Community Cloud and can be accessed here:

👉 https://builtbypurva-spam-classifier.streamlit.app/


### 📬 Example Output
Input:
Congratulations! You've won a free vacation to the Bahamas. Reply now!
Prediction: 🚫 Spam

Input:
Hey, can we meet at 7 PM for dinner?
Prediction: ✅ Not Spam


## 🙋‍♀️ Author
### Purva Kamerkar
📎 [LinkedIn](https://www.linkedin.com/in/purva-kamerkar)
