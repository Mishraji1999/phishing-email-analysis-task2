# phishing-email-analysis-task2
Phishing email report for scam impersonating U.S. government
# 📧 Phishing Email Analysis Report – Task 2

**Analyzed Email Subject:** `Dear Beneficiary`  
**Date Received:** May 11, 2025  
**Reported By:** surajmishra1826@gmail.com  
**Purpose:** Educational and forensic analysis of a phishing scam using social engineering and impersonation tactics.

---

## 🚨 Summary

This report analyzes a phishing email received on May 11, 2025. It falsely claims to offer a large inheritance from the "Office of the U.S. Accountant General" and urges the recipient to contact a fraudulent diplomat. The objective of this scam is to trick victims into sharing personal or financial data under the guise of receiving money.

---

## 🧾 Email Metadata Overview

| Field | Details |
|-------|---------|
| **From** | `"EUGENE L. DODARO" <kimhavid97@gmail.com>` |
| **Reply-To** | `jeuhdhk45@gmail.com` |
| **To** | `undisclosed-recipients` |
| **BCC** | `surajmishra1826@gmail.com` |
| **SPF/DKIM/DMARC** | ✅ Passed (via Gmail infrastructure) |
| **Sending IP** | `209.85.220.41` (Google SMTP relay) |
| **Headers** | Standard Gmail authentication, but non-government domains |

---

## 🧠 Behavioral & Linguistic Analysis

### 🔸 Tactics Identified:
- **Authority Misuse**: Impersonates `Eugene L. Dodaro`, real U.S. Comptroller General
- **Emotional Manipulation**: Promises a $12.75 million inheritance
- **Urgency & Scarcity**: Requests immediate action to claim funds
- **Redirecting Contact**: Instructs the recipient to email a second suspicious Gmail address

### 🔸 Language Characteristics:
- Grammatical errors: “CONTACAT” instead of “CONTACT”
- Redundant phrases: "wonderful good news"
- Generic formatting and impersonal greeting
- Poor punctuation and structure for a government notice

---

## 🔍 Technical Red Flags

| Indicator | Description |
|----------|-------------|
| ❌ **Non-official Sender** | Gmail address used to mimic a U.S. government authority |
| ❌ **Mismatch in Sender vs. Reply-To** | Reply-To differs, suggesting redirection to scammer |
| ❌ **Mass Mailing via BCC** | Sent to undisclosed recipients (mass phishing attempt) |
| ❌ **Email Tone** | Unprofessional for a federal office |
| ❌ **Lack of Personalization** | Does not address recipient by name |
| ✅ **SPF/DKIM/DMARC** | Passed for Gmail, not proof of legitimacy |

---

## 📬 Original Email Body (Plain Text)

```text
This notice is reaching you from the office of Accountant General of the
United States of America. This is to inform you on this wonderful good news.
However, an Inheritance Funds valued sum of ($12.750.000.00 USD) allocated
to your family long ago was recovered by the help of IMF "SDR" server and
assigned to your favor via Bank Draft Check and has been handed over to
diplomat Mr Johnny Wills. So kindly contact him:

CONTACT: Diplomat Below
Mr. Johnny Wills
EMAIL: jeuhdhk45@gmail.com

Therefore all you need to do now is to contact Diplomat Johnny Wills and
provide him with your current home addresses for the delivery okay.

Best Regards,  
Eugene L. Dodaro  
U.S Accountant/Controller General
