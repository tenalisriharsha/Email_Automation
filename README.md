# 📧 Email Automation with CSV Scheduling and HTML Templates

This Python project enables automated email delivery using `smtplib`, with customizable HTML content and scheduled dispatch times. Users can manage multiple recipients and unique delivery schedules by simply editing a CSV file — no coding changes required.

---

## 🚀 Features

- ✅ Send emails to **multiple recipients**
- 📅 Schedule emails at **different times and dates** via CSV
- 🎨 Supports rich **HTML email templates** (funny, cute, or professional)
- 📄 Command-line interface (CLI) – no GUI needed
- 🧩 Modular structure for easy upgrades and customization

---

## 🗂️ Project Structure

email_automation/
├── main.py # Entry point – reads CSV and schedules emails
├── scheduler.py # Schedules one-time jobs with threading.Timer
├── email_sender.py # Sends HTML + plain-text emails via SMTP
├── email_template.html # Custom email template (editable)
├── email_schedule.csv # CSV with recipient schedule data
└── requirements.txt


---

## 📄 CSV Format

Provide your schedule in a file called `email_schedule.csv`:

```csv
email,date,time
friend1@example.com,2025-06-15,14:30
friend2@example.com,2025-06-15,14:32
