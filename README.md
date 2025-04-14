# 🤖 AI Doctor Booking Automation (n8n + GPT + WhatsApp)

A fully automated AI agent for booking doctor appointments using WhatsApp, GPT, Airtable, Google Meet, and email confirmations — built with n8n.



---

## 🚀 Features

✅ WhatsApp-triggered AI conversation  
✅ ChatGPT-powered data collection  
✅ Appointment validation and error handling  
✅ Airtable database integration  
✅ Google Meet link scheduling  
✅ Confirmation via WhatsApp + Email  

---

## 🧠 Tech Stack

- [n8n](https://n8n.io/)
- OpenAI GPT-4
- WhatsApp API (Twilio or custom bridge)
- Airtable API
- Google Calendar API
- SMTP Email

---

## 📂 How to Use

1. **Import Workflow**  
   Upload the file from `workflows/doctor_booking_ai_agent.json` into your n8n instance.

2. **Configure Credentials**  
   Set these in your n8n credentials panel:
   - `whatsappApi`
   - `openai`
   - `airtable`
   - `google`
   - `smtp`

3. **Set Up Airtable**  
   Create a table with these fields: `Name`, `Phone`, `Symptoms`, `PreferredTime`.

4. **Enable Webhook**  
   Use a WhatsApp API to POST messages to:  
   `https://your-n8n-instance/webhook/whatsapp-in`

---

## 📸 Preview

<img> ![image](https://github.com/user-attachments/assets/9906a467-f90c-4637-9e59-b6833265178b) </img>

---

## 📄 License

MIT License. Use it freely, modify it deeply, and if you profit from it — send good vibes ✨

---

## 👤 Author

Built by [Maruf](https://github.com/maruf7705). Optimised for productivity, automation, and impact.
