# Interactive Dashboard for Sentiment Analysis  

**A Streamlit-powered dashboard for analyzing customer sentiment on US Airlines using Twitter data.**  

##  Project Overview  
This project aims to analyze customer sentiment toward US Airlines using **Python** and **Streamlit**. The dashboard allows users to explore **positive, neutral, and negative tweets**, visualize sentiment trends, and generate word clouds for insights.  

🔹 **Technologies Used:**  
- Python (Pandas, NumPy, Matplotlib)  
-  Plotly (Interactive Bar Charts, Pie Charts, Maps)  
-  Streamlit (Dashboard UI & Interactivity)  
-  WordCloud (Text Data Visualization)  
-  Twitter US Airlines Dataset (from Kaggle)  

---

## Features  
**Sentiment Analysis Dashboard** – Displays airline sentiment trends using **bar charts and pie charts**  
**Interactive Filters** – Users can select specific airlines or sentiment categories  
**Live Tweet Display** – Shows a random tweet based on selected sentiment  
**Geolocation Mapping** – Displays **tweet locations** using an interactive map  
**Word Clouds** – Generates **most frequent words** for positive, neutral, and negative sentiments  
**User-friendly UI** – Built with **Streamlit widgets and dropdowns**  

---

## Screenshots  
### **Dashboard Overview**  
![Dashboard](./screenshots/dashboard.png)  

### **Sentiment Analysis Charts**  
![Bar Chart](./screenshots/bar_chart.png)  
![Pie Chart](./screenshots/pie_chart.png)  

---

## Installation & Setup  
### 1️⃣ Clone this repository  
```bash
git clone https://github.com/yourusername/sentiment-dashboard.git
cd sentiment-dashboard
```
### 2️⃣ Install dependencies
```
bash
pip install -r requirements.txt
```
### 3️⃣ Run the Streamlit app
```
streamlit run app.py
```
🔹 Open http://localhost:8501/ in your browser to view the dashboard.


## Dataset
The project uses the Twitter US Airlines Sentiment dataset from Kaggle. 
![Link](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)

## Project Report & Presentation
- Report (PDF): ![Here](./Documents/Project_Report.pdf)
- Presentation (PPT): ![Here](./Documents/interactive_dashboard_presentation.pdf)
