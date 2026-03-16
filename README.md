# ai-guardrail-red-teamer
This project tests the "Safety" of an AI Chatbot. It automatically attempts to "break" the AI to see if it will violate company policy.

# 🛡️ AI Guardrail Red-Teamer

An automated security testing suite designed to "Red Team" LLM applications by simulating adversarial attacks.

### 🎯 The Problem
Standard QA doesn't account for **Adversarial Prompts**. Users can "Jailbreak" an AI to bypass safety filters, leading to data leaks, brand damage, or toxic outputs.

### 🧠 The AI Solution
This project automates **Safety & Trust** testing using **DeepEval**. It subjects the LLM to:
- **Prompt Injection Attacks:** Attempting to override system instructions.
- **PII Leakage Scenarios:** Trying to extract sensitive user data.
- **Toxicity & Bias Audits:** Baited queries to check for unprofessional responses.

### 🛠 Tech Stack
- **Python / Pytest**
- **DeepEval** (LLM-as-a-Judge)
- **OpenAI GPT-4o** (The Security Evaluator)

### 📈 Business Impact
- **Brand Protection:** Ensures AI never outputs harmful or biased content.
- **Data Security:** Validates that the LLM cannot be manipulated into leaking PII.
