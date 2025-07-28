# crewai-agents
This repository showcases a basic setup using CrewAI, a framework for orchestrating autonomous AI agents with distinct roles and tasks

# 🤖 CrewAI Project

This project uses [CrewAI](https://github.com/joaomdmoura/crewai) to orchestrate autonomous AI agents that collaborate to complete tasks.  
It includes sample agents, tasks, and tools for quick testing and learning.

---

## ⚙️ Quick Setup

### 1. 📥 Clone the Repository

```bash
git clone https://github.com/dincho-kostadinov/crewai-agents
cd crewai-agents

## Create virtual environment
python -m venv .venv

# Activate (Windows)
.venv\Scripts\activate

# Activate (macOS/Linux)
source .venv/bin/activate

pip install -e .

# Create a .env file or export required API keys:

OPENAI_API_KEY=your-openai-key
SERPER_API_KEY=your-serper-key

#Run the crew

python src/your_project/main.py
