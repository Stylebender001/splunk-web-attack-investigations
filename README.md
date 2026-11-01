# Splunk Web Attack Investigations

A hands-on blue-team security investigation portfolio using **Splunk Enterprise** to investigate suspicious web activity and authentication events in a controlled lab environment.

This project demonstrates practical experience with log analysis, SPL (Search Processing Language), security event investigation, suspicious activity detection, and evidence documentation.

## Project Overview

The repository contains four security investigation labs covering common web application attacks and authentication threats.

| Lab | Investigation | Focus |
|---|---|---|
| 01 | SQL Injection Investigation | Detecting suspicious SQL injection patterns in web logs |
| 02 | Reflected XSS Investigation | Identifying reflected cross-site scripting payloads |
| 03 | Suspicious File Upload | Investigating upload endpoints and suspicious file access |
| 04 | SSH Authentication Failures | Analysing failed SSH login activity and source IPs |

## Repository Structure

```text
splunk-web-attack-investigations/
│
├── Lab-01-SQL-Injection/
│   ├── Investigation Report (.md)
│   ├── queries.spl
│   └── evidence/
│
├── Lab-02-XSS/
│   ├── Investigation Report (.md)
│   ├── queries.spl
│   └── evidence/
│
├── Lab-03-Suspicious-File-Upload/
│   ├── Investigation Report (.md)
│   ├── queries.spl
│   └── evidence/
│
└── Lab-04-BruteForce/
    ├── Investigation Report (.md)
    ├── queries.spl
    └── evidence/
```

## Investigation Details

### 01 — SQL Injection Investigation

**Objective:** Investigate suspicious SQL injection activity within web server logs.

Areas covered:
- SQL injection keyword and payload detection.
- Reviewing suspicious HTTP requests.
- Analysing extracted request fields.
- Filtering potentially malicious URL parameters.

[View Lab 01](./Lab-01-SQL-Injection/)

### 02 — Reflected Cross-Site Scripting (XSS)

**Objective:** Identify and investigate reflected XSS payloads in web traffic.

Areas covered:
- Detecting script tags and JavaScript payload patterns.
- Searching for URL-encoded XSS payloads.
- Analysing suspicious HTTP requests.
- Reviewing activity using SPL.

[View Lab 02](./Lab-02-XSS/)

### 03 — Suspicious File Upload Investigation

**Objective:** Investigate suspicious file upload activity and subsequent access to an uploaded test file.

Areas covered:
- Identifying file upload endpoints.
- Reviewing upload-related HTTP requests.
- Investigating access to a test PHP file.
- Analysing request activity and response status codes.

[View Lab 03](./Lab-03-Suspicious-File-Upload/)

### 04 — SSH Authentication Failure Investigation

**Objective:** Investigate failed SSH authentication activity using Linux authentication logs.

Areas covered:
- Identifying failed password attempts.
- Reviewing SSH authentication events.
- Extracting source IP addresses and usernames.
- Analysing authentication failure patterns.

[View Lab 04](./Lab-04-BruteForce/)

## Tools & Technologies

- **Splunk Enterprise** — Log ingestion, searching, and investigation.
- **SPL** — Searching, filtering, extracting, and aggregating security events.
- **Linux** — Authentication log analysis.
- **DVWA** — Controlled web application testing environment.
- **HTTP access logs** — Web activity investigation.
- **Markdown** — Technical reporting and documentation.

## Skills Demonstrated

- Security Information and Event Management (SIEM)
- Log Analysis and Investigation
- SPL Query Development
- Web Attack Detection
- SQL Injection and XSS Detection
- Suspicious File Upload Investigation
- SSH Authentication Monitoring
- Source IP and Username Extraction
- Security Evidence Documentation
- Basic Threat Detection and Analysis

## Evidence & Documentation

Each lab contains:

- A written investigation report.
- SPL queries used during the investigation.
- Screenshots documenting relevant events, searches, and findings.

The reports explain the investigation process and observations made during each exercise.

## Scope & Disclaimer

All investigations in this repository were conducted in controlled lab environments using test systems and simulated attack activity.

This repository is intended for educational and portfolio purposes. The findings should not be interpreted as investigations of real-world security incidents.

---

**Author:** Shardul Sapkota

**Focus:** Cybersecurity | SOC Analysis | SIEM | Threat Detection

