# 🤖 AI Agents Collection  

This repo contains **5 AI-powered agents** built with n8n + OpenAI.  
Each agent has its **name, description, and source code link** neatly listed below.  

---

## 📊 Agents Overview  

| 🧑‍💻 Agent Name | 📄 Description | 🔗 Source Code |
|-----------------|----------------|----------------|
| 📩 Instagram DM Inbox Agent | Automates Instagram DMs using ManyChat + OpenAI. Replies in your style and tone. | [View JSON](./AI%20agent%20for%20Instagram%20DM_inbox.%20Manychat%20+%20Open%20AI%20integration.json) |
| 📄 CV/Resume PDF Parser Agent | Extracts structured data (name, email, skills, education) from uploaded CV PDFs. Saves to Airtable. | [View JSON](./CV%20Resume%20PDF%20Parsing%20with%20Multimodal%20Vision%20AI.json) |
| 🚗 License Plate Extraction Agent | Upload a car image → Extracts license plate number using AI vision. | [View JSON](./Extract%20license%20plate%20number%20from%20image%20uploaded%20via%20an%20n8n%20form.json) |
| 📝 Job Application Submission Agent | Handles multi-step job applications, parses resumes, pre-fills forms, and saves to Airtable. | [View JSON](./Handling%20Job%20Application%20Submissions%20with%20AI%20and%20n8n%20Forms.json) |
| 📊 Job Applications with GSheets & Drive | Similar to above but integrated with Google Sheets + Drive for storage & tracking. | [View JSON](./Job_Application_GSheets_GDrive.json) |

---

## 🚀 Usage – Run on n8n Website (Cloud)  

You don’t need to install anything locally. You can run these AI Agents directly on the **n8n website**:  

### 1️⃣ Create an Account  
- Go to [n8n.io](https://n8n.io)  
- Sign up for a free account (n8n Cloud).  

### 2️⃣ Open n8n Editor  
- After logging in, you’ll see the **n8n workflow editor** in your browser.  
- This is where you can build and import workflows.  

### 3️⃣ Import Workflow  
- Click on **Workflows → Import from File**.  
- Choose one of the `.json` files from this repository (for example: `CV Resume PDF Parsing with Multimodal Vision AI.json`).  

### 4️⃣ Add API Credentials  
Depending on the agent, you’ll need to connect services inside n8n:  
- **OpenAI** → for AI/LLM responses  
- **Airtable** → for storing candidate/job data  
- **Google Drive / Google Sheets** → for file & data storage  
- **ManyChat** → for Instagram DM automation  

👉 Go to **Credentials** in n8n and add the required API keys before running the workflow.  

### 5️⃣ Run the Workflow  
- Click **Execute Workflow** in the editor.  
- Depending on the workflow:  
  - Upload a CV (PDF)  
  - Upload a car image  
  - Submit a job application form  
  - Send an Instagram DM test  
- The workflow will run, and you’ll see the results in real time.  

### 6️⃣ Automate & Deploy  
- Once tested, you can:  
  - Turn on the workflow for continuous automation  
  - Trigger it via webhooks, forms, or schedules  
  - Monitor results directly inside your n8n dashboard  

---

✅ That’s it! In just a few clicks, you can have these **5 AI Agents** running on the cloud without installing anything locally.  

