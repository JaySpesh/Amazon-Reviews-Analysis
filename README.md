# 📊 Amazon Products Review Analysis  

## 🎯 Executive Summary  
This project analyzes customer reviews for two bedding products **Bedsure bedsheets** and **Breescape bedsheets** based on **data cleaning, exploratory data analysis (EDA), and sentiment analysis** of reviews from 2020–2025.  

---

## 📌 Key Findings  

### 🛏 Bedsure Product  
- **Strong Positive Sentiment** (84.6% of reviews are positive)  
- **Minimal Negative Feedback** (only 8.6%)  
- **Stable Rating Trends** over time  

### 🛏 Breescape Product  
- **Cooling Feature Highly Valued** by customers  
- **Fit Issues Drive Negative Reviews**  
- **Helpful Reviews are Mostly Positive**  

---

## ✅ Recommendations  

### Bedsure Product  
- Highlight strengths in marketing campaigns  
- Address durability & fabric weakness issues  
- Improve customer retention through engagement  

### Breescape Product  
- Leverage its **unique cooling feature (USP)** in promotions  
- Improve design to fix sizing/fit issues  
- Encourage more detailed positive reviews  

---

## 📖 Introduction  

### 1. Background  
The primary objective was to analyze customer reviews for two Amazon products — Bedsure and Breescape — to uncover key **customer sentiments**, identify **pain points**, and provide **recommendations** for product improvement and business strategy.  

### 2. Objectives  
- Clean and prepare raw review data (remove duplicates, fix types, handle missing values)  
- Perform EDA (rating distribution, descriptive stats, trends)  
- Conduct **sentiment analysis** (positive, neutral, negative) using TextBlob  
- Identify insights: dominant sentiments, pain points, and satisfaction drivers  
- Provide actionable business recommendations  
- Compare both products  

### 3. Problem Statement  
To understand customer sentiment and pain points for two competing bedding products, in order to identify what drives **positive and negative feedback** and how to improve product competitiveness.  

### 4. Tools Used  
- **Amazon Review Scraper** (for data collection)  
- **Excel** (data cleaning)  
- **SQL Server** (database creation)  
- **Python** (EDA & sentiment analysis)  
- **Power BI** (dashboards & visualizations)  

---

## 🔎 Analysis  

### 1. Data Cleaning  
- Dropped irrelevant columns (e.g., URLs, empty fields)  
- Handled missing values  
- Standardized data types (ratings → floats, counts → integers, dates → proper date format)  
- Removed duplicates (based on reviewer, review text, date)  

### 2. Database Design & Schema  
Normalized relational schema with:  
- **Product Table** → static product details  
- **Reviewer Table** → unique reviewer info  
- **Review Table** → review text, rating, date (linked to product & reviewer)  

### 3. Data Analysis  
- Conducted EDA in Jupyter Notebook  
- Calculated descriptive statistics & plotted distributions  
- Used TextBlob for sentiment polarity classification  
- Identified rating trends and customer pain points  

### 4. Exploratory Data Analysis (EDA)  
- Bedsure: High ratings, right-skewed distribution, majority positive reviews  
- Breescape: Bimodal distribution → mixed experiences (some love it, some dislike it)  

### 5. Sentiment Analysis  
- **Bedsure**: 84.6% Positive | 8.6% Negative | 6.8% Neutral  
- **Breescape**: Mostly Positive, but notable negative feedback around fit issues  

### 6. Business Meaning  
- **Bedsure**: Strong approval, minor issues with fabric durability  
- **Breescape**: Positive but needs design fixes (fit/size consistency)  

---

## 💡 Actionable Insights  

### Bedsure Product  
- Focus marketing on comfort & softness  
- Investigate durability complaints  
- Engage dissatisfied customers to retain them  

### Breescape Product  
- Emphasize cooling USP in marketing  
- Fix fit and design issues  
- Encourage more detailed customer reviews  

---

## 📊 Visualization  

- **Sentiment Analysis** → Classified ratings (Positive: 4–5, Neutral: 3, Negative: 1–2)  
- **Keyword Analysis** → Word Cloud for common terms  
- **Dashboards** → Power BI visuals for sentiment distribution, trends, keywords  

---

## 📝 Conclusion  

### Bedsure Product  
- ⭐ Strong positive sentiment (84.6%)  
- ⚠️ Negative reviews highlight thinness/durability issues  
- 📈 Stable high rating trends  

### Breescape Product  
- ⭐ Cooling & comfort highly valued  
- ⚠️ Fit issues drive most negative reviews  
- ✅ Helpful reviews are overwhelmingly positive  

### Recommendations  
- **Bedsure** → Emphasize softness, address durability, improve retention  
- **Breescape** → Improve product fit, highlight cooling USP, encourage detailed reviews  

### Challenges  
- Amazon scraping restrictions  
- Difficulty creating sentiment columns (solved with DAX in Power BI)  
- Added Word Cloud add-in to Power BI for keyword analysis  

### Overall Conclusion  
Both products enjoy strong customer approval.  
- **Bedsure**: needs durability fixes.  
- **Breescape**: must resolve fit issues.  
By addressing weaknesses and leveraging strengths, both can improve satisfaction and competitiveness.  

---

## 🛠️ Tech Stack  
- **Python** (Pandas, TextBlob, Matplotlib)  
- **SQL Server** (database design & querying)  
- **Excel** (data cleaning)  
- **Power BI** (dashboard visualizations)  
- **Jupyter Notebook** (analysis & reporting)  
