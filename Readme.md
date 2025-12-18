# Moshi Voice Chatbot

A real-time AI voice chatbot powered by **Kyutai Lab’s Moshi model**.  
Speak into your microphone, and Moshi listens, reasons, and responds in natural voice almost instantly, using **stateful streaming speech-to-speech AI**.

---

## **Features**

- Real-time **speech-to-speech** using Moshi
- Bi-directional audio streaming via **WebSockets**
- Maintains **conversation context** per user
- Low-latency streaming with **Opus audio compression**
- React frontend for **microphone capture and audio playback**
- Serverless deployment supported via **Modal**
- GPU-backed sessions for **isolated, fast inference**

---

## **Tech Stack**

| Component           | Technology/Library           |
|--------------------|-----------------------------|
| Backend             | Python, FastAPI, Modal      |
| Frontend            | React, Web Audio API        |
| AI Model            | Moshi (Speech-to-Speech)   |
| Audio Streaming     | WebSockets, Opus codec      |
| Deployment          | Modal (serverless GPU)      |

---

## **Installation (Local Development)**

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/moshi-voice-chatbot.git
cd moshi-voice-chatbot
