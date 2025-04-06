# 💰 FinTrack - Personal Finance Tracker

FinTrack is a lightweight and intuitive personal finance tracker built with Flask. It helps users manage their income, expenses, savings, and view financial insights through interactive charts and transaction logs.

---

## 🚀 Features

- 🔐 **User Authentication**: Secure login & signup using a CSV-based user database.
- 📊 **Dashboard Overview**:
  - Income vs Expenses (Last 6 Months)
  - Spending Breakdown by Category
- 💸 **Real-time Financial Tracking**:
  - Input monthly income and expenses
  - View savings rate and earned points
- 🛎️ **Expense Alerts**: Notifications if expenses exceed 60% of income.
- 📁 **CSV-Based Storage**: No complex DB setup—data is stored in simple CSV files.
- 📝 **Transaction History**: View and add categorized financial transactions.

---

## 🛠️ Technologies Used

- **Backend**: Python, Flask
- **Frontend**: HTML5, CSS3, JavaScript, Chart.js
- **Database**: CSV files (`accounts.csv`, `tranxtion.csv`)
- **Libraries**: Pandas, SQLite (in-memory for auth check)

---

## 🧑‍💻 Getting Started

### Prerequisites
- Python 3.8+
- Pip

### Install dependencies
```bash
pip install flask pandas
