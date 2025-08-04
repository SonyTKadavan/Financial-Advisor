# 💡 AI Agent for Digital Financial Literacy

This project is developed as part of the *IBM SkillsBuild SB4Academia Challenge 2025* (Problem Statement No. 7).

## 🧠 Objective

To build an AI-powered assistant that educates users — especially students, beginners, and rural citizens — about digital financial concepts such as UPI, budgeting, interest rates, and scam prevention.

## 🚀 Built With

- *IBM Watsonx.ai*
- *Granite Foundation Model (13B Chat)*
- *Natural Language Processing (NLP)*
- *Retrieval-Augmented Generation (RAG)*
- *Cloud Object Storage*
- *LangGraph + ReAct Architecture*

## 🧩 Features

- ✅ Simple answers to financial questions (UPI, loans, interest rates, etc.)
- ✅ Scam and fraud awareness (phishing, OTP fraud)
- ✅ RAG-based document retrieval using vector index
- ✅ Links to trusted resources (RBI, NPCI, Cybercrime portal)
- ✅ Multilingual-friendly instructions (regional language support optional)

## 👨‍🏫 End Users

- Students and Young Adults  
- Rural Citizens and First-time Internet Users  
- NGOs and Financial Literacy Campaigns  
- Government Digital India Projects

## 🔐 Safety Highlights

- Does *not* collect personal data (Aadhaar, OTPs, passwords, bank info)
- Warns about scams and links users to official help portals

## 📌 How to Run

1. Create a new project in [IBM Watsonx.ai](https://cloud.ibm.com)
2. Upload the .txt file as a vector index
3. Set up your agent with ReAct + LangGraph
4. Attach IBM Granite model + runtime
5. Deploy via Deployment Space with Cloud Object Storage
6. Test with user queries like:
   - "How to use UPI?"
   - "What is phishing?"
   - "How to plan my monthly budget?"


---

