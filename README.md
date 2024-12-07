# log-analysis-tool
Log Analysis Tool
A Python-based tool designed to analyze web server logs efficiently. This tool is perfect for gaining insights into server activity, identifying frequently accessed resources, and detecting potential security threats like suspicious login attempts.

Project Overview
Web server logs contain critical information about user interactions and server activity. The Log Analysis Tool provides a comprehensive analysis of these logs, helping system administrators and security professionals monitor server health and security.

Features
Request Analysis: Counts and lists requests made by each IP address.
Top IPs: Highlights the top 5 IPs with the highest number of requests.
Endpoint Insights: Identifies the most frequently accessed endpoint.
Suspicious Activity Detection: Detects IPs with excessive failed login attempts.
CSV Reporting: Outputs results to a CSV file for easy sharing and documentation.
Requirements
This tool requires Python 3.x and the following libraries:

re (for pattern matching)
csv (for saving results)
collections (for efficient data handling)
Install Python libraries using:

bash
Copy code
pip install -r requirements.txt
Usage
1. Clone the Repository
bash
Copy code
git clone https://github.com/judit1806/log-analysis-tool.git
2. Navigate to the Project Directory
bash
Copy code
cd log-analysis-tool
3. Place the Log File
Place your server log file (e.g., sample.log) in the project directory.

4. Run the Script



