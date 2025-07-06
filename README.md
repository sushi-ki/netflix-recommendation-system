# 🎬 Netflix Movie Recommendation System
![Android_Collage_1920x1080__UCAN_En](https://github.com/user-attachments/assets/4cbb6b04-9350-4afe-a32d-d58ed3f3551d)


This project is a **content-based recommendation system** built using a custom dataset (`moviesdta.csv`).  
It analyzes movie metadata and viewer ratings to suggest similar titles, and includes both a visual interface and machine learning backend.

---

## 📌 Features
- 📊 Exploratory Data Analysis (EDA) on the Netflix dataset  
- 🧠 Content-based filtering using **cosine similarity** on genres and descriptions  
- 🎨 Visualizations using **Matplotlib**, **Seaborn**, and **Plotly**  
- 🌐 Frontend UI using custom HTML layout  
- 🗂 Works on a cleaned CSV dataset (`moviesdta.csv`)

---

## 📁 Project Structure

- `netflxsystem.ipynb` – Jupyter Notebook with EDA and ML logic  
- `app.py` – Flask app for running the recommendation system as a web application  
- `index.html`
- `result.html`
- `moviepage.html` 
- `moviesdta.csv` – Cleaned dataset used in this project  
- `requirements.txt` – List of Python dependencies  
- `README.md` – Project documentation (this file)

## 🌐 Hybrid Project Overview

This project simulates a **full-stack ML recommendation system** with two components:

- 🖼 **Frontend UI**: An HTML page (`ntflx.html`) that mimics the Netflix interface — including search bars, filters, and recommendation layout.
- 🧪 **Backend ML Logic**: A Jupyter Notebook (`netflxsystem.ipynb`) containing the content-based recommendation system, built using Python and scikit-learn.

### 🧩 How They Relate

Although the HTML UI is static, and not directly connected to the Python logic, the project structure is designed to **simulate a real-world full-stack deployment**, where:

- The **user interacts with the frontend**, searching or selecting a movie.
- The **backend ML model** processes the input and returns top 5 recommendations.
- (In a live app, this would be done via Flask or Streamlit APIs.)

### 💡 Why This Approach?

This hybrid design demonstrates your understanding of:
- UI/UX in real applications  
- Core machine learning pipelines  
- Full-stack product thinking

---

## ▶️ How to Run

### 🌐  Run as a Web App

1. Install required libraries:
   ```bash
   pip install -r requirements.txt
2.Start the Flask app:
streamlit run app.py


3.Open your browser and go to:
http://172.20.10.2:8501

## 🧾 Requirements
Install with pip:

pip install pandas matplotlib seaborn plotly scikit-learn flask
Or simply use the requirements file:

pip install -r requirements.txt

## 🧠 Techniques Used

Data cleaning and normalization with Pandas
Genre extraction and text pre-processing
NLP with CountVectorizer
Similarity via cosine_similarity
Visualizations: Pie charts, bar plots, heatmaps
Flask routing and dynamic movie recommendations

## 🙋‍♀️ Author

-Kirti Khatri

This Netflix-style content recommender project showcases real-world ML and web integration.
Made with 💖 for learning and demonstrating recommendation systems.













