# Personal Finance Tracker Python Mini Project

A simple yet powerful **Personal Finance Tracker** built with Python, allowing users to track income, expenses, recurring transactions, and gain insights through a command-line interface and Jupyter notebook interface. Data is stored in-memory and can be exported/imported via CSV.

---

## 📌 Features

- ✅ Add income and expense transactions
- 🔁 Supports recurring transactions with frequency (daily, weekly, monthly, yearly)
- 🔍 Search transactions by category
- 📊 View financial summary (income, expenses, savings)
- 📈 Insights: Highest spending category
- 🧹 Delete transactions by category
- 🗃️ Export and Import transactions using CSV
- 📅 Date validation and formatting included
- 💾 Handles one-time and recurring transactions separately

---

## 🧰 Technologies Used

| Tool          | Purpose                         |
|---------------|----------------------------------|
| Python        | Core language                   |
| pandas        | Data export/import              |
| datetime      | Date handling                   |
| Jupyter       | Interactive notebook interface  |

---

## 🚀 How to Run

### Option 1: Run in Jupyter Notebook

1. Open the `personal_finance_tracker_surya-updated.ipynb` in Jupyter Notebook.
2. Run all cells step-by-step.
3. Use the terminal-style prompts to interact.

### Option 2: Convert to Python Script

You can export the notebook as a `.py` file using:
```bash
jupyter nbconvert --to script personal_finance_tracker_surya.ipynb
