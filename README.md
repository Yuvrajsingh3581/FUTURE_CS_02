# FUTURE_CS_02 — Phishing Email Detection & Awareness System

## Task Overview
Task 2 of the Future Interns Cyber Security Internship. This project involves
analyzing real phishing email samples, identifying phishing indicators,
classifying email risk, and creating a professional awareness report.

## Scope & Approach
Six real-world email samples were collected and analyzed — two modern,
legitimate emails and four historical samples from the SpamAssassin Public
Corpus (a free, public dataset used for spam/phishing research). Each email
was investigated for authentication (SPF, DKIM, DMARC) and manually reviewed
for social engineering indicators. No exploitation or offensive testing was
performed — this is analysis and awareness only.

## Tools Used
- Google Header Analyzer (toolbox.googleapps.com/apps/messageheader)
- MxToolbox (mxtoolbox.com) — Email Header Analyzer
- Manual content/domain review

## Repository Structure

FUTURE_CS_02/

├── README.md

├── report/

├── samples/

│   ├── safe/

│   ├── suspicious/

│   └── phishing/

└── screenshots/



## Findings Summary
6 emails analyzed — 2 Safe, 2 Suspicious/Spam, 2 Phishing.

| # | Email Subject | Sender | Classification |
|---|---|---|---|
| 1 | Security alert | no-reply@accounts.google.com | Safe |
| 2 | Find out more about our updated Terms of Service | google-noreply@google.com | Safe |
| 3 | Something EVERY Business Needs! | 2b1lf@msn.com | Suspicious |
| 4 | Get Paid For What You Know | 63rlfplk4@aaaticketsource.com | Suspicious |
| 5 | CLIENTE PRIME - BRADESCO LIVELO... | banco.bradesco@atendimento.com.br | Phishing |
| 6 | Verify Your Wallet Now... | support@pcpilrjf.zendesk.com | Phishing |

## Deliverable
A Phishing Detection & Awareness Report (PDF) covering identified phishing
indicators, risk classification, plain-language explanations of each attack,
and prevention guidelines (Do's and Don'ts) for employees.

## Author
Yuvraj Singh — Certified Ethical Hacker (CEH v13)
LinkedIn:- https://linkedin.com/in/yuvraj-singh-997a45372
