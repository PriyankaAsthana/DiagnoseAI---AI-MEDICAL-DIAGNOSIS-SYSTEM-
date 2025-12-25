<div align="center">

<h1>🩺 DiagnoseAI</h1>

<h3>Voice-First • Safety-Driven • Built for Real Healthcare</h3>

<p>
  <img src="https://img.shields.io/badge/Status-Deployed-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AI-Healthcare-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Voice-Native-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/FullStack-Production--Grade-black?style=for-the-badge"/>
</p>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&duration=2500&pause=600&color=38BDF8&center=true&vCenter=true&width=700&lines=Not+just+AI.;Not+just+Chat.;Designed+for+Healthcare.;DiagnoseAI." />

</div>

---

## 🧠 “Oh, you mean ChatGPT?”

If building responsible healthcare systems were that simple,  
we wouldn’t be having trust issues with AI in medicine. 💁‍♀️

**DiagnoseAI** is a **voice-first AI medical assistant** engineered for **real healthcare use cases** — not generic chatbot conversations.

Users **speak their symptoms naturally**, and DiagnoseAI processes them through a **medically constrained AI pipeline**, delivering:

- 🎙️ Real-time voice-based medical guidance  
- 📄 Structured medical reports  
- 🕒 Consultation history  
- 🔐 Secure, authenticated sessions  

---

## 🚫 What DiagnoseAI Is NOT

- ❌ A doctor replacement  
- ❌ A generic LLM wrapper  
- ❌ A text-only chatbot  
- ❌ An unsafe “ask anything” medical model  

---

## ✅ What DiagnoseAI IS

- ✅ Voice-native by design  
- ✅ Accessibility-focused  
- ✅ Medically constrained reasoning  
- ✅ Built for elderly & non-technical users  
- ✅ Designed with safety, context & system integrity in mind  

---

## ⚙️ End-to-End System Architecture

```txt
┌──────────────┐
│   User Voice │
└──────┬───────┘
       ↓
┌────────────────────┐
│ AssemblyAI (STT)   │
│ Speech → Text      │
└──────┬─────────────┘
       ↓
┌──────────────────────────┐
│ OpenAI GPT               │
│ Medical Reasoning Layer  │
│ (Safety-Constrained)     │
└──────┬───────────────────┘
       ↓
┌────────────────────┐
│ Response Validator │
│ & Safety Filters   │
└──────┬─────────────┘
       ↓
┌────────────────────┐
│ Vapi Voice Engine  │
│ Real-Time Output   │
└──────┬─────────────┘
       ↓
┌────────────────────┐
│ Node.js Backend    │
│ Reports + Sessions │
└──────┬─────────────┘
       ↓
┌────────────────────┐
│ Drizzle ORM + DB   │
│ Secure Persistence │
└────────────────────┘

🧩 Technology Stack (Exact Usage)
AI & Voice Layer
OpenAI GPT

Symptom interpretation

Medically scoped reasoning

Safe response generation

AssemblyAI

High-accuracy speech-to-text

Handles accents & natural pauses

Vapi

Low-latency voice interaction

Conversational state handling

Backend
Node.js

API orchestration

Consultation lifecycle handling

Report generation logic

Drizzle ORM

Type-safe schema

Structured medical records

Consultation history persistence

Authentication & Security
Clerk

User authentication

Session isolation

Secure access control

Frontend
Next.js

Server-side rendering

Route-level security

React

Interactive consultation UI

TypeScript

Strong typing across stack

Tailwind CSS

Accessible, responsive UI

🧪 API Design (Concrete)
Start Consultation
http
Copy code
POST /api/consultation/start
Creates a new voice session and initializes AI context.

Process Symptoms
http
Copy code
POST /api/consultation/process
Handles transcribed symptoms, AI reasoning, and response generation.

Generate Report
h
Copy code
POST /api/report/generate
Produces a structured medical summary for the session.

Fetch History
http
Copy code
GET /api/consultation/history
Returns authenticated user’s consultation records.

🧠 Safety & Constraint Design
Prompt-level medical boundaries

No absolute or definitive claims

Symptom-based guidance only

Explicit fallback responses

Encourages professional consultation

AI responses are assisted, scoped, and contextual — never authoritative.

⚠️ Medical Disclaimer
DiagnoseAI is not a diagnostic tool and does not replace medical professionals.

All outputs are:

Informational

Preliminary

Context-limited

Users must consult qualified healthcare providers for diagnosis or treatment.

🌍 Intended Use Cases
Preliminary symptom exploration

Accessibility-focused healthcare interfaces

Elderly-friendly medical guidance

Health-tech system architecture demos

Responsible AI experimentation

🏆 Why This Repo Is Different
✔ End-to-end system, not a model demo
✔ Voice-first by design, not an add-on
✔ Medical safety constraints enforced
✔ Real authentication & persistence
✔ Production-ready architecture

This repository demonstrates engineering judgment, not just AI capability.

🧭 Roadmap
diff
Copy code
+ Multilingual voice support
+ Doctor referral workflows
+ Wearable health data ingestion
+ Explainable AI response layers
+ Regulatory-aligned safety checks
📦 Deployment Status
diff
Copy code
+ Live Deployment
+ Secure Auth Enabled
+ Scalable Backend
+ Production-Grade
<div align="center">
DiagnoseAI
Thoughtful AI for Real-World Healthcare

AI in healthcare isn’t a model problem.
It’s a design, safety, and context problem.

</div>
