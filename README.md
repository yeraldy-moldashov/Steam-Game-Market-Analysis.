# 🎮 Steam Market Analysis Project

## 📌 Project Description
This project analyzes the PC gaming market using data scraped from Steam. We collected and cleaned data on over 10,000 games to understand pricing strategies, genre popularity, and discount trends.

Goal: Answering business questions like "Which genre has the best discounts?" and "Does higher price mean better quality?".

## 👥 Team Members
* Yermek Zhanerke
* Bakyt Samgar
* Yeraldy Moldashov
* Serikbolov Shynggys
* Ingkar Aktay
* Jiahanka Yeerasili

## 🛠 Tools & Technologies
* Language: Python 3.x
* Libraries: Pandas, NumPy, Seaborn, Matplotlib, Requests, BeautifulSoup.
* Environment: Google Colab / Jupyter Notebook.

## 📂 File Structure
* Part1_Scraper.ipynb - Code for scraping data from Steam (50+ categories).
* Part2_Cleaning.ipynb - Data cleaning and feature engineering (handling nulls, currency conversion).
* Part3_Analysis.ipynb - Exploratory Data Analysis (EDA) with 8 visualizations.
* steam_raw.csv - Raw dataset gathered from the website.
* steam_cleaned.csv - Processed dataset used for analysis.

## 📊 Key Insights (Based on Data)
1. Most Popular Genre: Action games dominate the market (followed by Robots and Magic).
2. Pricing Structure: The market is heavily saturated with Free-to-Play titles (**~80%** of the dataset), while paid games are mostly under $20 (Indie segment).
3. Best Discounts: The best deals are found in the Adventure (~22% avg discount) and Racing categories.
4. Quality vs Price: Expensive games do not guarantee satisfaction. Games with "Mixed" ratings often cost nearly the same as "Overwhelmingly Positive" masterpieces, suggesting that price is not a direct indicator of quality.
5. AAA Market: Only a small fraction of games are priced above $50, showing Steam is primarily an Indie-focused platform.

---
*University Project | Data Science Course*
