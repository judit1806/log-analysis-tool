# 🔍 Log Analysis Tool – Python Web Server Log Analyzer

A Python-based, open-source tool for analyzing web server logs with a focus on usability, performance, and actionable insights. This log analyzer helps system administrators and developers gain visibility into server traffic, popular endpoints, suspicious activities, and much more.

---

## 📘 Project Overview

Web server logs (e.g., from Apache or Nginx) contain critical data on how users interact with your site. This tool parses and analyzes these logs to provide:

- ✅ Security monitoring
- ✅ Traffic insights
- ✅ Resource usage tracking

Ideal for:
- System administrators
- DevOps engineers
- Security analysts
- Backend developers

---

## 🚀 Features

- **Request Analysis:** Count and list requests from each unique IP address
- **Top IPs:** Identify the top 5 IPs with the highest number of requests
- **Endpoint Insights:** Find the most frequently accessed endpoints
- **Suspicious Activity Detection:** Detect IPs with excessive failed login attempts
- **CSV Reporting:** Export results to CSV for documentation or sharing

---

## 🧰 Requirements

- Python 3.x
- No external dependencies except standard libraries:
  - `re`
  - `csv`
  - `collections`

Install Python libraries (if needed):

```bash
pip install -r requirements.txt

__installation__
# Clone the repository
git clone https://github.com/judit1806/log-analysis-tool.git

# Navigate to the project directory
cd log-analysis-tool

Usage
Place your log file (e.g., access.log, sample.log) in the project directory.

Run the analyzer:

Place your log file (e.g., access.log, sample.log) in the project directory.

Run the analyzer:
python log_analyzer.py sample.log



