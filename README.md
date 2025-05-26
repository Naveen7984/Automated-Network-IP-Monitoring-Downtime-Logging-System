📌 Project Description
A Python-based real-time network monitoring system that automates the pinging of IP addresses, tracks their online/offline status, logs response times, and calculates precise downtime durations. The system continuously updates a Microsoft SQL Server database and maintains a live status dashboard, with robust error handling and Outlook-based email alert functionality.

🔍 Key Features

Real-Time Monitoring: Continuously pings multiple IP addresses at defined intervals.

Downtime Calculation: Accurately computes downtime based on historical "Up" status records.

SQL Integration: Logs all ping status data into SQL Server tables (ip_ping_status, live_ping_status, PingResponse).

Auto Schema Update: Dynamically adds new IP address columns to the database schema when needed.

Email Alerts: Sends automated error reports via Microsoft Outlook upon script failure.

Customizable Runtime: Easily adjustable monitoring intervals and runtime durations.

Scalable Architecture: Supports adding more IPs and handles long-term logging without code changes.

Executable Conversion: Script has been compiled into a .exe file for deployment.

24×7 Operation: Runs continuously in production, executing every 10 minutes without manual intervention.

🛠️ Tech Stack

Language: Python

Database: Microsoft SQL Server

Libraries: pandas, pyodbc, subprocess, socket, datetime, win32com.client

Platform: Windows (for compatibility with Outlook and the ping command)

Note: This is a demo version of the project, created to showcase the core functionality while adhering to confidentiality policies restricting the sharing of the original production code.

