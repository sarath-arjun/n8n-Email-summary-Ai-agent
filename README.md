# n8n-Email-summary-Ai-agent
it will send you the summary of the entire email you've receive on a day via Whatsapp
# n8n Workflow – Daily Email Summary

This repository contains an exported **n8n workflow** (`daily_email_summary.json`).  
The workflow automatically summarizes all emails received today and sends the summary to the user once per day.

---

## How to Import

1. Open your **n8n** editor.
2. Click **Workflows** → **Import from File**.
3. Select the `daily_email_summary.json` file from this repo.
4. After import, open the workflow and:
   - Configure your **Email** credentials (IMAP/SMTP or Gmail/Outlook etc.).
   - Adjust schedule (Cron node) if needed.
5. **Activate** the workflow.

---

## Requirements

- n8n version 1.x or later
- Valid email credentials configured in n8n (stored securely in n8n, not in the JSON)

---

## Notes

- No credentials are included in this repository.  
- Update environment variables or credentials inside n8n before running.  
- Feel free to fork or adapt for your own use.

---

## License
MIT (or whichever license you prefer)
