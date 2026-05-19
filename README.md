# 🚗 Automotive CRM — Multi-Agent AI Automation System using n8n & Generative AI

![Architecture](Screenshot%202026-05-18%20233351.png)

---

# 📌 Project Title

**Automotive CRM — Agentic AI Powered Multi-Agent Automation System**

---

# 📖 Project Description

Automotive CRM is an enterprise-style AI automation system designed using **n8n workflow automation**, **Google Gemini AI**, and **multi-agent orchestration architecture**.  

The system automates automotive dealership customer operations such as:

- Vehicle Sales Enquiries
- EMI & Finance Assistance
- Vehicle Service Reminders
- Inventory Clearance Campaigns
- Customer Retention & Feedback Monitoring

Traditional CRM systems require heavy manual intervention, slower response times, and human routing between departments.  
This project transforms the workflow into an **AI-driven autonomous backend automation system** capable of understanding customer intent, routing requests intelligently, and generating personalized responses automatically.

The architecture follows a **Supervisor-Worker Multi-Agent Model**, where one AI agent acts as a central routing brain while specialized agents handle specific business functions.

---

# 🎯 Main Objectives

The major objectives of this project are:

- To automate dealership CRM workflows using AI
- To reduce manual customer handling
- To improve response speed and operational efficiency
- To implement intelligent intent classification
- To design a scalable multi-agent AI architecture
- To integrate Generative AI into real-world business workflows
- To reduce hallucinations using structured outputs and role-based prompting
- To explore Agentic AI concepts using n8n

---

# 🧠 Core Technologies Used

| Technology | Purpose |
|---|---|
| n8n | Workflow automation platform |
| Google Gemini 2.5 Flash | AI reasoning and response generation |
| JSON Schema | Structured AI outputs |
| Prompt Engineering | Controlled AI behavior |
| Webhooks | Triggering workflow execution |
| Switch Nodes | Intent-based routing |
| Multi-Agent Architecture | Specialized AI task handling |
| Generative AI | Intelligent conversational automation |

---

# 🏗️ System Architecture

The workflow follows a **Multi-Agent AI Architecture**.

## Workflow Structure

```text
Customer Message
       ↓
Chat Trigger
       ↓
Supervisor Agent
(Intent Classification)
       ↓
Switch Routing Logic
       ↓
------------------------------------------------
|        |         |         |         |
Sales   Finance   Service  Inventory Retention
Agent    Agent      Agent     Agent      Agent
       ↓
Automated Customer Response
