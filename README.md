# 📊 Strategic Product Placement Analysis using Tableau

## 📌 Project Title
**Strategic Product Placement Analysis: Unveiling Sales Impact with Tableau Visualization**

---

## 📝 Project Overview
This project focuses on analyzing the impact of **product positioning strategies** on **sales performance** and **consumer behavior**.  
Using **Tableau visualizations**, the project identifies which product placement strategies (Aisle, End-cap, Front of Store) generate maximum sales.

The final Tableau **Dashboard** and **Story** are embedded into a **Flask Web Application** for easy access through a browser.

---

## 🎯 Project Purpose
Retail companies face strong competition and need data-driven strategies to increase revenue.  
This project helps businesses understand:
- Which product placement is most effective
- Which product category has the highest sales volume
- How promotions influence sales
- Which customer demographics contribute the most
- How seasonal trends and foot traffic affect performance

---

## 📂 Dataset Information
📌 Dataset Name: **Impact of Product Positioning on Sales**  
📌 Source: Kaggle  
🔗 Dataset Link:  
https://www.kaggle.com/datasets/amitvkulkarni/impact-of-product-positioning-on-sales

---

## 🛠️ Technologies Used
| Tool/Technology | Purpose |
|----------------|---------|
| Tableau Desktop | Data visualization & Dashboard creation |
| Tableau Public | Publishing dashboard & story |
| Python Flask | Web integration |
| HTML / CSS | UI templates for dashboard and story |
| Kaggle Dataset | Data source |

---

## 📌 Key Attributes in Dataset
- **Product ID**
- **Product Position** (Aisle, End-cap, Front of Store)
- **Price**
- **Competitor Price**
- **Promotion** (Yes/No)
- **Foot Traffic** (Low/Medium/High)
- **Consumer Demographics**
- **Product Category**
- **Seasonal** (Yes/No)
- **Sales Volume**

---

## ❓ Business Questions Answered
✔ Which product category has the highest average sales volume?  
✔ How does competitor price compare with product price?  
✔ Which product position generates the highest sales volume?  
✔ Which consumer demographic group contributes more sales?  
✔ How does promotion impact price and sales volume?  
✔ How does seasonality affect product category sales?  
✔ How does foot traffic influence sales volume?

---

## 📊 Tableau Visualizations Created
1. **Avg Sales Volume vs Product Category** (Bar Chart)
2. **Competitor Price vs Price** (Dual Axis Bar Chart)
3. **Avg Sales Volume by Category by Product Position** (Stacked Bar)
4. **Consumer Demographics vs Sales Volume** (Donut Chart)
5. **Product Category vs Price** (Pie Chart)
6. **Avg Sales Volume by Category by Season** (Stacked Bar)
7. **Foot Traffic by Avg Sales Volume** (Bubble Chart)
8. **Promotion Impact Table** (Text Table)

---

## 📌 Dashboard & Story
✔ Built an interactive **Tableau Dashboard** combining all visualizations  
✔ Created a **Tableau Story** with 3 scenes explaining insights step-by-step

---

## 🌐 Web Integration (Flask)
The Tableau Public embed codes for dashboard and story are integrated into a Flask web application.

### Flask Pages:
- **Home Page**
- **Dashboard Page**
- **Story Page**

---

## 🏗️ Project Architecture
📌 Dataset (CSV from Kaggle)  
➡ Tableau Desktop (Visualization + Dashboard + Story)  
➡ Tableau Public (Publishing & Embed Code)  
➡ Flask Web App (Embedding dashboard & story)  
➡ End User Access via Browser  

---

## 🚀 How to Run Flask Project
### 1️⃣ Install Requirements
```bash
pip install flask
```
### 2️⃣ Run Flask Application
```bash
python app.py
```
### 3️⃣ Open in Browser
```bash
http://127.0.0.1:5000/
```

## 📁 Project Folder Structure
``` bash
ProductPlacementAnalysis/
│
├── app.py
├── templates/
│   ├── home.html
│   ├── dashboard.html
│   ├── story.html
│
└── static/
    └── css/
        └── style.css
```
## 📌 Tableau Public Links
### 🔗 Dashboard Link:
(https://public.tableau.com/views/ProductPlacementAnalysis_17713332821370/PRODUCTPLACEMENTANALYSIS-DASHBOARD?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### 🔗 Story Link:
(https://public.tableau.com/views/ProductPlacementAnalysis_17713332821370/PRODUCTPLACEMENTANALYSIS-STORY?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## 🎥 Project Demo Video
### 🔗 Demo Video Link:
(https://drive.google.com/file/d/1eHpiqxCTZ5DOxU3hbJVr2cu3D-rCcguX/view)

## 📌 Results Summary
- Clothing category has the highest average sales volume.
- Front of Store placement generates better sales compared to Aisle.
- Promotions improve sales volume significantly.
- High foot traffic areas contribute more sales.
- College students and Families are major consumer groups.

## ✅ Conclusion
This project provides a complete end-to-end solution for analyzing product placement strategies.
The interactive Tableau dashboard and story provide valuable insights to help retail businesses improve sales and optimize product positioning for better revenue growth.

## 🔮 Future Scope
- Add real-time database connection (SQL/MongoDB)
- Perform predictive analytics using Machine Learning
- Improve Flask UI with modern Bootstrap templates
- Add recommendation engine for best placement strategies
