# Aegis AI - Enterprise AI Firewall 🛡️

**🔴 Live Demo: [https://vikas-daddi.github.io/aegis-ai-firewall/](https://vikas-daddi.github.io/aegis-ai-firewall/)**

Aegis AI is an advanced, client-side simulation of an enterprise AI security firewall, built for the **HackCulture Hackathon**. It intercepts, analyzes, and blocks malicious traffic between users and Large Language Models (LLMs) in real-time.

## 🚀 Features

- **Real-Time Threat Interception:** Monitors user prompts before they reach the LLM.
- **Rules Engine:** Granular control to toggle specific threat detections:
  - 🛑 **Prompt Injection / Jailbreaks:** Blocks attempts to override system instructions (e.g., DAN mode).
  - 🔒 **PII Leakage Prevention:** Detects and blocks sensitive data like SSNs and Credit Cards.
  - ⚠️ **Toxicity & Harm Filter:** Prevents requests for malicious code or exploits.
- **Automated Red-Team Simulator:** A built-in stress tester that automatically fires a barrage of attacks at the system to demonstrate speed and resilience.
- **Persistent Threat Logs:** Records all blocked requests with timestamps and confidence scores for compliance auditing.
- **Premium UI:** Built with modern glassmorphism, dynamic animations, and a responsive Single Page Application (SPA) architecture.

## 🛠️ Technology Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Architecture:** Client-side SPA (No backend dependencies required for demo)
- **Styling:** Custom CSS variables, Flexbox/Grid layouts, Glassmorphism effects
- **Icons:** FontAwesome

## 🏃 How to Run Locally

Since this is a lightweight frontend application, no complex backend installation is required. You can run it instantly using a simple local server.

1. Clone the repository:
   ```bash
   git clone https://github.com/Vikas-daddi/aegis-ai-firewall.git
   ```
2. Navigate to the project directory:
   ```bash
   cd aegis-ai-firewall
   ```
3. Start a local server (using Python, which is pre-installed on most systems):
   ```bash
   python -m http.server 8000
   ```
4. Open your web browser and navigate to:
   **http://localhost:8000**

## 💡 How to Demo (For Judges)

1. **The Basics:** Type a normal prompt to see it pass, then click the **"Quick Tests"** buttons (Jailbreak, PII, Harmful) to watch the firewall instantly block the request and update the live stream.
2. **The "Wow" Factor:** Click the **"Launch Attack Simulation"** button in the bottom left. The system will automate a rapid-fire bot attack, demonstrating how Aegis handles high-velocity threats in real-time.
3. **The Analytics:** Navigate to the **Threat Logs** via the sidebar to view a permanent, auditable record of all blocked attacks.
4. **The Controls:** Navigate to **Settings** to show how enterprise IT admins can toggle the global security strictness or securely purge logs.

## 👨‍💻 Developer

Built with ❤️ by **Vikas Daddi** for the HackCulture Hackathon.
