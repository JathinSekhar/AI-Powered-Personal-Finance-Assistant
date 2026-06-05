# AI-Powered Personal Finance Assistant

An intelligent full-stack finance management platform that helps users track expenses, analyze spending habits, and generate smart budgeting insights using AI-driven analytics and visualization tools.

---

# 🚀 Features

## 🔐 User Management
- Secure user authentication and authorization
- Multi-user account support
- JWT-based session management

## 💰 Expense Management
- Add, edit, and delete expenses
- Categorize transactions into multiple expense categories
- Filter expenses by date, category, and amount
- Real-time expense tracking

## 🤖 AI-Powered Features
- AI-based spending pattern detection
- Smart budget recommendations based on user habits
- Monthly expense prediction and forecasting
- Automated expense categorization suggestions
- Overspending alerts using spending trend analysis
- Personalized financial insights and savings tips
- Dynamic budget utilization monitoring

## 📊 Analytics Dashboard
- Interactive charts and graphs
- Monthly and yearly expense trends
- Category-wise spending visualization
- Budget tracking dashboard
- Expense summary reports

## ⚡ Performance & Optimization
- Optimized SQL queries with indexing
- Faster data retrieval and analytics processing
- Real-time synchronization between frontend and backend

---

# 🛠️ Tech Stack

## Frontend
- React.js
- Chart.js / Recharts
- HTML5, CSS3, JavaScript

## Backend
- Spring Boot
- REST APIs
- Spring Security
- JWT Authentication

## Database
- MySQL
- Optimized relational schema design

## AI & Analytics
- Spending pattern analysis engine
- Budget forecasting algorithms
- Data-driven recommendation system

## Tools & Technologies
- Git & GitHub
- Maven
- Postman
- IntelliJ IDEA / VS Code

---

# 📂 Project Structure

```bash
AI-Personal-Finance-Assistant/
│
├── backend/
│   ├── controllers/
│   ├── services/
│   ├── repositories/
│   ├── models/
│   ├── security/
│   └── ai-engine/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── charts/
│   └── assets/
│
├── database/
│   └── schema.sql
│
├── screenshots/
│
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/AI-Personal-Finance-Assistant.git
cd AI-Personal-Finance-Assistant
```

---

# 🔧 Backend Setup

## Configure MySQL Database

Update `application.properties`

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/finance_assistant
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

## Run Backend

```bash
cd backend
mvn spring-boot:run
```

Backend runs on:

```bash
http://localhost:8080
```

---

# 🎨 Frontend Setup

## Install Dependencies

```bash
cd frontend
npm install
```

## Start Frontend

```bash
npm start
```

Frontend runs on:

```bash
http://localhost:3000
```

---

# 🤖 AI Functionalities

## 🧠 Spending Pattern Analysis
The system analyzes historical transactions to identify:
- Frequent spending categories
- High-expense periods
- Monthly spending behavior
- Unusual transaction patterns

## 📈 Smart Budget Prediction
AI forecasting algorithms estimate:
- Expected monthly expenses
- Future savings potential
- Budget risk alerts

## 💡 Financial Recommendations
The assistant provides:
- Personalized savings suggestions
- Budget optimization tips
- Overspending warnings
- Expense reduction insights

---

# 📊 Dashboard Insights

- Expense trends visualization
- Category-wise analytics
- Budget utilization percentage
- Monthly financial summaries
- Smart AI-generated reports

---

# 🧠 Database Optimization

Implemented:
- Indexed frequently queried columns
- Optimized JOIN operations
- Efficient schema normalization

### 🚀 Performance Result
Reduced database query response time by approximately **35%**

---

# 📷 Screenshots

Add screenshots for:
- Login & Registration
- Dashboard
- Expense Tracking
- Analytics Reports
- AI Insights Panel

Example:

```markdown
![Dashboard](screenshots/dashboard.png)
```

---

# 🔮 Future Enhancements

- 📱 Mobile Application
- 🧾 OCR-based receipt scanning
- 🎤 Voice-based expense entry
- 🤖 AI chatbot financial assistant
- ☁️ Cloud deployment with Docker
- 📤 Export reports in PDF/Excel
- 🔔 Smart notifications and reminders

---

# 👨‍💻 Author

## Jathin Sekhar

- GitHub: [JathinSekhar](https://github.com/JathinSekhar)

---

# 📜 License

This project is licensed under the MIT License.

```text
MIT License © 2026 Jathin Sekhar
```
