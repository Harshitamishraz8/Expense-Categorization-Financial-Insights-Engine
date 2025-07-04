# Expense-Categorization-Financial-Insights-Engine
---

````markdown
# 💸 Expense Categorization + Financial Insights Engine

An AI-powered tool to analyze financial transactions, auto-categorize expenses, and provide intelligent financial insights. Built using Python in Google Colab.

---

## 🚀 Features

- ✅ Reads `.csv` file of bank transactions  
- ✅ Auto-categorizes expenses (Food, Shopping, EMI, etc.) using rule-based logic  
- ✅ Generates monthly summaries with savings reports  
- ✅ Interactive charts:
  - 🥧 Expense breakdown by category
  - 📈 Monthly spending trend
- ✅ Smart insights:
  - "Your EMI takes up 32% of your income"
  - "You spent ₹1800 on subscriptions this month"
- ✅ Built-in chatbot:
  - 💬 "What did I spend on Swiggy?"
  - 💬 "How much did I spend on food last month?"
  - 💬 "Show expenses in March 2024"

---

## 📁 Sample Input Format

`fake_transactions.csv`:
```csv
Date,Description,Amount,Transaction Type,Category
2023-07-01,Zomato,400,Debit,
2023-07-05,Monthly Salary,50000,Credit,
2023-07-08,Netflix,650,Debit,
...
````

---

## 📊 Visualizations

* 📈 Monthly expense trend line plot
* 🥧 Pie chart of expenses by category
* 📋 Income vs Expense monthly summary
* 📢 Financial insight generator

---

## 💬 Chatbot Sample Queries

> 💬 What did I spend on Amazon?
> 💬 How much did I spend on food last month?
> 💬 Show my expenses in May 2024

---

## 🛠 Tech Stack

* Python (Pandas, Matplotlib, Regex)
* Google Colab
* Rule-based NLP
* Optional: Streamlit for UI

---

## 🧪 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/expense-insights-engine.git
   ```

2. Open `Expense_Insights_Colab.ipynb` in [Google Colab](https://colab.research.google.com/)

3. Run all cells in order:

   * Generates fake data
   * Categorizes expenses
   * Shows charts & summaries
   * Starts chatbot for queries

---

## 🌱 Future Enhancements

* GPT/BERT-based smart query engine
* Real-time SMS transaction extraction
* Streamlit dashboard interface
* Personal finance goals + budget tracker
