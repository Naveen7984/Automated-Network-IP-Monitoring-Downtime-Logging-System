# Automated-Network-IP-Monitoring-Downtime-Logging-System

Project Description
A Python-based real-time network monitoring system that automates the pinging of IP addresses, tracks their online/offline status, logs response times, and calculates downtime durations. The system continuously updates a SQL Server database and maintains a live status dashboard, with built-in error handling and Outlook-based alert notifications.

🔍 Key Features:
Real-Time Monitoring: Pings multiple IP addresses at defined intervals.

Downtime Calculation: Accurately computes downtime since the last "Up" state using historical data.

SQL Integration: Stores all ping status logs in SQL Server tables (ip_ping_status, live_ping_status, PingResponse).

Auto Schema Update: Dynamically adds new IP columns if missing in the target SQL tables.

Email Alerts: Sends detailed error reports via Microsoft Outlook if any exception occurs.

Customizable Runtime: Easily adjust monitoring interval and total run time.

Scalable Architecture: Designed for adding more IPs and long-term logging without code changes.

🛠️ Tech Stack:
Language: Python

Database: Microsoft SQL Server

Libraries: pandas, pyodbc, subprocess, socket, datetime, win32com.client

Platform: Windows (for Outlook and ping command compatibility)

