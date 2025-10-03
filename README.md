# 💰 Money Manager – Personal Finance Tracker

![GitHub repo size](https://img.shields.io/github/repo-size/Roshan-prakhar/Money_Manger)
![GitHub stars](https://img.shields.io/github/stars/Roshan-prakhar/Money_Manger?style=social)
![GitHub forks](https://img.shields.io/github/forks/Roshan-prakhar/Money_Manger?style=social)
![License](https://img.shields.io/github/license/Roshan-prakhar/Money_Manger)

**Money Manager** is a full-stack application designed to help users **track, analyze, and optimize their personal finances**.  
It provides a clean and user-friendly interface to record **income, expenses, and savings**, along with powerful **budgeting tools and insights**.  

Whether you’re a student managing pocket money, a working professional budgeting monthly expenses, or just someone who wants to visualize financial habits — this app is built for you.

---

## ✨ Key Features

### 📝 Transaction Management
- Add income and expenses with description, category, and date  
- Edit or delete existing transactions  
- Categorize transactions (Food, Travel, Shopping, Bills, Salary, etc.)  

### 📊 Budget & Analytics
- Set monthly or custom budgets  
- Track spending against budgets  
- Visual reports and charts for income vs. expenses  

### 📈 Insights
- Daily, weekly, and monthly breakdowns  
- Category-wise expense distribution (Pie/Bar charts)  
- Trend analysis over time  

### 💾 Data Management
- Local database for fast access  
- Export data to CSV/Excel (if implemented)  
- Option to reset or archive old records  

### 🖥️ UI/UX
- Minimalist and responsive design  
- Mobile-friendly interface  
- Dark/Light theme (if implemented)  

---

## 🏗️ Architecture

- **Frontend:** React.js (components for Dashboard, Add Transaction, Analytics, etc.)  
- **Backend:** Spring Boot REST APIs for transaction handling, budgets, and reporting  
- **Database:** H2/MySQL for storing transactions, categories, and budgets  
- **Visualization:** Chart.js / Recharts for analytics  
- **Deployment:** Docker-ready setup (optional)  

```mermaid
flowchart TD
  User[User Interface] --> |React.js| Frontend[Frontend App]
  Frontend --> |REST API| Backend[Spring Boot Backend]
  Backend --> |JPA Queries| DB[(Database: H2/MySQL)]
