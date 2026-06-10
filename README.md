# 🧠 Smart Document Analyst
### Microsoft Agents League Hackathon — Enterprise Agents Track

![Copilot Studio](https://img.shields.io/badge/Built%20with-Microsoft%20Copilot%20Studio-0078D4?style=for-the-badge&logo=microsoft)
![Work IQ](https://img.shields.io/badge/IQ%20Layer-Work%20IQ-00A4EF?style=for-the-badge&logo=microsoft)
![SharePoint](https://img.shields.io/badge/Knowledge-SharePoint-0078D4?style=for-the-badge&logo=microsoftsharepoint)

---

## 📌 Overview

**Smart Document Analyst** is an enterprise-grade AI agent built on Microsoft Copilot Studio that helps business professionals instantly analyze, summarize, and extract insights from complex business documents such as contracts, reports, and invoices.

Instead of spending hours reading through lengthy legal or financial documents, users can simply ask questions in natural language and get accurate, cited answers in seconds — powered by **Work IQ**.

---

## 🎯 Problem Statement

Every enterprise deals with hundreds of business documents daily:
- 📄 Contracts with hidden risks and penalties
- 📊 Reports with buried action items
- 🧾 Invoices with complex payment terms

Manually reviewing these documents is **time-consuming, error-prone, and expensive**. Smart Document Analyst solves this by bringing AI-powered document intelligence directly into Microsoft 365 workflows.

---

## ✨ Key Features

| Feature | Description |
|--------|-------------|
| 📝 **Document Summarization** | Instant concise summary of any business document |
| ⚠️ **Risk Detection** | Automatically identifies risks, penalties, and compliance issues |
| ✅ **Action Item Extraction** | Pulls out action items with deadlines and responsible parties |
| 💰 **Payment Analysis** | Extracts payment terms, milestones, and financial obligations |
| 📅 **Key Dates Tracking** | Identifies all important dates and deadlines |
| ❓ **Q&A on Documents** | Ask any question about the document in natural language |

---

## 🏗️ Architecture

```
User (Microsoft Teams / M365 Copilot)
        │
        ▼
Microsoft Copilot Studio
        │
        ├── Work IQ (Intelligence Layer)
        │       └── SharePoint Knowledge Base
        │
        ├── Uploaded Documents (PDF, Word, Excel)
        │
        └── Claude Sonnet 4.6 (Reasoning Model)
                │
                ▼
        Smart Document Analyst Agent
```

---

## 🔧 Microsoft IQ Layer Used

### Work IQ ✅
- Connects to **SharePoint** to access enterprise documents
- Builds memory from organizational files and data
- Delivers **cited, grounded answers** to reduce hallucination
- Enables agents to understand business context and relationships

---

## 🚀 How to Set Up

### Prerequisites
- Microsoft 365 account
- Access to Microsoft Copilot Studio
- SharePoint site (optional but recommended)

### Step 1: Open Copilot Studio
Go to [https://copilotstudio.microsoft.com](https://copilotstudio.microsoft.com)

### Step 2: Create a New Agent
Click **"+ Agent"** and describe your agent:
```
I want to build a Smart Document Analyst agent for enterprise use. 
It should analyze business documents like contracts, reports and invoices, 
extract key insights, summarize content, identify risks or action items, 
and answer questions about the document using Work IQ.
```

### Step 3: Add Knowledge Sources
- Go to **Knowledge** tab
- Click **"+ Add Knowledge"**
- Add **SharePoint** (powered by Work IQ) ✅
- Upload your business documents (PDF, Word, Excel)

### Step 4: Configure the Model
- Select **Claude Sonnet 4.6** as the reasoning model
- Keep default instructions or customize as needed

### Step 5: Test the Agent
Use the built-in **Test panel** to verify responses

### Step 6: Deploy
- Go to **Channels** tab
- Add **Microsoft 365 and Microsoft Teams**
- Publish the agent

---

## 💬 Sample Interactions

**User:** What is this contract about?
> **Agent:** This is a Software Services Agreement (SSA-2026-0611) between TechSolutions Pvt. Ltd. and Manav Rachna International Institute, effective June 11, 2026 for 12 months...

**User:** What are the risks and penalties?
> **Agent:** The contract includes three key risk areas: Late Delivery (2% penalty per week), Data Breach liability (up to INR 25,00,000), and Uptime SLA guarantee (99.5% with credit penalties)...

**User:** What are the immediate action items?
> **Agent:** There are 4 immediate action items: 1) Client to provide SharePoint credentials by June 14, 2) Provider to submit project plan by June 18...

---

## 🎥 Demo Video
[Watch the Demo](YOUR_DEMO_VIDEO_LINK_HERE)

---

## 🏆 Hackathon Track
- **Event:** Microsoft Agents League Hackathon
- **Track:** 🏢 Enterprise Agents
- **Tool:** Microsoft 365 Copilot + Copilot Studio
- **IQ Layer:** Work IQ (SharePoint integration)
- **Submission Deadline:** June 14, 2026

---

## 👨‍💻 Built By
**Atharva Sinha**
Manav Rachna International Institute
Built during the Microsoft Agents League Hackathon 2026

---

## 📄 License
This project is submitted as part of the Microsoft Agents League Hackathon and follows Microsoft's hackathon terms and conditions.
