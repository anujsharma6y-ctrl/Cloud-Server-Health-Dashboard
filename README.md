# Cloud Server Health Dashboard

This project provides a simple automation script to monitor:

- Linux Disk Usage
- CPU Usage
- Memory Usage
- AWS S3 Public Bucket Detection
- IAM Admin User Detection

## Requirements

- Python 3.8+
- AWS CLI configured (`aws configure`)
- Install dependencies:
- pip install -r requirements.txt

- ## Run the Script
- python monitor.py

## Output
- Terminal report
- server_report.csv file generated automatically

## Use Case

This script helps startups and small businesses:
- Monitor server health
- Detect public S3 buckets
- Identify IAM users with admin privileges

Ready for customization and integration.

📂 Project Structure
Files are organized to ensure a clean, searchable, and professional repository hierarchy:

cloud-server-health-dashboard/
│
├── monitor.py
├── requirements.txt
├── server_report.csv   (auto generated)
└── README.md
🛠️ Tech Stack & Requirements
Language: Python 3.x, Bash

Core Libraries: streamlit, boto3, psutil, fpdf, requests, pandas, hashlib

Standard Compliance: MITRE ATT&CK, NIST, CIS Benchmarks


## ⚖️ License & Legal Information

This project is primarily licensed under the **MIT License**, with specific modules covered under **Apache 2.0** and **GPL v3**.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](./LICENSE)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-red.svg)](./LICENSE)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/)

### Key Permissions:
- ✅ **Commercial Use:** You can use this code for business purposes.
- ✅ **Modification:** You can change the code however you like.
- ✅ **Distribution:** You can share the code with others.
- ✅ **Private Use:** You can use it privately.

### Conditions:
- ⚠️ **Notice:** You must include the original copyright and license notice in any copy of the software/source code.

### Warranty:
- 🛡️ **No Warranty:** The software is provided "as is", without any warranty of any kind. The author is not liable for any claims or damages.

**For more details, view the [Full LICENSE File](./LICENSE)**


👨‍💻 Author
Anuj Sharma Cybersecurity Enthusiast |Cloud Security Automation Specialist | DevSecOps Engineer

- 
