# Incident Response Playbook – Web Application Attack

## Project Overview
This project demonstrates a complete Incident Response (IR) playbook for a web application attack scenario.  
The playbook is based on real-world security operations practices and uses Apache web server access logs analyzed through Splunk.

The objective of this project is to show how security incidents are detected, analyzed, contained, eradicated, and reviewed in a structured and professional manner.

This project is suitable for SOC Analyst, Cybersecurity, and SIEM-focused roles.

---

## Incident Scenario
Suspicious web traffic was detected on a web application, including:
- Sudden traffic spikes
- High number of HTTP 404 and 403 responses
- Repeated access attempts to sensitive URLs

The activity indicated possible scanning or malicious behavior targeting the web application.

---

## Tools and Technologies
- Splunk Enterprise
- Apache Web Server Access Logs
- SPL (Search Processing Language)

---

## Project Structure


---

## Incident Response Lifecycle Covered

### 1. Incident Definition
Defined the incident scope, affected assets, and data sources based on abnormal web traffic patterns.

### 2. Detection and Alert Triggers
Configured detection logic using Splunk searches to identify:
- Traffic spikes
- Excessive 404 errors
- Repeated 403 errors
- Requests to sensitive endpoints

### 3. Severity Classification
Classified incidents into Low, Medium, High, and Critical based on impact and intent.

### 4. Investigation and Analysis
Performed log analysis to:
- Validate alerts
- Identify source IP addresses
- Analyze targeted URLs
- Determine duration and scope of activity

### 5. Containment Actions
Implemented immediate actions to limit impact, including:
- Temporary IP blocking
- Rate limiting
- Restriction of sensitive endpoints
- Log preservation

### 6. Eradication and Recovery
Removed root causes, applied security updates, and restored normal operations while monitoring system stability.

### 7. Post-Incident Review and Reporting
Documented the incident, performed root cause analysis, identified lessons learned, and improved detection and response procedures.

---

## Key Outcomes
- Demonstrated a structured incident response workflow
- Applied real-world SOC investigation techniques
- Used log data to drive security decisions
- Produced a professional, reusable incident response playbook

---

## Author
Mahavirsinh Dabhi

