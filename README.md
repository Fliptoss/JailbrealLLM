# 🚨 JailBreakLLM
An Effective Fine-Tuned LLaMa Model Designed to Jailbreak OpenAI GPT-4o

## 📄 Overview
**JailBreakLLM** is a fine-tuned version of Meta's LLaMa 3.1 8B model, specifically crafted to generate adversarial prompts capable of bypassing the safety guardrails of OpenAI's GPT-4o. This project highlights the vulnerabilities in modern LLM alignment protocols by demonstrating how a smaller open-source model can effectively jailbreak a state-of-the-art proprietary LLM.

- 🎯 **Attack Success Rate (ASR):** 85% in one-shot jailbreak attempts.
- ⚡ Focused on roleplay and intent obfuscation techniques.
- 🛡️ Designed as a research tool to expose and analyze weaknesses in LLM safety mechanisms.

---

## 🚀 Features
- Fine-tuned using a custom **Jailbreak FineTune Dataset** (204 handcrafted samples).
- Utilizes **LoRA** and **Unsloth.ai** for efficient parameter-efficient fine-tuning (PEFT).
- Prioritizes **one-shot jailbreaks** for practical, low-compute attack scenarios.
- Demonstrates how minimal compute resources can compromise larger, aligned LLMs.

---

## 📚 Methodology
1. **Dataset Creation:**  
   Curated malicious intents paired with effective jailbreak prompts targeting GPT-4o.
   
2. **Fine-Tuning:**  
   Applied **LoRA** via Unsloth.ai to adapt LLaMa 3.1 8B for generating adversarial prompts.

3. **Evaluation:**  
   Benchmarked against GPT-4o's safety filters to measure ASR, undesired outputs, and outright rejections.

---

## 🏗️ System Architecture
- **Core Model:** LLaMa 3.1 8B (Fine-Tuned)
- **Tech Stack:** 
  - Python
  - Hugging Face Transformers
  - Unsloth.ai
  - LoRA (Low-Rank Adaptation)
- **Target:** GPT-4o via API access (black-box interaction)

---

## 📊 Results
- **85%** Success Rate in one-shot jailbreaks.
- Identified GPT-4o vulnerabilities in categories like:
  - Roleplay exploitation
  - Intent obfuscation
  - Sensitive topic manipulation

---

## ⚠️ Disclaimer
This project is intended **solely for research and educational purposes** to highlight security gaps in LLM alignment strategies. Misuse of this tool for malicious purposes is strictly discouraged.

---

## 🔮 Future Work
- Expand dataset for multi-turn jailbreak strategies.
- Test transferability across other proprietary models.
- Investigate defense mechanisms and automated mitigation techniques.

---

## 📎 References
- Meta LLaMa 3.1
- OpenAI GPT-4o
- Unsloth.ai
- LoRA: Low-Rank Adaptation for Efficient Fine-Tuning

---

## 🤝 Contributors
- Rasel Ahmed Antor  
- Kazi Tamjeed Newaz  
- Sameer Mahmud  
- Md Asif Mostafa  
- Tamima Tabassum Anan  
- Nilasha Mondal  

Supervised by **Dr. Nafees Mansoor**  
_Department of Computer Science and Engineering, University of Liberal Arts Bangladesh_
