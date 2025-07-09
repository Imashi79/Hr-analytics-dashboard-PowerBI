# HR Analytics Dashboard – Power BI

This project is an interactive HR Analytics Dashboard built in Power BI. It provides insights into key workforce metrics such as employee distribution, promotion readiness, retrenchment risk, service years, and more. The dashboard uses custom measures, calculated columns, and conditional logic to support HR decision-making.

---

## 📊 Project Features

- **3 Report Pages:**

  - ### 🏠 Home  
    High-level overview with employee count, gender split, and navigation  
    ![Home Page](Images/Hr-Homedashboard.png)

  - ### 📋 Details  
    Departmental breakdowns and employee-level metrics  
    ![Details Page](Images/details-page.png)

  - ### ⚙️ Action  
    Flags for retrenchment and promotion readiness  
    ![Action Page](Images/action-page.png)

- **Data Transformations:**
  - Used **Power Query Editor** to clean and shape the dataset
  - Created **conditional columns** (e.g., for status flags)
  - Added **calculated columns** (e.g., service years, performance labels)

- **DAX Measures:**
  - Used `CALCULATE`, `IF`, `DIVIDE`, and other functions
  - Calculated promotion eligibility percentages and retrenchment risk

- **Navigation:**
  - Built an interactive sidebar with **page navigation buttons**

---

## 🧠 Tools Used

- Power BI Desktop  
- Power Query Editor  
- DAX (Data Analysis Expressions)

---

## 🚀 Getting Started

1. Clone the repository or download the `.pbix` file
2. Open the file in **Power BI Desktop**
3. Refresh the data to explore the visuals and interactions

---

## ☁️ Published Report

This dashboard has also been published to the **Power BI Service** for online sharing and collaboration.

### 🔗 Live Report 
> [View Dashboard on Power BI Service](https://app.powerbi.com/groups/me/reports/3e9fd093-3b6c-43ec-9ee5-8b5fb74e6cb0/f412a3322bd2d453187a?experience=power-bi)

---

## 📁 Repository Structure
```
HR-PowerBI-Dashboard/
│
├── HR-powerBi Dashboard.pbix # Main Power BI report file
├── README.md # This file
│
├── Images/ # Dashboard screenshots
│ ├── home-page.png
│ ├── details-page.png
│ └── action-page.png
│
└── data set/ # Sample HR dataset
```
