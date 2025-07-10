# 🧠 Sentiment Analysis using SVM (PHP + Python)

This project performs sentiment analysis on user comments using **Support Vector Machine (SVM)** and is integrated with a **PHP frontend**. It uses **Python** for machine learning and runs locally on **XAMPP (Apache + MySQL + PHP)**.

---

## 📌 Table of Contents
- [📖 Overview](#-overview)
- [🧠 How It Works](#-how-it-works)
- [🛠️ Technologies Used](#️-technologies-used)
- [🚀 How to Run](#-how-to-run)
- [📊 Results](#-results)
- [🤝 Contributing](#-contributing)
- [📃 License](#-license)

---

## 📖 Overview

This project performs sentiment classification (Positive, Negative, Neutral) on user comments from social networking platforms using an SVM classifier. The goal is to predict the sentiment of a given sentence and visualize the results effectively.

---

## 🧠 How It Works

1. Preprocess the text (cleaning, stopwords removal, etc.)
2. Convert text into numerical features using **TF-IDF**
3. Train an **SVM classifier**
4. Predict sentiment for new/unseen text
5. Visualize and evaluate accuracy, precision, and recall

---

## 🛠️ Technologies Used

- 🐍 Python
- 💡 Scikit-learn (SVM, TF-IDF)
- 📊 Pandas, NumPy, Matplotlib
- 🧼 NLTK (for preprocessing)
- 📁 Jupyter Notebook

---

## 🚀 How to Run

### 🔧 Install Dependencies

```bash
pip install -r requirements.txt
▶️ Run the Notebook
bash
Copy
Edit
jupyter notebook Sentiment_Analysis_SVM.ipynb
📄 Sample Dataset
Ensure training.csv is in your project directory. It should contain:

c
Copy
Edit
Text,Sentiment
"I love this product!",Positive
"This is terrible.",Negative
📊 Results
✔️ Accuracy: 90%+

✔️ Handles noisy social media data

✔️ Classifies text into: Positive / Negative / Neutral

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

## 📃 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🌐 Connect With Me

<p align="left">
  <a href="https://www.linkedin.com/in/gayatri-patil-0388a027b/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/linkedin.png" alt="LinkedIn" width="32" height="32"/>
  </a>
  <a href="https://github.com/patilgayatri05" target="_blank">
    <img src="https://img.icons8.com/glyph-neue/48/000000/github.png" alt="GitHub" width="32" height="32"/>
  </a>
</p>

## 🚀 How to Run the Project

## 1. ✅ Requirements

- XAMPP (Download from: https://www.apachefriends.org/index.html)
- Python (3.x)
- Python packages:
  ```bash
  pip install pandas scikit-learn flask
## 2. 📁 Project Folder Setup
Place your entire project folder (e.g. newsportalnew/) inside:

makefile
Copy
Edit
C:\xampp\htdocs\
Make sure your Python script is inside the same project and can be called using shell_exec() from PHP.

## 3. ⚙️ Start Apache Server
Open XAMPP Control Panel

Click Start next to:

Apache ✅

MySQL (if your project uses a database)

## 4. 🌐 Access the Project
Open your browser and go to:

arduino
Copy
Edit
http://localhost/newsportalnew/
Replace newsportalnew with your actual folder name.

## 5. 🐍 Running the Python Sentiment Script (If Needed)
If your PHP page calls a Python file using shell_exec, ensure Python is added to your system path.
