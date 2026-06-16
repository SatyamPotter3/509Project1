# 🛡️ 509 Army Base - Offline Network Monitoring System

## 📌 Overview

The **509 Army Base Offline Network Monitoring System** is a secure and lightweight network monitoring solution designed for environments where internet connectivity is restricted or unavailable.

The system provides real-time visibility into network activity, device status, traffic statistics, active connections, and interface health through an intuitive monitoring dashboard.

Built with a focus on security, reliability, and operational awareness, the platform enables administrators to monitor critical network infrastructure without relying on external cloud services.

---

## 🚀 Features

### 🔹 Device Identity Monitoring

* Hostname detection
* IP Address monitoring
* MAC Address identification
* Real-time refresh updates

### 🔹 Live Network Throughput

* Upload Speed Monitoring
* Download Speed Monitoring
* Bandwidth Usage Tracking

### 🔹 Data Transfer Analytics

* Total Data Sent
* Total Data Received
* Aggregate Network Traffic

### 🔹 Packet Monitoring

* Packets Sent
* Packets Received
* Network Activity Statistics

### 🔹 Network Interface Tracking

* Interface Status (UP/DOWN)
* IP Configuration
* MTU Information
* Interface Speed Monitoring

### 🔹 Active Connection Analysis

* Established Connections
* Listening Ports
* Time-Wait Connections
* Total Active Sockets

### 🔹 Secure Offline Deployment

* No internet dependency
* Local network monitoring
* Military-grade deployment suitability
* Reduced attack surface

---

## 🏗️ System Architecture

```text
+-------------------------+
| Network Devices         |
| Routers / Switches      |
| Workstations / Servers  |
+------------+------------+
             |
             v
+-------------------------+
| Monitoring Engine       |
| (Python / Backend)      |
+------------+------------+
             |
             v
+-------------------------+
| Dashboard Frontend      |
| HTML+CSS+js+Bootstrap   |
+-------------------------+
```

---

## 🛠️ Technology Stack

### Frontend

* HTML5
* CSS3
* Bootstrap 5
* JavaScript

### Backend

* Python
* Linux / Kali Linux

### **Database**

SQlite

### Monitoring Components

* Network Interface Monitoring
* Socket Monitoring
* Packet Statistics Collection
* Throughput Analysis

---

## 📂 Project Structure

```text
509Project1/
│
├── NetworkMonitor-Frontend/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── assets/
│
├── Backend/
│   ├── monitoring_scripts/
│   └── network_collectors/
│
├── README.md
│
└── Documentation/
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/509Project1.git
```

### Navigate to Project

```bash
cd 509Project1
```

### Launch Frontend

Open:

```text
index.html
```

or run using a local server.

---

## 📊 Dashboard Modules

| Module             | Description                        |
| ------------------ | ---------------------------------- |
| Device Identity    | Shows host details and identifiers |
| Throughput         | Upload & Download monitoring       |
| Data Transfer      | Sent/Received traffic analytics    |
| Packet Monitoring  | Packet statistics                  |
| Interfaces         | Interface status monitoring        |
| Active Connections | Socket and connection tracking     |

---

## 🎯 Objectives

* Improve situational awareness of network infrastructure.
* Detect unusual network behavior.
* Monitor critical devices in real time.
* Operate in isolated and secure environments.
* Provide an intuitive monitoring dashboard.

---

## 🔒 Security Considerations

* Fully offline deployment
* No third-party cloud dependency
* Local data processing
* Reduced external exposure
* Suitable for restricted operational environments

---

## 📈 Future Enhancements

* Real-time alerts
* Intrusion detection integration
* Historical traffic analytics
* Network topology visualization
* Automated reporting
* Device discovery module

---

## 👨‍💻 Authors

**509 Army Base Monitoring Team**

Developed as a secure network monitoring solution for offline operational environments.

---

### ⭐ If you find this project useful, consider giving it a star.
