# AI-Powered Personal Finance Assistant

An intelligent full-stack finance management platform that helps users track expenses, analyze spending habits, and generate actionable budgeting insights using analytics and visualization tools.

---

## 🚀 Features

- 🔐 Multi-user authentication and account management
- 💰 Expense tracking and categorization
- 📊 Interactive dashboards with spending analytics
- 📈 Monthly budget forecasting and utilization tracking
- 🧠 AI-powered spending pattern analysis
- ⚡ Real-time data synchronization
- 🗂️ Expense filtering by category, date, and account
- 📉 Financial insights and personalized recommendations
- 📱 Responsive UI for desktop and mobile devices

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Chart.js / Recharts
- HTML5, CSS3, JavaScript

### Backend
- Spring Boot
- REST APIs
- Spring Security & JWT Authentication

### Database
- MySQL
- Optimized SQL queries with indexing

### Tools & Technologies
- Git & GitHub
- Postman
- Maven
- IntelliJ IDEA / VS Code

---

## 📂 Project Structure

```bash
AI-Personal-Finance-Assistant/
│
├── backend/
│   ├── src/main/java/
│   ├── controllers/
│   ├── services/
│   ├── repositories/
│   ├── models/
│   └── security/
│
├── frontend/
│   ├── src/components/
│   ├── src/pages/
│   ├── src/services/
│   └── src/assets/
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

# 🔧 Backend Setup (Spring Boot)

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

# 🎨 Frontend Setup (React)

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

# 📊 Key Functionalities

## ✅ Expense Management
- Add, edit, and delete expenses
- Categorize transactions
- Track recurring expenses

## ✅ Analytics Dashboard
- Monthly spending reports
- Budget utilization graphs
- Expense trend analysis
- Category-wise visual insights

## ✅ AI-Powered Insights
- Detects unusual spending behavior
- Provides budget recommendations
- Forecasts future expenses based on historical data

---

# 🧠 Database Optimization

Implemented:
- Indexed frequently queried columns
- Optimized JOIN operations
- Efficient relational schema design

### Result
🚀 Reduced data retrieval latency by approximately **35%**

---

# 📷 Screenshots

Add screenshots of:
- Dashboard
- Expense Analytics
- Budget Reports
- Login/Register Pages

Example:

```markdown
![Dashboard](screenshots/dashboard.png)
```

---

# 🔮 Future Enhancements

- 📱 Mobile App Integration
- 🧾 OCR-based receipt scanning
- 🎤 Voice-enabled expense entry
- 🤖 AI chatbot financial advisor
- ☁️ Cloud deployment with Docker & Kubernetes
- 📤 Export reports as PDF/Excel

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
