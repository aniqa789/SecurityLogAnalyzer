Security Log Analyzer

Overview

Security Log Analyzer is a Python-based cybersecurity tool that processes system log files to detect suspicious activities such as failed login attempts, warnings, and errors. It automatically generates structured security reports for monitoring and analysis.

Features
Detects failed login attempts
Identifies warnings and system errors
Generates automated security reports
Calculates basic risk score
Exports results in TXT and CSV formats
Helps in basic threat monitoring
Tech Stack
Python 3
Regex (for IP detection)
File Handling
Collections (defaultdict)
DateTime module
Project Structure
SecurityLogAnalyzer/
│
├── app.py
├── sample_log.txt
├── requirements.txt
├── logs/
├── reports/
│   ├── security_report.txt
│   └── security_report.csv
How to Run
1. Clone the repository
git clone https://github.com/your-username/SecurityLogAnalyzer.git
cd SecurityLogAnalyzer
2. Run the project
python app.py
Sample Output
================ SECURITY ANALYSIS REPORT ================

Total Logs Processed : 8
Failed Logins        : 3
Warnings             : 2
Errors               : 3

FINAL RISK SCORE     : 19

Future Improvements
Real-time log monitoring
Web dashboard (Flask)
Email alerts for threats
Machine learning-based anomaly detection
Cloud log integration
Author

Aneeqa Kashif
Cybersecurity Enthusiast | Python Developer

Support

If you like this project, give it a ⭐ on GitHub!

