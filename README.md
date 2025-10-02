# Developing an Intelligent Phone Assistant with FastAPI, Twilio, and OpenAI

## Description
This project demonstrates the implementation of an **intelligent phone assistant** using:
- **FastAPI** for the backend API,
- **Twilio** for handling phone calls,
- **OpenAI GPT** to generate natural and contextual responses.

The goal is to allow a user to call a Twilio number and interact in real-time with an AI-powered voice assistant.

---

## Technologies Used
- [FastAPI](https://fastapi.tiangolo.com/) — Modern Python framework for building APIs.
- [Uvicorn](https://www.uvicorn.org/) — High-performance ASGI server.
- [Twilio](https://www.twilio.com/) — Communication API (voice, SMS).
- [OpenAI](https://platform.openai.com/) — GPT models for text generation.
- [Ngrok](https://ngrok.com/) — Secure tunnel to expose the local server.
- [Nest Asyncio](https://pypi.org/project/nest-asyncio/) — Compatibility with Jupyter/Colab environments.

---

## Block Structure
- **Block 0 — Installation & Ngrok**  
  Installs dependencies and sets up the public tunnel.
- **Block 1 — Environment Variables**  
  Defines Twilio and OpenAI credentials.
- **Block 2 — FastAPI Application**  
  Handles the `/call`, `/voice`, `/bot` endpoints and conversation logic.
- **Block 3 — Bot Testing (Twilio Simulation)**  
  Enables AI testing directly via HTTP request.
- **Block 4 — Server Health Check**  
  Verifies that the API is up and running.
- **Block 5 — Real Call Trigger**  
  Initiates an automated phone call via Twilio.

---

## Prerequisites
1. [Twilio](https://www.twilio.com/) account with a purchased phone number.
2. [OpenAI](https://platform.openai.com/) API key.
3. Python 3.9+ installed.
4. [Ngrok](https://ngrok.com/) account to expose the local server.

---

## ▶️ Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/phone-assistant.git
   cd phone-assistant
