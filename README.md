# 🏏 ODI Batting Statistics – Exploratory Data Analysis  

## 📌 Project Overview  
This project is an **Exploratory Data Analysis (EDA)** of ODI (One Day International) batting statistics using **Python, Seaborn, and Matplotlib**.  
It covers **web scraping, data cleaning, and data visualization** to uncover player performance insights and cricketing trends.  

---

## ❓ Problem Statement  
Cricket generates a massive amount of performance data, but raw numbers can be difficult to interpret.  
This project aims to:  
- Identify **top-performing players** based on runs, averages, and strike rates.  
- Compare batting performance across **eras and countries**.  
- Uncover insights into **batting trends and evolution of playing styles**.  

---

## 📂 Dataset  
The dataset was collected via **Web Scraping (BeautifulSoup)**.  
It contains the following columns:  

- Player_Names  
- Country  
- Matches, Innings, Not Outs  
- Total Runs, Highest Score  
- Batting Average  
- Balls Faced  
- Strike Rate  
- 100s (Centuries)  
- 50s (Half-centuries)  

---

## 🛠️ Tools & Technologies  
- **Python** 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, BeautifulSoup  
- **Jupyter Notebook**  

---

## 📊 Key Insights  
- 👑 A few **elite players dominate** in runs & centuries, while most fall in the mid-range.  
- ⚡ **Strike rates have significantly improved** in modern cricket.  
- 📈 Matches strongly correlate with total runs, but **batting averages vary** widely.  
- 🌍 Country-wise, some nations consistently produce top-performing batsmen.  

---

## 📸 Sample Visualizations  
Here are some sample outputs from the analysis:  

![Top 10 Run Scorers](images/top10_runs.png)  
![Strike Rate Distribution](images/strike_rate.png)  
![Correlation Heatmap](images/heatmap.png)  

*(Add your plots as `.png` in an `images` folder and link them here)*  

---

## ▶️ How to Run this Project  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/odi-batting-eda.git
   cd odi-batting-eda
