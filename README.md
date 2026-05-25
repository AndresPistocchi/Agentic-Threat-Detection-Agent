# Agentic-Threat-Detection-Agent
Using different LLMs to be able to identify threats and any security gaps

## Key Concepts & Definitions

### 🔑 API (Application Programming Interface)
A way for two pieces of software to talk to each other. In this project, my agents send requests to an AI provider's API and get responses back. Think of it like a waiter — you (the code) tell the waiter (the API) what you want, and the kitchen (the AI model) makes it.

### 🔑 API Key
A secret password that proves who you are to an API provider. It's tied to your account and controls what you can access. **Never share it publicly.** In this project I use a Groq API key.

### 🔑 .env File (Environment Variables File)
A simple config file that stores settings your app needs to run — things like API keys, model names, server addresses. Instead of hardcoding these directly in Python code, the app reads them from `.env` at startup. Benefits:
- Keep secrets out of your code
- Change settings without touching the actual code
- Share code publicly without exposing your keys

My `.env` file looks like:

