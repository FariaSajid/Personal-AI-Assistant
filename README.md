# 🤖 FariaAI – Personal AI Assistant for University Students

> A WhatsApp-based AI assistant that knows your timetable, personal details, and sends you automatic reminders – built with n8n, Google Gemini, and Google Sheets.

---

## 📌 Why This Project?

University life is chaotic. Between lectures, assignments, exams, and bus schedules, it's easy to forget things. I wanted a **personal assistant** that:

- Knows **my timetable** (course, time, room, instructor)
- Knows **my personal details** (roll number, bus timing, etc.)
- Works on **WhatsApp** (where I already am)
- Sends **automatic reminders** so I don't have to ask
- Is **completely free** and runs on my own machine

Existing solutions like Google Calendar or reminder apps require manual entry. I wanted something that **feels like Jarvis** – just ask or get notified automatically.

So I built **FariaAI** – my own WhatsApp AI assistant.

---

## 🎯 What It Does

| Feature | Description |
|---------|-------------|
| 📅 **Timetable Query** | Ask "What class do I have now?" or "What's my schedule for Tuesday?" |
| 👤 **Personal Info** | Knows my name, roll number, department, bus timing, emergency contact |
| ➕ **Add Events** | Tell it "Add assignment due on March 30th" – it saves to Google Sheets |
| 🔔 **Daily Reminders** | Automatically sends my schedule for the day every morning at 7 AM |
| 🧠 **Memory** | Remembers conversation context (thanks to n8n's Simple Memory) |
| 💬 **WhatsApp Native** | Works from my phone – no new app to install |

---

## 🛠️ How I Made It

### Tech Stack

| Tool | Purpose |
|------|---------|
| **n8n** | Workflow automation (self-hosted, free) |
| **Google Gemini API** | AI model (free tier available) |
| **WhatsApp Business API** | Messaging (via Meta or WhatsApp Cloud API) |
| **Google Sheets** | Database for timetable & profile |
