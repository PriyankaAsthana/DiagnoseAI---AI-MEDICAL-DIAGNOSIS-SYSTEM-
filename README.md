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
│ Secure Persistence│
└────────────────────┘
