# LinkedIn Post Scheduler (n8n Workflow)

This workflow automates **LinkedIn post scheduling** using [n8n](https://n8n.io).  
It generates **3 different kinds of posts** daily with AI, refines them, and publishes directly to LinkedIn at your chosen time.  

![Workflow Screenshot](./workflow.png)

---

## 🔄 Workflow Overview

1. **Daily Schedule**  
   - Triggers the workflow automatically at a set time.  

2. **AI Agent 1, AI Agent 2, AI Agent 3**  
   - Each AI agent generates a **different style of LinkedIn post** (e.g. professional, conversational, thought-leadership).  
   - Powered by **Google Gemini Chat Model**.  

3. **Simple Memory**  
   - Maintains context across AI generations for consistency.  

4. **Post to LinkedIn**  
   - Automatically publishes the generated post(s) to your LinkedIn account.  

---

## ⚙️ Setup Instructions

1. **Download & Import**  
   - Get the workflow file: `linkedinpostscheduler.json`.  
   - In n8n, go to **Import from File** and upload it.  

2. **Set Up Credentials**  
   - Configure your **LinkedIn API credentials** in n8n.  
   - Add your **Google Gemini API key**.  

   👉 Watch this video tutorial for LinkedIn setup:  
   [Self-Hosted n8n LinkedIn API Credentials Setup | Step-by-Step Guide](https://youtu.be/SFLC0okOvnE)  

3. **Adjust the Schedule**  
   - Open the **Daily Schedule node**.  
   - Set the time and frequency (e.g., daily at 9 AM).  

4. **Customize Prompts**  
   - Modify AI Agent prompts to match your brand voice, tone, or specific campaign needs.  

---

## 📺 Video Tutorials

- [Automate LinkedIn Post Scheduling with n8n | Step-by-Step Workflow Tutorial (Free Tool)](https://youtu.be/4PfKLpFV7Ew)  
- [Self-Hosted n8n LinkedIn API Credentials Setup | Step-by-Step Guide](https://youtu.be/SFLC0okOvnE)  

---

## ✅ Example Use Cases

- Automate **daily LinkedIn posting** for personal branding or company pages.  
- Create **different styles of content** (professional, casual, thought leadership) in one workflow.  
- Save time and stay consistent on LinkedIn without manual effort.  

---

## 📂 Files in This Folder

- `linkedinpostscheduler.json` → The exported n8n workflow.  
- `workflow.png` → Workflow diagram (screenshot).  
- `README.md` → This documentation.  

---

## 🚀 Future Enhancements

- Add image or video upload for richer LinkedIn posts.  
- Pull trending industry topics and auto-generate posts.  
- Extend to multi-platform posting (Twitter, Facebook, Instagram).  

---
