# LLM + RL Debate Agent  
**AI Agents That Argue, Learn, and Win** 🤖⚡  

This project implements an **autonomous debate system** where two Large Language Model (LLM) agents argue opposing sides of a topic. Their performance is optimized using **Reinforcement Learning (RL)** to improve persuasion, logical coherence, and factual accuracy over time.  

The system includes:  
- 🎯 **LLM-based Agents** — Built using Hugging Face Transformers.  
- 🧠 **Reinforcement Learning Fine-Tuning** — Agents learn better debate strategies using PPO.  
- 🌐 **Full-Stack Web Interface** — Next.js (Vercel) frontend + Supabase backend for storing debates, feedback, and scores.  
- 📊 **Analytics Dashboard** — Visualize agent progress, win rates, and debate quality metrics.  
- ☁️ **Colab Training Support** — Train agents in the cloud, deploy results instantly to the web app.  

---

## Features  
- **Topic Generator** — Auto-generates random or user-defined debate topics.  
- **Timed Rounds** — Agents respond in multiple back-and-forth exchanges.  
- **User Voting** — Visitors can vote for the more convincing agent.  
- **RL Feedback Loop** — Votes and metrics feed directly into PPO training.  
- **Leaderboard** — Track the top-performing debate agents.  

---

## Tech Stack  
- **Frontend**: Next.js + TailwindCSS (Vercel Deployment)  
- **Backend**: Supabase (PostgreSQL + Auth + Storage)  
- **AI**: Hugging Face Transformers, Stable-Baselines3 PPO  
- **Training**: Google Colab Pro (optional)  
- **Deployment**: Vercel (frontend), Supabase (backend)  

---

## Installation  
```bash
git clone https://github.com/aditya-hubli/llm-rl-debate-agent.git
cd llm-rl-debate-agent
pip install -r requirements.txt
