# 🎬 Netflix Movie Recommendation System
![Android_Collage_1920x1080__UCAN_En](https://github.com/user-attachments/assets/4cbb6b04-9350-4afe-a32d-d58ed3f3551d)


This project is a **content-based recommendation system** built using a custom dataset (`moviesdta.csv`).  
It analyzes movie metadata and viewer ratings to suggest similar titles, and includes a visual, web-based interface using Flask via `app.py`.

---

## 📌 Features

- 📊 Exploratory Data Analysis (EDA) on the Netflix dataset
- 🧠 Content-based filtering using **cosine similarity** on genres and descriptions
- 🎨 Visualizations using **Matplotlib**, **Seaborn**, and **Plotly**
- 🌐 Web app interface using **Flask** (`app.py`)
- 🗂 Works on a cleaned CSV dataset (`moviesdta.csv`)

---

## 📁 Project Structure

Netflix-Recommendation-System/
├── netflxsystem.ipynb # Jupyter Notebook with EDA + ML logic
├── app.py # Flask app for web-based interaction
├── moviesdta.csv # Netflix dataset used in the project
├── requirements.txt # Python dependencies (optional but recommended)
└── README.md # You're reading it!

## 🔍 Dataset Info

The project uses a modified Netflix dataset:
- Filename: `moviesdta.csv`
- Encoding: `'latin-1'`
- Index column: `Title`
- Columns: `Series or Movie`, `ViewerRating`, `Genres`, and other metadata

## ▶️ How to Run

### 🧪 Option 1: Run Jupyter Notebook
bash
jupyter notebook
Open netflxsystem.ipynb
Run all cells
Try exploring the similarity model and visualization outputs

### 🌐 Option 2: Run as a Web App

1. Install required libraries:
   ```bash
   pip install -r requirements.txt
   Start the Flask app:
python app.py
Open your browser and go to:
http://127.0.0.1:5000/

## 🧾 Requirements

Install with pip:

pip install pandas matplotlib seaborn plotly scikit-learn flask
Or simply use the requirements file:

pip install -r requirements.txt

## 🧠 Techniques Used

-Data cleaning and normalization with Pandas
-Genre extraction and text pre-processing
-NLP with CountVectorizer
-Similarity via cosine_similarity
-Visualizations: Pie charts, bar plots, heatmaps
-Flask routing and dynamic movie recommendations

## 🙋‍♀️ Author
Kirti Khatri
This Netflix-style content recommender project showcases real-world ML and web integration.
Made with 💖 for learning and demonstrating recommendation systems.










