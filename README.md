# IT Service Chatbot 🤖

A Streamlit-based chatbot that helps employees with common IT issues like password resets, network troubleshooting, software installations, and ticket status inquiries. Combines **FAQ-based responses** with **OpenAI GPT-3.5-turbo** for dynamic answers.

---

## Features

- Responds to common IT questions using stored FAQ data
- Step-by-step guidance for IT issues
- Uses OpenAI GPT-3.5-turbo for queries not in FAQ
- Maintains conversation history during the session
- Simple and interactive Streamlit UI

---

## Prerequisites

- Python 3.8+
- OpenAI API key
- Streamlit
- `pickle` module (standard in Python)

Install required packages:

```bash
pip install openai streamlit
