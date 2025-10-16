🚀 Autobiotic Cold Email Pipeline

Automate your job outreach with Python — send personalized cold emails, attach resumes, and track every attempt automatically.

💡 Overview

This project automates cold emailing to HRs and recruiters using Gmail SMTP. It reads contact data from an Excel/CSV file, personalizes each email using a template, attaches your resume, and logs results — all while skipping already sent emails.

⚙️ Key Features

📧 Personalized subject & body (Name, Company, Role)
📎 Auto resume attachment
🔁 Smart retry & random delay system
🚫 Prevents resending to “sent” contacts
🧾 Detailed logs of sent, failed, and skipped emails
🔒 Secure Gmail App Password authentication

🧩 Folder Structure
Cold_Email_Pipeline/
├── send_emails.py
├── Data/recipients_list.csv
├── Templates/email_template_v1.txt
└── Assets/AanayaVerma.pdf

⚡ Usage

- Add contacts to recipients_list.csv
- Edit email_template_v1.txt

Run:
python send_emails.py

The script auto-updates CSV with status logs.

Author: Aanaya Verma
Data & Automation Enthusiast | Python | SQL | Power BI
🔗 https://www.linkedin.com/in/aanaya-verma


