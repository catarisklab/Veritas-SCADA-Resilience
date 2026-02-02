---
title: Cata Risk Lab - Policy Auditor
emoji: 🛡️
colorFrom: blue
colorTo: green
sdk: streamlit
sdk_version: 1.40.0
app_file: app.py
pinned: true
license: mit
short_description: AI Use Policy Analyzer & Certification Tool
---

# 🛡️ Cata Risk Lab: Policy Auditor

A comprehensive AI Use Policy analysis and certification tool built with Streamlit.

## Features

- **📄 Policy Analysis**: Paste any AI Use Policy and receive instant analysis
- **🔍 16 Key Areas**: Scans for critical policy elements across 7 categories
- **📊 Weighted Scoring**: Each keyword has point values based on importance (5-20 pts)
- **🏆 Certification**: Policies scoring >80 receive a "Certified by Cata Risk Lab" badge
- **💡 Recommendations**: Actionable suggestions for missing policy elements
- **📥 Export Reports**: Download audit results in TXT or JSON format

## What We Check For

| Category | Keywords |
|----------|----------|
| 🛡️ Critical Safety | Human-in-the-Loop |
| ⚖️ Legal Protection | Liability, Accountability |
| 👁️ Oversight | Human Review |
| 📊 Data Governance | Data Training, Model Governance |
| 🔐 Privacy | Privacy, Consent |
| ✅ Compliance | Audit, Compliance, Testing |
| ⚠️ Risk Management | Risk Assessment, Incident Response |
| 🤝 Ethics | Transparency, Bias |
| 🔒 Security | Security |

## Scoring System

- Each keyword has a weighted point value (5-20 points)
- Scores are normalized to 100
- **Special Penalty**: Missing "Human-in-the-Loop" incurs an additional 15-point deduction
- **Certification Threshold**: Score must exceed 80 points

## Usage

1. Paste your AI Use Policy into the text area
2. Click "Analyze Policy"
3. Review your Safety Score and detailed findings
4. Download your audit report
5. Implement recommendations to improve your score

## Try It

Click "Load Sample Policy" to test with a comprehensive example policy.

---

**Built by [Cata Risk Lab](https://huggingface.co/spaces/Cata-Risk-Lab)**

*Helping organizations build safer, more responsible AI practices*
