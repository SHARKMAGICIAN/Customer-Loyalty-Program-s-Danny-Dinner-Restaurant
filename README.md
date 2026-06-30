# 🍜 Case Study: Danny's Diner - Customer Loyalty Program Analysis

An end-to-end data analysis project focusing on customer loyalty, purchase behavior, and menu performance for **Danny's Diner** using **SQL** for data extraction and **Power BI** for visual insights.

---

## 🛠️ Tech Stack & Architecture

- **Database:** PostgreSQL / SQL Server (Data definition and business logic queries)
- **Visualization:** Power BI (`Dashboard visualize insights.pbix`)
- **Presentation:** Microsoft PowerPoint (`Report Presentation.pptx`)
- **Language:** SQL

---

## 📂 Project Structure

```text
├── Create database SQL.txt          # SQL Schema setup and dataset insertion script
├── SQL Analysis insights           # SQL query file containing business logic solutions
├── Dashboard visualize insights.pbix # Interactive Power BI Dashboard
├── Report Presentation.pptx        # Executive presentation deck for stakeholders
├── Objective 1.png                  # Dashboard snippet - Customer Spend Metrics
├── Objective 2.png                  # Dashboard snippet - Product Popularity Analysis
└── Objective 3.png                  # Dashboard snippet - Loyalty Points Tracking
```
---
## 📊 Project Objectives & Visualizations
The project addresses core business problems related to customer spending patterns, most-ordered items, and the effectiveness of the loyalty points program. Below are the key dashboard visualizations answering these objectives:

<table width="100%" cellpadding="5" style="border-collapse: collapse; border: none;">
  <tr>
    <td align="center" style="border: none;"><b>🎯 Objective 1</b></td>
    <td align="center" style="border: none;"><b>🎯 Objective 2</b></td>
    <td align="center" style="border: none;"><b>🎯 Objective 3</b></td>
  </tr>
  <tr>
    <td style="border: none;">
      <img src="Objective 1.png" alt="Objective 1" width="100%" height="auto" />
    </td>
    <td style="border: none;">
      <img src="Objective 2.png" alt="Objective 2" width="100%" height="auto" />
    </td>
    <td style="border: none;">
      <img src="Objective 3.png" alt="Objective 3" width="100%" height="auto" />
    </td>
  </tr>
</table>

---
## 🧠 Business Questions Solved via SQL
The SQL Analysis insights file provides robust queries utilizing Joins, Window Functions, and Common Table Expressions (CTEs) to answer:
1. **Total Spend:** What is the total amount each customer spent at the restaurant?
2. **Visit Frequency:** How many days has each customer visited the restaurant?
3. **First Purchase:** What was the first item from the menu purchased by each customer?
4. **Most Popular Item:** What is the most purchased item on the menu and how many times was it purchased by all customers?
5. **Customer Favorites:** Which item was the most popular for each customer?
6. **Loyalty Impact:** Which item was purchased first by the customer after they became a member?
7. **Pre-membership Behavior:** Which item was purchased just before the customer became a member?
8. **Pre-membership Stats:** What is the total items and amount spent for each member before they became a member?
9. **Points Calculation:** If each $1 spent equates to 10 points and sushi has a 2x points multiplier — how many points would each customer have?
10. **Promo Period Analysis:** In the first week after a customer joins the program (including their join date) they earn 2x points on all items, not just sushi — how many points do customer A and B have at the end of January?

---
## 🚀 How to Review This Project
1. **Database Setup:** Run the scripts inside Create database SQL.txt to set up schemas, tables (sales, menu, members), and records.
2. **Query Verification:** Open and run the business queries in SQL Analysis insights to see analytical results.
3. **Interactive Dashboard:** Open Dashboard visualize insights.pbix in Power BI Desktop to interact with charts and metrics filters.









