# project2
Log File Analyzer for Intrusion Detection
🧾 Log Analyzer Project
📌 Abstract
The Log Analyzer project automates the detection and classification of suspicious log activities from Windows and Web logs. It leverages pattern matching and regular expressions to identify common attack types such as SQL Injection, Cross-Site Scripting (XSS), and Brute Force attempts. This automation enhances real-time log monitoring and alert generation, reducing manual effort and improving cybersecurity incident detection.

💡 Introduction
In cybersecurity, analyzing system and web logs is crucial to detect potential threats and vulnerabilities. Manual log inspection is inefficient, time-consuming, and prone to oversight. The Python-based automated Log Analyzer integrates data from multiple log sources, processes them, and identifies suspicious or abnormal activities using regex-based detection and classification.

🛠️ Tools Used
Python 3
Pandas – for data manipulation
Matplotlib and Seaborn – for visualization
Regular Expressions (re module) – for pattern-based attack detection
Jupyter Notebook / VS Code – for implementation
CSV files – for storing log data and output
⚙️ Steps Involved in Building the Project
Data Collection – Imported Windows and Web logs in CSV format.
Data Cleaning – Removed missing/irrelevant data and standardized column names.
Suspicious Log Detection – Applied regex rules to detect suspicious entries.
Classification – Categorized attacks into SQL Injection, XSS, and Brute Force.
Visualization – Displayed distribution using Seaborn charts.
Report Generation – Generated summary reports and exported suspicious logs to CSV.
🧩 Features
Automated suspicious log detection from Windows and Web sources
Regex-based attack classification (SQL Injection, XSS, Brute Force)
Alert summary and exportable suspicious log reports
Visual representation of log statistics
📊 Output
Alerts summary report displayed in the console
Suspicious logs saved in the /alerts folder (suspicious_windows.csv, suspicious_web.csv)
Final summary file generated as Suspicious_Log_Report.csv
✅ Conclusion
The Log Analyzer successfully automates the detection and classification of suspicious log entries. It offers an efficient, scalable, and lightweight solution for early-stage security monitoring and forensic analysis. Future improvements may include integration with SIEM tools and machine learning-based anomaly detection for enhanced threat analysis.

