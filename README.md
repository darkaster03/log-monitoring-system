# 🚀 Real-Time Log Monitoring & Debugging System

## 📌 Overview

A real-time system to collect, store, analyze, and visualize application logs for monitoring system health and debugging issues.

This project simulates how modern production systems handle logs and detect abnormal behavior such as error spikes.

---

## 🎯 Key Features

* 📥 **Log Ingestion API** – Collect logs from applications via REST endpoints
* 🔍 **Log Filtering & Search** – Query logs by severity, service, and timestamp
* ⚠️ **Error Spike Detection** – Identify abnormal error patterns in near real-time
* 📊 **Dashboard UI** – Visualize logs and monitor system activity
* 🔄 **Real-Time Updates (Optional)** – Live log streaming using WebSockets

---

## 🧠 System Architecture

```
Application → Backend API → Database → Analyzer → Dashboard UI
```

---

## 🛠️ Tech Stack

**Backend**

* Node.js
* Express.js
* MongoDB

**Frontend**

* JavaScript (UI Dashboard)
* *(Can be extended to Angular)*

**Other**

* REST APIs
* WebSockets (optional)

---

## ⚙️ How It Works

1. Applications send logs to the backend API
2. Logs are stored in the database
3. Analyzer checks for abnormal patterns (e.g., error spikes)
4. Dashboard displays logs and system status
5. (Optional) Real-time updates via WebSockets

---

## 📂 Project Structure

```
log-monitoring-system/
│
├── backend/
│   ├── config/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── utils/
│   └── server.js
│
├── frontend/
│   └── index.html
│
└── README.md
```

---
