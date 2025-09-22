# 🧠 AskReminderAI  

A smart **AI-powered Reminder & Task Manager** built using **n8n**, WhatsApp integration, and Airtable.  
This project allows users to:  
- Create reminders with natural language (e.g., *“Remind me to pay electricity bill tomorrow at 8 PM”*)  
- Fetch pending tasks (e.g., *“What tasks are left?”*)  
- Update task status automatically after reminders are sent  
- Manage tasks in Airtable (with **Pending/Done** status)  

---

## 🚀 Features
General Questions 
- ✅ Here you will get normal chat bot eg - **What is the capital of India / Ask about the recipes and all** 
Reminder and Task related query
- ✅ Add reminders with **task, date, time, frequency, and category**  
- ✅ Store tasks in **Airtable** with status tracking  
- ✅ Fetch and display only **pending tasks**  
- ✅ Auto-update task status to **Done** after reminders  
- ✅ WhatsApp integration for receiving and sending reminders  

---

## 📂 Project Structure
```
AskReminderAI/
 ├── Ask & Remind AI.json   # Exported n8n workflow
 ├── README.md                # Project documentation

```

## 🛠 Tech Stack
- [n8n](https://n8n.io/) (Automation platform)  
- [Airtable](https://airtable.com/) (Task storage)  
- WhatsApp Business API (Messaging)  
- OpenAI / LLM API (Natural language understanding)  

---

## 📌 Example Usage
**Add Task:**  
👉 “Remind me to drink water every 2 hours”  

**Pending Tasks Query:**  
👉 “What tasks are pending?”  

**Output on WhatsApp:**  
```
📌 Your Pending Tasks List:
- Pay electricity bill at 2025-09-07 20:00
- Submit weekly report at 2025-09-08 09:00
```

## 📄 License
This project is licensed under the MIT License.  
