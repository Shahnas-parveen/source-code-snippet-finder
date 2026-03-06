# 🔎 Source Code Snippet Finder

A Flask-based web application that allows users to search and retrieve Python code snippets efficiently using Information Retrieval techniques.

The system uses **TF-IDF (Term Frequency–Inverse Document Frequency)** and an **Inverted Index** to rank and return the most relevant code snippets based on user search queries.

---

# 📌 Project Objective

The objective of this project is to develop a **web-based Information Retrieval system** that enables users to quickly locate useful Python code snippets by entering programming-related keywords.

This project demonstrates:

- Web application development using **Flask**
- Implementation of **Information Retrieval techniques**
- Code snippet indexing and searching
- Version control using **Git and GitHub**
- Deployment on a cloud platform

---

# 🚀 Live Application

Access the deployed project here:

👉 https://source-code-snippet-finder.onrender.com

---

# 🛠️ Tools and Technologies

- **Python**
- **Flask Framework**
- **TF-IDF Algorithm**
- **Inverted Index**
- **HTML / CSS**
- **Git & GitHub**
- **Render (Cloud Deployment)**

---

# 📂 Project Structure
```
source-code-snippet-finder/
│
├── code_snippets/
│ ├── binary_search.py
│ ├── db_connection.py
│ ├── linear_search.py
│ ├── login_validation.py
│ ├── queue.py
│ └── stack.py
│
├── templates/
│ └── index.html
│
├── app.py
├── snippet_finder.py
├── requirements.txt
└── README.md
```
---

# ⚙️ Installation Steps

Follow these steps to run the project locally.

### 1️⃣ Clone the repository

    git clone https://github.com/Shahnas-parveen/source-code-snippet-finder.git


### 2️⃣ Navigate to the project directory

    cd source-code-snippet-finder


### 3️⃣ Install required dependencies

    pip install -r requirements.txt


---

# ▶️ Running the Application

Start the Flask application using:

    python app.py

Then from the output go to:

```
http://127.0.0.1:5000
```

---

# 🔍 How the System Works

1. The user enters a programming keyword in the search box.
2. The system searches through stored Python code snippets.
3. The **TF-IDF algorithm** calculates the relevance score.
4. Snippets are ranked and displayed based on relevance.
5. Users can copy the snippet directly using the **Copy Snippet** button.

# 🌐 Deployment

The application is deployed using **Render Cloud Platform**.

### Deployment Configuration

**Build Command**

     pip install -r requirements.txt


**Start Command**

     python app.py


---

# 📌 Live Application

Access the deployed project here:

👉 https://source-code-snippet-finder.onrender.com

---

# 👩‍💻 Author

Developed as part of an **Information Retrieval (IR) course assignment** demonstrating Flask web application development, TF-IDF based search, GitHub version control, and cloud deployment.

---