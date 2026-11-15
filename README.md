# Sutrefia Security Policy Compliance Dashboard

## Project Overview

This project involves the development of a security monitoring dashboard using Splunk Enterprise on Windows Server. The dashboard was designed to monitor Sutrefia's security policy compliance by analysing authentication events, endpoint processes, and multi-factor authentication (MFA) status.

The project utilises the Splunk Boss of the SOC (BOTSv3) dataset to investigate security-related events and present the findings through interactive visualisations.

## Project Objectives

- Monitor successful and failed Windows authentication attempts.
- Identify suspicious login activities and potential brute-force attacks.
- Evaluate Multi-Factor Authentication (MFA) compliance.
- Analyse endpoint processes and identify potentially unusual activities.
- Improve visibility into security-related events.
- Support security policy monitoring through data visualisation.

## Dashboard Components

### 1. Failed Authentication Attempts Over Time

Monitors failed Windows authentication attempts over time to identify suspicious login activities, repeated login failures, and potential brute-force attacks.

### 2. Successful Authentication Attempts

Tracks successful Windows authentication events to monitor legitimate user access patterns and identify unusual login behaviour.

### 3. Multi-Factor Authentication (MFA) Compliance

Visualises MFA requirement status to provide an overview of authentication security compliance.

### 4. Top 10 Endpoint Processes

Displays the ten most frequently executed endpoint processes to support endpoint activity monitoring and identify potentially unusual process execution patterns.

## Technologies and Tools

| Technology | Purpose |
|---|---|
| Splunk Enterprise | Security information and event monitoring |
| Windows Server | Operating environment |
| Search Processing Language (SPL) | Log searching and analysis |
| Splunk BOTSv3 Dataset | Security event analysis |
| XML | Dashboard configuration |

## Implementation

The dashboard was developed using Splunk Enterprise installed on Windows Server.

Search Processing Language (SPL) queries were implemented to retrieve, filter, analyse, and visualise security-related events from the BOTSv3 dataset.

The resulting information was organised into multiple dashboard panels to provide an overview of authentication activities, MFA compliance, and endpoint processes.

## Dashboard Preview

The following screenshot demonstrates the completed Splunk Security Policy Compliance Dashboard.

![Sutrefia Security Policy Compliance Dashboard](Screenshots/Dashboard%20layout.png)

## Repository Structure

```
Splunk-Security-Monitoring/
│
├── sutrefia_security_compliance.xml
│
├── screenshots/
│   └── dashboard-overview.png
│
└── README.md
```

## Skills Demonstrated

- Security Information and Event Management (SIEM)
- Splunk Enterprise Administration
- Search Processing Language (SPL)
- Security Log Analysis
- Authentication Monitoring
- Endpoint Activity Monitoring
- Security Policy Compliance
- Dashboard Development and Data Visualisation

## Dataset

**Splunk Boss of the SOC (BOTSv3)**

The BOTSv3 dataset was used as the source of security-related event data for dashboard development and analysis.

## Project Information

**Project Title:** Sutrefia Security Policy Compliance Dashboard

**Platform:** Splunk Enterprise

**Operating Environment:** Windows Server

**Dashboard Configuration:** XML

**Project Domain:** Cybersecurity / SIEM

---

## Author

Developed as a practical cybersecurity project to demonstrate the application of SIEM technologies, security event analysis, and dashboard development using Splunk Enterprise.
