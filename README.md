# 🌍 Air Quality Index (AQI) Monitoring System

## 📖 Project Overview

The Air Quality Index (AQI) Monitoring System is a web-based application developed using Advanced Java technologies to monitor, manage, and analyze air quality data. The system helps users track pollution levels, understand air quality conditions, and receive health recommendations based on AQI values.

The application provides a centralized platform for storing pollutant information, generating AQI reports, and visualizing environmental data through an easy-to-use interface.

---

## 🚀 Key Features

### User Features

* View current AQI status.
* Monitor pollutant levels (PM2.5, PM10, CO, NO₂, SO₂, O₃).
* Access AQI reports and historical data.
* Receive health recommendations based on AQI categories.
* User-friendly dashboard for data visualization.

### Admin Features

* Add, update, and delete air quality records.
* Manage pollutant information.
* Generate AQI analysis reports.
* Monitor environmental trends.
* Manage user accounts and system data.

---

## 🛠️ Technology Stack

| Technology    | Purpose                   |
| ------------- | ------------------------- |
| Java          | Backend Development       |
| JSP           | Dynamic Web Pages         |
| Servlets      | Request Processing        |
| JDBC          | Database Connectivity     |
| MySQL         | Database Management       |
| HTML5         | Structure                 |
| CSS3          | Styling                   |
| JavaScript    | Client-Side Functionality |
| Apache Tomcat | Application Server        |

---

## 📊 AQI Parameters Monitored

| Pollutant | Description               |
| --------- | ------------------------- |
| PM2.5     | Fine Particulate Matter   |
| PM10      | Coarse Particulate Matter |
| CO        | Carbon Monoxide           |
| NO₂       | Nitrogen Dioxide          |
| SO₂       | Sulfur Dioxide            |
| O₃        | Ozone                     |

---

## 🏗️ System Architecture

```text
User Interface (JSP)
         │
         ▼
     Servlets
         │
         ▼
 Business Logic
         │
         ▼
        JDBC
         │
         ▼
      MySQL
```

---

## 📸 Screenshots

### Home Page

![Home Page](screenshots/home.png)

### AQI Dashboard

![AQI Dashboard](screenshots/dashboard.png)

### Pollutant Monitoring

![Pollutant Monitoring](screenshots/pollutants.png)

### AQI Report

![AQI Report](screenshots/report.png)

### Admin Panel

![Admin Panel](screenshots/admin.png)

> Create a folder named **screenshots** and place your project images inside it.

---

## 📂 Project Structure

```text
AQI-Monitoring-System
│
├── src/
│   ├── servlets/
│   ├── dao/
│   ├── model/
│   └── utility/
│
├── WebContent/
│   ├── css/
│   ├── js/
│   ├── images/
│   ├── dashboard.jsp
│   ├── login.jsp
│   └── report.jsp
│
├── database/
│   └── aqi.sql
│
└── README.md
```

---

## ⚙️ Installation Guide

### Prerequisites

* JDK 11 or later
* Apache Tomcat 9+
* MySQL Server
* Eclipse/NetBeans IDE

### Steps

1. Clone the repository

```bash
git clone: https://github.com/ahefaj-sheikh/air-quality-index-monitoring-system
```

2. Import project into Eclipse or NetBeans.

3. Create MySQL database:

```sql
CREATE DATABASE aqi_db;
```

4. Import the SQL script.

5. Update database credentials in JDBC configuration.

6. Deploy on Apache Tomcat.

7. Open browser:

```text
http://127.0.0.1:5500/sheikh_ahefaj_portfolio.html
```

---

## 🔮 Future Enhancements

* Real-time AQI API integration.
* Interactive charts and graphs.
* Email alerts for hazardous AQI levels.
* Mobile-responsive design.
* Location-based AQI tracking.
* Predictive AQI analysis using Machine Learning.

---

## 🎯 Learning Outcomes

* Advanced Java Development
* JSP and Servlet Integration
* JDBC Database Connectivity
* MVC Architecture
* CRUD Operations
* Session Management
* Web Application Deployment

---

## 👨‍💻 Author

**Sheikh Ahefaj**

### Connect with Me

* GitHub: https://github.com/ahefaj-sheikh
* LinkedIn: https://www.linkedin.com/in/sheikhahefaj

---

⭐ If you found this project useful, consider giving it a star on GitHub.
