# 🔍 Microsoft Purview Insider Risk Investigation

This project documents a simulated insider threat investigation using Microsoft Purview and Microsoft Defender. The investigation covers alert triage, user activity analysis, case escalation, and cross-platform incident correlation.

---

## 🎯 Objective

To investigate a potential insider threat involving data exfiltration prior to employee departure and determine the risk level and appropriate response.

---

## 🛠️ Tools Used

- Microsoft Purview (Insider Risk Management)
- Microsoft Defender (XDR)
- Activity Explorer
- Copilot (for assisted analysis)

---

## 🚨 Scenario

An alert titled:

**"Potential data theft – Employee Departure"**

was triggered due to suspicious user activity involving sensitive data access and downloads from SharePoint.

---

## 🔎 Investigation Process

### 1. Alert Triage (Microsoft Purview)

- Reviewed alert details and risk indicators
- Identified:
  - High volume of sensitive file access
  - Files downloaded to unmanaged device
  - Access to PII and confidential data

---

### 2. User Activity Analysis

Key findings:
- Hundreds of sensitive files accessed
- File renaming (possible obfuscation)
- File deletion (possible cleanup)
- Data accessed included:
  - Passport information
  - API keys
  - Personal data

---

### 3. Case Escalation

- Created insider risk case:
  **"Employee departure – Data exfiltration"**

- Escalated for investigation via eDiscovery

**Justification:**
- Data staging behavior
- High-risk data exposure
- Activity occurring before account deletion

---

### 4. Cross-Platform Correlation (Microsoft Defender)

- Identified correlated incident:
  **"Exfiltration incident involving one user"**

- Defender aggregated:
  - Insider risk alerts
  - User activity signals
  - Incident timeline

---

## 🧠 Analyst Assessment

The observed behavior is consistent with:

> **Insider-driven data staging and potential exfiltration prior to employee departure**

Despite a medium risk score, the combination of:
- Sensitive data access  
- File manipulation  
- Account deletion  

indicates a **high-risk insider threat scenario**

---

## 🤖 Copilot-Assisted Insights

Copilot identified:
- Repeated access to sensitive SharePoint data
- File uploads to cloud storage
- Risk indicators aligned with insider threat patterns

These findings supported and validated the manual investigation.

---

## ✅ Outcome

- Case escalated for investigation  
- Incident correlated in Microsoft Defender  
- Final classification:
  **Confirmed policy violation (data exfiltration)**  

- Action taken:
  - HR notified
  - Case resolved

---

## 📸 Screenshots

Screenshots of key investigation steps are included in the `/screenshots` folder.

---

## 🚀 Key Skills Demonstrated

- Alert triage  
- Insider threat detection  
- Data exfiltration analysis  
- Incident escalation  
- Cross-platform correlation (Purview + Defender)  
- SOC documentation  

---
