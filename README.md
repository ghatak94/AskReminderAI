# 🧠 n8n Reminder Bot  

A smart **AI-powered Reminder & Task Manager** built using **n8n**, WhatsApp integration, and Airtable.  
This project allows users to:  
- Create reminders with natural language (e.g., *“Remind me to pay electricity bill tomorrow at 8 PM”*)  
- Fetch pending tasks (e.g., *“What tasks are left?”*)  
- Update task status automatically after reminders are sent  
- Manage tasks in Airtable (with **Pending/Done** status)  

---

## 🚀 Features
- ✅ Add reminders with **date, time, frequency, and category**  
- ✅ Store tasks in **Airtable** with status tracking  
- ✅ Fetch and display only **pending tasks**  
- ✅ Auto-update task status to **Done** after reminders  
- ✅ WhatsApp integration for receiving and sending reminders  

---

## 📂 Project Structure
```
n8n-reminder-bot/
 ├── reminder-workflow.json   # Exported n8n workflow
 ├── README.md                # Project documentation
 └── notes.txt (optional)     # Your notes/extra docs
```

---

## ⚡ Setup Instructions
### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/n8n-reminder-agent.git
cd n8n-reminder-agent
```

### 2. Import Workflow to n8n
- Open n8n  
- Go to **Workflows → Import from File**  
- Upload `reminder-workflow.json`  

### 3. Configure Environment
- **WhatsApp Node** → Add WhatsApp Business API credentials  
- **Airtable Node** → Add API Key + Base ID + Table Name  
- **AI Agent Node** → Configure with your LLM provider (e.g., OpenAI API key)  

---

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

---

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.  

---

## 📄 License
This project is licensed under the MIT License.  
