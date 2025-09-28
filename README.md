# 🧮 *Monthly Budget Calculator*

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Google Colab](https://img.shields.io/badge/Platform-Google%20Colab-yellow.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)
![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red.svg)
![Codecademy Portfolio Project](https://img.shields.io/badge/Codecademy-Portfolio%20Project-purple)

## 👩‍💻 About Me

Hi! I'm **Umaama**, a developer currently building my portfolio through Codecademy...

##  📌 Project Overview

A terminal-based Python program to help users track their monthly income and expenses, calculate savings, and manage their budget—all stored securely in Google Drive.

This program is Designed for anyone, who wants to calculates their monthly icome, expenses and their budget.

### 🚀 Features

- Interactive terminal menu
- Input monthly income and categorize expenses
- View detailed budget summary with percentages
- Save and load budget data using Google Drive
- Edit income and expenses anytime
- Alerts for overspending and savings rate

## 📦 Requirements

- Python 3.x
- Google Colab (recommended for easy access)
- Access to Google Drive (for saving/loading data)

## 💻 How to Run

1. Open the project in [Google Colab](https://colab.research.google.com).
2. Run the first cell to mount your Google Drive:
   ```python

   from google.colab import drive
   drive.mount('/content/drive')
3.  Run the rest of the code cells to start the program.
4. Follow the terminal prompts to create or load your budget.

## 📁 File Management 

Budgets are saved as `budget_username_YYYYMMDD_HHMMSS.json` in your Google Drive. 
These are timestamped versions for history and backup.

A copy is also saved as `budget_username.json`
This acts as the latest version for quick access and editing.

## 📊 Sample Output
After entering your income and expenses, you'll see:
• 	A detailed breakdown of each category
• 	Percentage of income spent per category
• 	Remaining balance and savings rate
• 	A pie chart showing your budget distribution


Thanks for checking out my project! Feel free to explore, use, or improve it—and happy budgeting! 
