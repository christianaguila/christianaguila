# Christian Rhomel Aguila
### AI Automation Specialist | n8n | Claude API | Facebook Messenger API | Python

I build AI-powered automation systems that eliminate manual work and deliver measurable business results. Self-hosted infrastructure, end-to-end — from webhook to delivery.

## Featured Project

### Dental Clinic AI Automation System
A 3-module AI receptionist system for dental clinics, built for the Philippine market where patients prefer Facebook Messenger over phone calls.

**Module 1 — AI Chat Agent:** Facebook Messenger webhook → Claude AI Agent with multi-turn memory → Google Calendar (check availability, book, reschedule, cancel) → CRM logging. The AI receptionist (Sunshine) holds natural Taglish/English conversations, verifies slot availability in real-time, and books appointments autonomously.

**Module 2 — Pre-Appointment Reminder:** Daily scheduled trigger → fetches tomorrow's bookings from Google Calendar → filters `[BOOKED]` events → extracts patient details → sends personalized Messenger reminders via Facebook Graph API.

**Module 3 — Post-Appointment Follow-up & Reactivation:** Two scheduled branches — daily follow-up messages after appointments, and monthly reactivation campaigns for patients inactive 60+ days. Deduplication logic prevents duplicate outreach.

**Stack:** n8n (self-hosted), Claude API, Facebook Messenger API, Google Calendar API, Google Sheets, Docker, Traefik

---

## All Projects

| Project | Stack | Demo |
|---|---|---|
| Dental Clinic AI Automation System (3 modules) | n8n, Claude API, Facebook Messenger API, Google Calendar, Google Sheets | — |
| AI Social Media Content Calendar Generator | n8n, Claude API, Google Slides API, Gmail | [Loom](https://www.loom.com/share/e9cf179aab3e4e43b6f448a6f07ac5dc) |
| AI Customer Support Bot | n8n, Gmail, Claude API, Google Sheets | [Loom](https://www.loom.com/share/baf79ee055a3400dbc6f3dedb380a577) |
| YouTube Comment Bot | n8n, YouTube Data API, Claude API, Slack, Google Sheets | — |
| AI Lead Capture & Follow-up | n8n, Claude API, Google Forms, Gmail, Twilio | — |
| Automated Client Assessment Pipeline | n8n, Stripe, Google Forms, Claude API, Gmail | [Loom](https://www.loom.com/share/d132de7da9a6424f9c8d6940885c8764) |
| AI Job Matching System | n8n, Claude API, Google Sheets, Gmail | [Loom](https://www.loom.com/share/4eda50a045264b3aa3f0ecfde8bd2af1) |
| AI Sales Reporting Engine | n8n, Claude API, Google Sheets, Gmail | — |

## Tech Stack
**Automation:** n8n (self-hosted on VPS), REST APIs, Webhooks, Facebook Messenger API, Google Workspace APIs  
**AI/LLM:** Claude API (Anthropic), Prompt Engineering, AI Agent architecture  
**Infrastructure:** Docker, Traefik, Let's Encrypt, Ubuntu VPS  
**Programming:** Python, JavaScript, SQL  
**Data & BI:** Snowflake, Databricks, Power BI, Looker, Google Sheets

## Background
Marketing Analytics Manager at Globe Telecom with 3 years of enterprise experience building automated data pipelines, ETL systems, and executive dashboards across datasets of 60M+ rows. Now building done-for-you AI automation systems for SMEs.

## Contact
christianrhomel@gmail.com
