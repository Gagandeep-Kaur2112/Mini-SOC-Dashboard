# Mini-SOC-Dashboard

A lightweight Security Operations Center (SOC) Dashboard built using Python and Flask. This project monitors authentication logs, detects suspicious login activity, generates alerts, and visualizes security events through an interactive web dashboard.

## Project Overview

The Mini SOC Dashboard simulates basic SOC operations by monitoring log data and identifying potential brute-force attacks. It helps demonstrate core Blue Team concepts such as log analysis, threat detection, alert generation, and security monitoring.

## Features

- Real-time log monitoring
- Failed login detection
- Brute-force attack detection
- Alert generation and storage
- Interactive dashboard
- Security event visualization
- Threat statistics and reporting
- Severity-based alert classification

## Technologies Used

- Python
- Flask
- HTML
- CSS
- JavaScript
- Chart.js
- JSON

## Project Structure

```text
mini-soc-dashboard/
│
├── app.py
├── realtime_monitor.py
├── log_analyzer.py
├── sample.log
├── report.txt
│
├── alerts/
│
├── static/
│
└── templates/
    └── dashboard.html
```

## How It Works

1. The monitoring engine continuously reads authentication logs.
2. Failed login attempts are identified and analyzed.
3. Multiple failed attempts from the same source trigger a brute-force alert.
4. Alerts are stored and displayed on the dashboard.
5. Security statistics and charts provide an overview of detected threats.

## Installation

### Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/mini-soc-dashboard.git
cd mini-soc-dashboard
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Monitoring Engine

```bash
python realtime_monitor.py
```

### Run the Dashboard

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## Dashboard Capabilities

- Alert Monitoring
- Threat Detection
- Brute Force Attack Alerts
- Event Statistics
- Security Visualization
- Real-Time Monitoring

## Cybersecurity Skills Demonstrated

- Security Operations Center (SOC)
- Security Monitoring
- Log Analysis
- Threat Detection
- Incident Identification
- Alert Management
- Blue Team Operations
- Security Event Analysis

## Future Enhancements

- Wazuh Integration
- ELK Stack Integration
- Email Notifications
- Geo-IP Tracking
- MITRE ATT&CK Mapping
- User Authentication
- Multi-Source Log Collection
- SIEM Integration

## Screenshots

Add screenshots of your dashboard here after uploading the project.

Example:

<img width="1014" height="639" alt="Screenshot 2026-06-04 164815" src="https://github.com/user-attachments/assets/bd281b41-bda2-428f-9b62-d1d146a85a52" />



## Author

**Gagandeep Kaur**

Cybersecurity Student | SOC Analyst | Blue Team Enthusiast

---

⭐ If you found this project useful, consider giving it a star.
