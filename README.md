# 🚀 Autonomous AI LinkedIn Growth Engine (Self-Hosted)

A high-performance, zero-cost content automation pipeline built with **n8n**. This engine autonomously researches, writes, designs, and publishes professional LinkedIn content, keeping your personal brand active 24/7.

[![n8n](https://img.shields.io/badge/Automation-n8n-red)](https://n8n.io/)
[![Groq](https://img.shields.io/badge/AI-Groq%openai/gpt-oss-120b%203-orange)](https://groq.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 💡 Why This Project?
Maintaining a consistent presence on LinkedIn is time-consuming. This project solves that by using a **self-hosted automation stack** that leverages cutting-edge LLMs and Image Generation without expensive monthly subscriptions. 

## ✨ Key Features
- **🤖 Intelligent Topic Discovery:** Uses **Groq (openai/gpt-oss-120b)** to identify trending topics in AI and Full-Stack Development.
- **✍️ SEO-Optimized Copywriting:** Generates engaging posts with hooks, structured bullet points, and high-conversion CTAs.
- **🎨 Futuristic Visuals:** Integrates with **Pollinations AI** to generate stunning, context-aware 2026-style imagery.
- **📱 Instant Monitoring:** Sends a real-time notification via **Pushbullet** to your mobile phone the second a post goes live.
- **💰 Zero Operational Cost:** Runs entirely on free tiers and self-hosted infrastructure.

---

## 🛠️ The Tech Stack
- **Orchestration:** [n8n](https://n8n.io/) (Self-hosted via Docker)
- **Language Model:** [Groq Cloud](https://groq.com/) (openai/gpt-oss-120b)
- **Image Generation:** [Pollinations.ai](https://pollinations.ai/)
- **Notifications:** [Pushbullet API](https://www.pushbullet.com/)
- **Deployment:** LinkedIn Developer API

---

## 🚀 Quick Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/n8n-ai-linkedin-automation.git](https://github.com/YOUR_USERNAME/n8n-ai-linkedin-automation.git)```

###  **Setup**

1. **Import the Workflow:**
   - Open your **n8n dashboard**.
   - Go to **Workflows** > **Import from File**.
   - Select `linkedin_flow.json` from this repository.

2. **Configure Nodes:**
   - **LinkedIn Node:** Connect your LinkedIn account via OAuth2.
   - **Groq Node:** Add your API key in the Header `Authorization: Bearer YOUR_KEY`.
   - **Pushbullet Node:** Add your Access Token in the Header `Access-Token: YOUR_TOKEN`.

3. **Set the Schedule:**
   - Update the **Schedule Trigger** node to your desired posting frequency (e.g., Daily at 9:00 AM).

---

### 📁 **Repository Structure**

* **`linkedin_flow.json`**: The complete n8n workflow export.
* **`README.md`**: Project documentation.
* **`.gitignore`**: Protection for your local environment files.

---

### 🤝 **Contributing**

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/YOUR_USERNAME/n8n-ai-linkedin-automation/issues).

---

### 👩‍💻 **Developed By**

**Aqsaa Qaazi** *Full Stack AI Developer* [LinkedIn Profile](https://www.linkedin.com/in/aqsaa-qaazi-10aa76401/)

> **Disclaimer:** *This project is for educational and automation purposes. Ensure your content follows LinkedIn's community guidelines.*
