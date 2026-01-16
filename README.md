# International Data Privacy Audit: Mobile Health App Case Study

## ⚖️ Project Overview
This project consists of a comparative legal and technical audit for a hypothetical mobile health application ("VitalTrack") that operates in Mexico, the United States, and the European Union. As an Attorney transitioning into Cybersecurity, I performed this audit to ensure the app's data handling practices align with diverse international privacy regulations.

## 🔍 Regulatory Frameworks Compared
* **LFPDPPP (Mexico):** Ley Federal de Protección de Datos Personales en Posesión de los Particulares.
* **CCPA/CPRA (USA - California):** California Consumer Privacy Act.
* **GDPR (European Union):** General Data Protection Regulation.

## 📋 Audit Scope
The audit evaluates how "VitalTrack" manages sensitive medical data (heart rate, sleep patterns, and medical history) across four key areas:
1. **User Consent:** How the app obtains permission to collect sensitive health data.
2. **Data Minimization:** Whether the app collects more data than necessary for its function.
3. **Data Subject Rights:** Procedures for users to access, delete, or port their data (ARCO rights in Mexico).
4. **Security Measures:** Technical safeguards required by each law (Encryption, Access Control).

## 📊 Comparative Analysis Matrix

| Feature | LFPDPPP (MX) | GDPR (EU) | CCPA/CPRA (USA) |
| :--- | :--- | :--- | :--- |
| **Sensitive Data Category** | Explicitly includes health data. | "Special Category" (Art. 9). | "Sensitive Personal Info". |
| **Consent Requirement** | Written/Express for sensitive data. | Clear Affirmative Action. | Opt-out (mostly), Opt-in for minors. |
| **Breach Notification** | Mandatory if rights are affected. | Mandatory within 72 hours. | Mandatory (state-specific). |
| **Fines/Penalties** | Significant (up to 320k USD approx). | Up to 4% of annual turnover. | Statutory damages per violation. |

## 🛡️ Technical Recommendations
Based on the legal gaps identified, the following technical controls are recommended:
1. **Encryption at Rest (AES-256):** To satisfy the "Security Measures" requirement across all three jurisdictions.
2. **Granular Consent Toggle:** A UI/UX feature allowing users to opt-in or opt-out of specific data processing activities.
3. **Automated Data Deletion:** Scripts to ensure data is deleted after the retention period specified in the Privacy Notice.

---
**Note:** This report is for educational purposes as part of a Cybersecurity portfolio and does not constitute formal legal advice.
