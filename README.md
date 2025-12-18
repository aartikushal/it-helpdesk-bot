# 🤖 IT Service Chatbot using Streamlit & OpenAI

An AI-powered **IT Service Chatbot** built with **Streamlit** and **OpenAI GPT**, designed to assist employees with common IT-related queries such as password resets, network issues, software installation, and ticket status.

---

## 📌 Project Overview

This project combines:
- **Rule-based FAQ matching**
- **Generative AI responses using OpenAI**
- **Interactive chat interface with Streamlit**

The chatbot first attempts to answer user queries using predefined IT FAQs.  
If no suitable FAQ match is found, it intelligently falls back to an OpenAI language model for a contextual response.

---

## 🚀 Key Features

- 💬 Interactive chat UI using Streamlit  
- 🧠 Hybrid approach: FAQ-based + AI-based responses  
- 🔐 Secure OpenAI API key handling via environment variables  
- 🗂 Persistent FAQ storage using Pickle  
- 📜 Maintains conversation history for better context  
- ⚡ Real-time responses  

---

## 🏗 Architecture Flow

1. User enters a query in the Streamlit chat interface  
2. Chatbot checks predefined IT FAQs  
3. If a match is found → returns FAQ response  
4. If no match → sends conversation to OpenAI GPT model  
5. AI-generated response is returned to the user  
6. Conversation history is stored in session state  

---

## 🧠 Supported IT Use Cases

- 🔑 Password reset assistance  
- 🌐 Network / internet troubleshooting  
- 💾 Software installation guidance  
- 🎫 IT ticket status queries  
- 📞 Contact IT support information  

---

## 📂 Project Structure

