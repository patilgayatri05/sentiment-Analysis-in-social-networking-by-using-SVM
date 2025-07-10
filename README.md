# 🧠 Sentiment Analysis using SVM (PHP + Python)

This project performs sentiment analysis on user comments using **Support Vector Machine (SVM)** and is integrated with a **PHP frontend**. It uses **Python** for machine learning and runs locally on **XAMPP (Apache + MySQL + PHP)**.

---

## 🚀 How to Run the Project

### 1. ✅ Requirements

- XAMPP (Download from: https://www.apachefriends.org/index.html)
- Python (3.x)
- Python packages:
  ```bash
  pip install pandas scikit-learn flask
2. 📁 Project Folder Setup
Place your entire project folder (e.g. newsportalnew/) inside:

makefile
Copy
Edit
C:\xampp\htdocs\
Make sure your Python script is inside the same project and can be called using shell_exec() from PHP.

3. ⚙️ Start Apache Server
Open XAMPP Control Panel

Click Start next to:

Apache ✅

MySQL (if your project uses a database)

4. 🌐 Access the Project
Open your browser and go to:

arduino
Copy
Edit
http://localhost/newsportalnew/
Replace newsportalnew with your actual folder name.

5. 🐍 Running the Python Sentiment Script (If Needed)
If your PHP page calls a Python file using shell_exec, ensure Python is added to your system path.

Example in PHP:

php
Copy
Edit
$output = shell_exec("python sentiment.py");
echo $output;
