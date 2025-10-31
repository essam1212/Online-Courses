# 📚 Online Courses Data Analysis Dashboard (Power BI)

This project presents an **interactive data analysis dashboard** built using **Microsoft Power BI** to evaluate the **performance, pricing, and content quality** of online courses.  

The dashboard delivers **actionable insights** into subscriber behavior, content value perception, and subject popularity — helping to guide strategic decisions in **content creation and pricing**.

---

## ✨ Project Structure & Key Analysis

The dashboard is structured into **three main analytical pages**:

---

### 1️⃣ Overview Page (Performance & Content)

- **Key KPIs:**  
  - 3,676 Courses  
  - 147K Lectures  
  - 574K Reviews  
  - 11.7 Million Subscribers  

- **Subject Popularity:**  
  - *Web Development* dominates with **7.9M subscribers**, far exceeding other subjects.  

- **📊 Critical Insight – Content Gap:**  
  Although Web Development leads in subscribers, **Business Finance** has nearly the same number of courses.  
  ➤ This highlights an inefficiency in content allocation — suggesting a **need to increase Web Development courses** to match learner demand.  

- **Content Trends:**  
  - Number of courses grew steadily until peaking in **2016 (1,204 courses)**, then slightly declined in 2017.  

- **Drill-Down Feature:**  
  Implemented **Hierarchy navigation** from Subject → Level (Beginner, Intermediate, Expert) → Course Details for deeper exploration.  

---

### 2️⃣ Price Analysis Page (Value vs. Cost)

- **Pricing Overview:**  
  - **Max Price:** $200  
  - **Min Price:** $0  
  - **Average Price:** $66.1  

- **Free vs. Paid Acceptance:**  
  - **Lectures & Reviews:** Paid courses contain **95.5%** of total lectures and **77.01%** of reviews.  
  - **Subscribers:** Paid courses still hold **69.49%** of subscribers — showing high **willingness to pay** for quality content.  

- **💡 Insight – Value vs. Cost:**  
  A deep dive using scatter and categorical analysis reveals that **price is not the main barrier** to subscription.  
  - *Expensive courses (28.25%)* still attract large audiences, proving that **content quality and value outweigh pricing**.  

---

### 3️⃣ Courses Details Page

A detailed table providing filtered insights based on selections from previous pages.  

**Displayed Fields:**  
- Subject  
- Level (Beginner / Intermediate / Expert)  
- Course Title  
- Payment Type (Free / Paid)  
- Price  

---

## 💡 Key Business Insights & Recommendations

1. **Increase Content for Popular Subjects:**  
   Expand Web Development content to meet growing learner demand.  

2. **Balance Course Distribution:**  
   Optimize the number of courses across underperforming subjects to avoid content oversaturation.  

3. **Pricing Strategy Optimization:**  
   Maintain or slightly increase prices for high-value courses — data shows users are willing to pay for quality.  

4. **Content Quality Emphasis:**  
   Since reviews strongly influence subscriptions, focus on improving lecture depth and presentation.  

---

## 🛠️ Tools & Techniques

- **Tool:** Microsoft Power BI Desktop  
- **Data Transformation:** Power Query (M Language)  
- **Custom Calculations:** DAX (Average Price, Min/Max, Subscriber Ratio, Review Percentage)  
- **Visualization:** Donut Charts, Scatter Plots, Line Charts, Hierarchical Drill-Downs  
- **Analysis Focus:** Course Performance, Pricing Sensitivity, Content Supply vs. Demand  

---

## 📎 Project Type
*Personal Learning Project | Data Analytics & Visualization Practice*

---

## 🔗 Repository Overview
This repository includes screenshots and reports of the **Online Courses Dashboard** created in Power BI.  
> *(Data used is simulated and intended for educational purposes only.)*
