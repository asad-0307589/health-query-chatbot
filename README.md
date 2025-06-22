# 🩺 Health Query Chatbot

This project is part of **Task 4: General Health Query Chatbot (Prompt Engineering Based)** for an internship assignment. The goal is to build a user-friendly chatbot that answers general health-related questions using a large language model (LLM) while ensuring safe and responsible communication.

---

## 🎯 Task Objective

- Develop a chatbot capable of responding to general health queries.
- Apply **prompt engineering** to simulate a helpful and responsible medical assistant.
- Implement **safety filters** to ensure no harmful or unauthorized medical advice is provided.
- Use an open-source LLM  through Hugging Face.

---

## 📊 Dataset Used

- **No explicit dataset** was used. The chatbot generates responses using the pre-trained knowledge of the language model. All inputs are user queries typed into the console.

---

## 🧠 Models Applied

- **Mistral-7B-Instruct-v0.1** (via Hugging Face Transformers)
  - A powerful open-source instruction-tuned LLM
  - Hosted on Hugging Face Hub
- The model is accessed through the Transformers library with a custom system prompt to guide its behavior.

---

## 🔑 Key Results & Findings

- The chatbot successfully responds to a wide range of general health-related questions (e.g., sore throat, sleep tips, hydration).
- Prompt engineering with a structured system message ensures responses are:
  - Polite and easy to understand
  - Safe (includes disclaimers)
  - Avoid giving diagnosis or treatment
- The final model uses:
  - Token-based authentication for secure model access
  - Environmental variable handling to avoid hardcoding sensitive data

---

## ⚠️ Disclaimer

This chatbot is intended **only for general informational purposes**. It does not provide any medical diagnosis or treatment. Always consult a qualified healthcare provider for any medical concerns.

---

# Set your Hugging Face token in .env
echo "HF_TOKEN=your_token_here" > .env

