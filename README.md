# 🎬 Viral News Autopilot: Self-Generating AI Avatar Channels (n8n + HeyGen)

![n8n](https://img.shields.io/badge/Workflow-n8n-FF6C37?style=flat&logo=n8n&logoColor=white)
![Perplexity](https://img.shields.io/badge/Research-Perplexity-00A699?style=flat&logo=perplexity&logoColor=white)
![OpenAI](https://img.shields.io/badge/AI-GPT--4o-412991?style=flat&logo=openai&logoColor=white)
![HeyGen](https://img.shields.io/badge/Synthesis-HeyGen-blue?style=flat)
![Blotato](https://img.shields.io/badge/Distribution-Blotato-FF0000?style=flat)

---

## 📺 Project Demo
<div align="center">
  <!-- Replace 'YOUR_VIDEO_FILENAME.mp4' with the actual video file you uploaded to GitHub -->
  <video src="https://github.com/Muneeb20019/n8n/raw/main/YOUR_VIDEO_FILENAME.mp4" width="100%" controls></video>
  <p><i>Autonomous AI Newsroom: Real-time trend research and talking-head AI Avatar synthesis.</i></p>
</div>

---

## 🚀 Project Overview
This system is a **Fully Autonomous AI Media House**. It functions as a digital newsroom that operates 24/7 without manual filming or editing. The pipeline proactively researches trending news in specific niches, generates a professional **"Talking Head" AI Avatar** video, and publishes the content to **9+ social media platforms** simultaneously.

By combining **Perplexity's** real-time research with **HeyGen's** high-fidelity avatar synthesis, this workflow enables creators and agencies to scale their digital presence with 100% automation.

---

## 🖼️ System Architecture

### 1. Full Workflow Orchestration
<div align="center">
  <img src="https://raw.githubusercontent.com/Muneeb20019/n8n/main/Video%20Generation%20for%20youtube.png" width="100%" alt="Workflow Overview"/>
</div>

### 2. Recursive Logic & HITL Gate
<div align="center">
  <img src="https://raw.githubusercontent.com/Muneeb20019/n8n/main/YouTube%20short.png" width="100%" alt="HITL Logic Gate"/>
</div>

---

## 🧠 Core Technical Pillars

### 1. 🔍 Autonomous Research & Virality Ranking
The process begins with **Perplexity AI**. Unlike standard LLMs, this node performs real-time web-crawling to identify the top trending news stories in a given niche. A specialized agent then ranks these stories based on **Viral Probability** and compiles a factual report to serve as the foundation for the video script.

### 2. 🔁 Recursive Logic & Human-in-the-Loop (HITL)
To ensure brand safety and premium quality, I implemented a **Conditional Approval Gate**:
- **Audit Phase:** The system sends the generated script to the administrator via email for review.
- **Recursive Loop:** If the script is rejected, the workflow automatically loops back to the next news item in the research queue and regenerates a new script. This ensures the pipeline only proceeds once a "High-Quality" status is achieved.

### 3. 🎭 Asynchronous AI Avatar Synthesis (HeyGen API)
Upon approval, the system interfaces with the **HeyGen REST API**. I utilized custom **JavaScript/Python nodes** to manage the dynamic injection of AI Avatar IDs, Voice IDs, and background assets. The system manages the **Asynchronous Polling Lifecycle**, monitoring the render status until the 4K binary asset is ready for retrieval.

### 4. 🚀 Omnichannel Distribution (Blotato Engine)
The final stage is a massive **Distribution Matrix**. Using the **Blotato API**, the workflow performs a single-burst upload to **TikTok, LinkedIn, Facebook, Instagram, Twitter, YouTube, Threads, Bluesky, and Pinterest**, syncing captions and titles automatically.

---

## ✨ Advanced Features (Production Grade)
- **⚙️ Fault-Tolerant Error Reporting:** A centralized node captures API failures across all 9 distribution streams and sends an automated alert report to the admin.
- **🛡️ Schema Enforcement:** Used **Structured Output Parsers** to ensure the AI's research data perfectly matches the requirements of the script-writing agent.
- **⏳ Dynamic Polling Logic:** Implemented intelligent wait-and-retry states to handle high-compute video renders without causing workflow timeouts.

---

## 🛠️ Technical Stack
| Layer | Technology |
| :--- | :--- |
| **🔄 Automation** | n8n (Recursive Loops & State Management) |
| **🔎 Research** | Perplexity AI (Real-time Web Search) |
| **🧠 AI Brain** | OpenAI GPT-4o |
| **📹 Synthesis** | **HeyGen API** (AI Avatar Synthesis) |
| **📧 Approval** | SMTP / Gmail (Human-in-the-loop) |
| **📢 Distribution** | **Blotato** (Omnichannel Social Engine) |

---

## 📝 How to Use
1.  **Orchestration:** The system triggers every 3 days at 10 AM via the **Schedule Trigger**.
2.  **Audit:** The admin reviews the "Viral Script" sent via email and clicks **Approve**.
3.  **Synthesis:** Upon approval, the AI Avatar begins rendering the video automatically.
4.  **Publish:** The final video is blasted to all 9 social media channels with AI-optimized metadata.

---

## ✍️ Author
**Muneeb Ali Khan**
- **GitHub:** [@Muneeb20019](https://github.com/Muneeb20019)
- **LinkedIn:** [Muneeb Ali Khan](https://www.linkedin.com/in/muneeb-ali-khan-2a1675365)
