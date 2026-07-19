# 🛡️ PromptShield - AI Prompt Security Firewall

> Real-time AI Prompt Security, Bias Detection & Optimization using Google Gemini

## 🎯 Problem Statement
As GenAI adoption explodes, prompt injection attacks, bias, and data leakage have become the #1 security threat to LLM applications (OWASP Top 10 for LLMs 2024).

## 💡 Solution
PromptShield acts as a real-time security firewall that analyzes every prompt BEFORE it reaches the LLM. It detects threats, scores quality, and auto-generates optimized safe versions.

## ✨ Features
- 🔍 Real-time Risk Scoring (Low/Medium/High)
- 💉 Prompt Injection Detection
- ⚖️ Bias & Toxicity Detection  
- 🔒 Privacy Risk Analysis
- ✨ Automatic Prompt Optimization
- 📊 Quality Scoring (0-100)

## 🛠️ Tech Stack
- **Frontend:** Streamlit
- **AI Engine:** Google Gemini 1.5 Flash
- **Language:** Python 3.11+
- **Deployment:** Streamlit Cloud

## 🚀 How GenAI is Used
1. **Multi-Stage Prompt Chaining** for layered analysis
2. **Structured JSON Schema Enforcement** for reliable outputs
3. **Chain-of-Thought Reasoning** for security decisions
4. **Zero-Shot Classification** for threat detection
5. **Context-Aware Rewriting** for optimization

## 📦 Installation
```bash
git clone https://github.com/YOUR_USERNAME/promptshield-ai
cd promptshield-ai
pip install -r requirements.txt
streamlit run app.py
