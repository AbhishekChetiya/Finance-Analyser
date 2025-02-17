# 📊 Financial Analyser

## 🌟 Introduction
Financial Analyser is a **full-stack web application** that helps users track, analyze, and compare their financial data. Built using **Django (Python) for the backend** and **React.js for the frontend**, this platform provides insightful financial analytics using **Google's Gemini AI model**.

The backend leverages Django's **Serializer** to convert complex data into **JSON format**, and a **custom user model** is implemented by inheriting Django’s built-in **User** model to enhance authentication and user-specific features.

---

## 🚀 Features

### 🔹 User Authentication
- **Custom User Model** based on Django’s built-in authentication system
- Secure authentication using **JWT Tokens**
- Role-based access control (Admin/User)

### 🔹 Financial Data Management
- Users can **input financial transactions** (income & expenses)
- Data is stored in **PostgreSQL** database  **Deployed** on the Render
- Transactions categorized by **date and category**

### 🔹 AI-Powered Financial Analysis
- **Gemini AI model** analyzes financial trends
- Insights provided based on **weekly, monthly, and yearly data**
- **Compare two financial datasets** over different time periods
- Smart **financial improvement suggestions** based on spending & earnings

### 🔹 Data Visualization
- **React-Chart.js** used for financial trend visualization
- Graphical representation of **income vs. expenditure**
- Line charts, bar graphs, and pie charts for **comparative analysis**

### 🔹 User Notifications & Alerts
- Real-time notifications using **Toastify**

### 🔹 Deployment
- **Frontend deployed on Vercel**
- **Backend deployed on Render**

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Django | Backend Framework |
| Django Rest Framework (DRF) | API Development |
| PostgreSQL | Database |
| React.js | Frontend Framework |
| Chart.js | Data Visualization |
| Toastify | Notifications & Alerts |
| Gemini AI | AI-Powered Analysis |

---

## ✨ AI-Powered Analysis with Gemini AI
One of the most powerful features of **Financial Analyser** is its **AI-driven insights**. Using **Gemini AI**, the platform evaluates users' financial data and provides:

- **Spending & saving patterns** over time
- **Predictions & recommendations** for better financial decisions
- **Comparative analysis** between different periods (weekly/monthly/yearly)

Example:
**Input:** User feeds transaction data for the past month
**Output:** "You spent 30% more on dining compared to last month. Consider reducing restaurant expenses to save more."

---

- **Portfolio:** [https://myportfolio-xi-inky-22.vercel.app/](https://myportfolio-xi-inky-22.vercel.app/)
- **Deployed Link:** [https://financial-anaylser.vercel.app/login](https://financial-anaylser.vercel.app/) 

