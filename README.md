EV Fleet Monitoring System

An IoT-based smart monitoring system designed to track, analyze, and visualize real-time electric vehicle (EV) data through an interactive web dashboard.
This project integrates hardware sensors, cloud/backend processing, and a frontend dashboard to provide a complete solution for monitoring EV performance and safety.

 Key Features
1)Real-time GPS Tracking
Tracks vehicle location using GPS module and displays it on a map interface.
2) Battery Monitoring
Monitors battery voltage/status to ensure optimal performance and detect issues early.
3) Environmental & Safety Monitoring
Uses sensors (like MPU6050, temperature sensors, etc.) to detect abnormal conditions.
4) Alerts & Notifications
Triggers alerts (e.g., temperature breach, abnormal motion) and displays them on dashboard.
5) Live Dashboard Visualization
Displays all incoming data in a clean, user-friendly web interface.

System Architecture
The system follows a full-stack IoT pipeline:
Hardware Layer
ESP32 collects data from sensors (GPS, MPU6050, battery, etc.)
Data Transmission
Data is sent as JSON packets over WiFi
Backend Server
Built using Node.js
Handles API requests and processes incoming sensor data
Database / Cloud
Stores historical data for analysis and tracking
Frontend Dashboard
Displays real-time data, alerts, and vehicle status

What Makes This Project Unique
Combines IoT + Web + Real-time monitoring in one system
Designed to be cost-effective and scalable, suitable for Indian EV ecosystem
Supports live tracking + predictive alerting
Modular architecture (easy to expand with more sensors/features)

Use Cases
EV fleet management companies
Logistics and delivery tracking
Smart vehicle monitoring systems
Academic and research projects
