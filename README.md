# Marketing-Analytics-Dashboard
This project analyzes marketing performance using SQL, Python, and Power BI. It includes data cleaning, sentiment analysis, interactive dashboards, and insights presentation.

---

## **Project Overview**  
This project focuses on improving marketing strategies for an online retail business facing reduced customer engagement and conversion rates. It provides a data-driven approach to analyze performance, identify gaps, and recommend optimizations through:
1. **Data Extraction and Cleaning (SQL):** Prepared data using SQL transformations.
2. **Sentiment Analysis (Python):** Enriched customer reviews with sentiment insights.
3. **Interactive Dashboard (Power BI):** Visualized marketing performance and insights.
4. **Stakeholder Presentation (PowerPoint):** Highlighted findings and recommendations.

---

## **Key Features**
- **SQL Transformations:** Cleaned, joined, and categorized data to prepare it for analysis.
- **Sentiment Analysis:** Used Python's Natural Language Toolkit (NLTK) to analyze customer feedback.
- **Power BI Dashboard:** Built an interactive dashboard to showcase trends, KPIs, and insights.
- **Business Insights Presentation:** Compiled key insights into actionable recommendations for stakeholders.

---

## **Project Files**
### **1. Database Backup**
- **`PortfolioProject_MarketingAnalytics.bak`:**
  - SQL Server database backup containing raw marketing data.
  - Includes tables for customer reviews, engagement metrics, and product details.
  - **Usage:** Restore in SQL Server Management Studio (SSMS).

### **2. Power BI Dashboard**
- **`Marketing_Dashboard.pbix`:**
  - Interactive dashboard with visualizations and KPIs.
  - **Usage:** Open with Power BI Desktop.

### **3. Python Notebook**
- **`Sentiment_Analysis.ipynb`:**
  - Python script for sentiment analysis using NLTK.
  - **Usage:** Open in Jupyter Notebook or Google Colab.

### **4. Processed Data**
- **`Customer_Reviews_Sentiment.xlsx`:**
  - Data enriched with sentiment scores and categories.
  - **Usage:** Input for Power BI dashboard.

### **5. SQL Scripts**
- **`Queries.sql`:**
  - SQL queries for data extraction, cleaning, and transformations.
  - **Usage:** Execute in SQL Server Management Studio (SSMS).

### **6. Presentation**
- **`Marketing_Insights_Presentation.pptx`:**
  - Stakeholder-ready slides summarizing insights and recommendations.
  - **Usage:** Open with Microsoft PowerPoint.

---

## **How to Use the Files**

### **Step 1: Restore Database**
1. Open **SQL Server Management Studio (SSMS)**.
2. Right-click **Databases** > **Restore Database**.
3. Select **Device** > Add the `PortfolioProject_MarketingAnalytics.bak` file.
4. Click **OK** to restore the database.

### **Step 2: Run SQL Scripts**
1. Open the **`Queries.sql`** file.
2. Connect to the restored database in SSMS.
3. Execute the queries step-by-step to clean and prepare the data.

### **Step 3: Sentiment Analysis with Python**
1. Open **`Sentiment_Analysis.ipynb`** in Jupyter Notebook or Google Colab.
2. Install required packages (`pandas`, `nltk`, `pyodbc`) if not already installed:
   ```bash
   pip install pandas nltk pyodbc
   ```
3. Execute each cell to process customer reviews and output a CSV file.

### **Step 4: Build Dashboard in Power BI**
1. Open **`Marketing_Dashboard.pbix`** in Power BI Desktop.
2. Refresh data sources to ensure updates reflect processed data.
3. Explore visualizations and insights.

### **Step 5: Presentation**
1. Open **`Marketing_Insights_Presentation.pptx`** in PowerPoint.
2. Review and present insights to stakeholders.

---

## **Project Goals**
- **Increase Conversion Rates:** Identify key drop-off points and optimize marketing funnels.
- **Enhance Customer Engagement:** Evaluate content performance and suggest improvements.
- **Improve Customer Feedback Scores:** Use sentiment analysis to address feedback themes.

---

## **Technologies Used**
- **SQL Server Management Studio (SSMS):** Data extraction, cleaning, and transformation.
- **Python (Jupyter Notebook):** Sentiment analysis with NLTK.
- **Power BI:** Interactive dashboards and visual storytelling.
- **Microsoft PowerPoint:** Business presentations.

---

## **Prerequisites**
- **SQL Server Express or SQL Server Management Studio (SSMS)** installed.
- **Python 3.x** with libraries: `pandas`, `nltk`, `pyodbc`.
- **Power BI Desktop** installed.
- **Microsoft PowerPoint (optional for presentation slides).**

---
