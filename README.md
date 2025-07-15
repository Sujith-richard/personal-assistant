# n8n Workflow Automation Project 🚀

This repository contains a collection of n8n workflows designed to automate various business processes using integrations with Google Workspace, Airtable, Telegram, Todoist, and more.

---

## 📁 Project Structure


---

## 🧠 Agents & Integrations

### 🤖 AI Agents
- **Email Agent** – Handles Gmail operations (send, reply, draft, label).
- **Calendar Agent** – Manages Google Calendar events.
- **Project Management Agent** – Handles task creation, updates, and deletions.
- **Research Agent** – Uses OpenAI for document parsing or web queries.
- **Manager Agent** – Oversees and routes tasks to appropriate agents.
- **Airtable Agent** – Automates record creation and updates.
- **Todoist Agent** – Manages personal or team tasks.

### 🔌 Integrations Used
- Gmail (send, read, label)
- Google Calendar
- Google Sheets
- Airtable
- Todoist
- Telegram Bot
- OpenAI GPT

---

## 🔧 How to Use

1. **Import workflows into n8n**
   - Use the *Import from JSON* option inside n8n.
2. **Update credentials and tokens**
   - Replace API keys and tokens with your own (Google, Telegram, Airtable).
3. **Customize tasks or flows**
   - Modify filters, conditions, or AI prompts as needed.

---

## 📝 Notes

- The `Window Buffer Memory` and `OpenAI Chat Model` are used in most agents for intelligent, context-aware responses.
- `Webhook` and `Telegram Triggers` are used to trigger flows externally.

---

## 📸 Screenshots

You can find UI previews of workflows in the `assets/` folder.

---

## 📄 License

MIT License – feel free to use and modify for your own automation.

