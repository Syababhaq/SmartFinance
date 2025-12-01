
# 📱 Smart Finance Manager

Smart Finance Manager is a comprehensive personal finance application built with Flutter. It helps users track cash flow, plan budgets with specific frequencies (Daily / Weekly / Monthly), manage debts with due-date notifications, and visualize financial health through dynamic charts. 

(Go to release to download SmartFinance.apk)

---

## 🚀 Getting Started (User Guide)

### 1. Configure Your Baseline
Before logging expenses, tell the app about your stable finances.

- Open the **Analysis** tab (bottom menu).
- Tap **Fixed Income & Bills**.
- Enter your:
  - **Total Monthly Income** — your salary or primary income source.
  - **Fixed Billings** — rent, internet, phone, etc.
  - **Insurance** — fixed monthly premiums.
  - **Other Expenses** — any other fixed monthly commitments.
- Tap **Save**.

> **Note:** The app calculates your **Net Balance** starting from this baseline.

---

## 📊 Dashboard (Overview)

The Home screen gives you an instant snapshot of your financial health.

### Key Metrics
- **Net Balance (Now):** The actual cash you have left for the month.  
  **Formula:** `(Income - Fixed Bills) - Actual Spending`

- **Est. Savings (Projected):** How much you'll save if you stick to your planned budget limits.  
  **Formula:** `(Income - Fixed Bills) - (Total Budget Limits)`

### Charts & Insights
- **Motivation Card:** Dynamic feedback based on your spending (e.g., "On Track!" or "Warning: Overspending!").
- **Monthly Pie Chart:** Visualizes spending breakdown for the current month. Tap any section to see the percentage.
- **Did You Know?:** Scroll to the bottom for financial trivia and tips.

---

## 📉 Analysis & Budgeting

Plan your spending and analyze trends.

### Setting Budgets
- Tap **Budget Limits** in the **Analysis** tab.
- Tap the **+** button to create a category (e.g., `Food`, `Transport`).
- Set a **Limit** and a **Frequency**:
  - **Daily:** Resets every day (e.g., lunch money).
  - **Weekly:** Resets every Monday.
  - **Monthly:** Resets on the 1st of the month.
  - **One-time:** Never resets (good for specific projects).

### Reports
- **Spending Trend:** Toggle between Week, Month, or Year views to see a bar chart of your spending history.
- **Breakdown & PDF:** Scroll to the bottom for a detailed list. Tap the **Share** icon (Top Right) to generate and share a PDF report of your expenses.

---

## 💵 Transaction History

Log your variable daily expenses here.

- **Log Expense:** Tap the **+** button.
- Enter **Amount** and **Description**.
- Select a **Category** (from your Budget list).
- Pick a **Date**.
- **Filters:** Use dropdowns at the top to filter by Category or specific Date.
- **Delete:** Tap the Trash icon next to any transaction to remove it.

---

## 💰 Savings Goals

Track long-term targets like a "Vacation" or "New Car".

- Tap **+ Add New Goal**.
- Set the **Target Amount** and **Target Date**.

### Manage Savings
- Tap the **3-dot menu** on any goal card.
- Choose **Deposit** to add money or **Withdraw** to take money out.
- The progress bar turns **Blue** when you reach **100%**!

---

## 💳 Debt Management

Keep track of what you owe and when it's due.

- Tap **+ Add New Debt**.
- Set the **Total Amount** and **Due Date**.

### Visual Alerts
- **Red:** Overdue!
- **Orange:** Due within 3 days.
- **Grey:** Due later.

---

## 📝 My Notes

Take notes to keep as memo.

- Tap **+ Add New Debt**.

- Insert **Title** and **Contents**.

- Tap then note again to edit.

---

## 🔔 Smart Alerts
The app proactively warns you if you are overspending:
- **"Budget Warning"** — triggers when you reach **90%** of a category limit.
- **"Budget Exceeded"** — triggers when you go over **100%**.

---
