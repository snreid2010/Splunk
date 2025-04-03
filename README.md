# Phishing Simulation & Response Plan

This project documents a simulated phishing attack conducted to raise security awareness and test incident response capabilities. It includes planning, execution, and mitigation strategies.

## Objectives
- Educate users on phishing tactics
- Measure click-through and submission rates
- Test incident response and escalation procedures

## Simulation Overview
- **Tool Used**: GoPhish (Open Source Phishing Framework)
- **Target**: Internal team (controlled environment)
- **Payload**: Fake login page mimicking a real service
- **Metrics**: Email opens, link clicks, credential submissions

## Response Plan
1. Identify & report suspicious emails
2. Isolate compromised systems (if any)
3. Reset affected credentials
4. Notify security team and log incident
5. Conduct post-incident review and training

## Screenshots

| Step | Description | Image |
|------|-------------|-------|
| 1 | Created phishing email campaign in GoPhish | ![Step 1](screenshots/gophish-campaign.png) |
| 2 | Customized fake login page template | ![Step 2](screenshots/fake-login.png) |
| 3 | Real-time results tracking via dashboard | ![Step 3](screenshots/gophish-dashboard.png) |
| 4 | Summary of clicks and submissions | ![Step 4](screenshots/report-summary.png) |

## Lessons Learned
- Importance of frequent training
- Most clicked emails had urgent language and branding
- Real-time monitoring allows faster containment

## Tools & Skills
- GoPhish
- Network monitoring
- Security awareness training
- Incident response planning# Splunk
