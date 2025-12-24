# 🚀 CryptoCrafters – ML-Powered Market Prediction Dashboard

**CryptoCrafters** is a full-stack web application that visualizes **machine-learning-based price predictions for the next 10 days**, generated using historical market data.  
The project focuses on presenting ML predictions through a **clean, interactive, and production-ready web dashboard**.

🔗 **Live Demo:** https://cryptocrafters.netlify.app

---

## 📌 Project Overview

CryptoCrafters demonstrates how **Machine Learning predictions** can be integrated into a **modern full-stack web application**.

- A Machine Learning model predicts future prices using historical data
- Prediction results are stored in a database
- The frontend fetches, analyzes, and visualizes these predictions using charts and dashboards

This project reflects a **real-world ML + frontend collaboration workflow**.

---

## 🧠 How It Works

1. Historical market data is used to train a **Machine Learning model**
2. The model predicts prices for the **next 10 days**
3. Predicted values are stored in **Supabase**
4. The React frontend:
   - Fetches prediction data
   - Displays insights using cards, tables, and charts
   - Calculates market sentiment, top gainers, and losers

---

## ✨ Features

### 📊 Dashboard
- Prediction cards with trend visualization
- Pagination for large datasets
- Market sentiment indicator
- Top gainers & top losers analysis

### 🔍 Predictions Page
- Search by symbol or name
- Filter by stock/crypto symbol
- Toggle between **Table View** and **Card View**
- Interactive 10-day prediction trend charts

### 🎨 UI & UX
- Fully responsive design
- Modern dark theme
- Smooth loading, empty, and error states

---

## 🛠 Tech Stack

### Frontend
- **React.js**
- **Vite**
- **Recharts**
- **React Router**

### Backend / Database
- **Supabase (PostgreSQL + APIs)**

### Deployment
- **Netlify**

---

## 🤝 Team Contributions

### 👨‍💻 My Role – Full-Stack Development
- Designed and built the complete frontend architecture
- Integrated Supabase for data fetching, filtering, and pagination
- Implemented charts, dashboards, and market sentiment logic
- Handled routing, state management, and UI/UX
- Deployed the application on Netlify

### 🧠 Machine Learning (Teammate Contribution)
- Built and trained the ML model
- Generated 10-day price predictions using historical data

> This mirrors real-world collaboration between ML engineers and frontend developers.

---


---

## 🚀 Getting Started (Local Setup)

```bash
# Clone the repository
git clone https://github.com/your-username/cryptocrafters.git

# Install dependencies
npm install

# Start development server
npm run dev

Configure your Supabase credentials inside supabaseclient.js.
