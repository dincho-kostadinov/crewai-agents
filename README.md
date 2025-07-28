# crewai-agents
This repository showcases a basic setup using [CrewAI](https://github.com/joaomdmoura/crewai), a framework for orchestrating autonomous AI agents with distinct roles and tasks.The project includes sample agents, tasks, and tools for quick testing and learning.

## ⚙️ Quick Setup

### 1. Clone the Repo
```bash
git clone https://github.com/dincho-kostadinov/crewai-agents
cd crewai-agents

# 2. Create virtual environment
python -m venv .venv

# 3. Activate (Windows)
.venv\Scripts\activate

# Activate (macOS/Linux)
source .venv/bin/activate

# 4. Install dependencies
pip install -e .

# 5. Create a .env file or export required API keys:

OPENAI_API_KEY=your-openai-key
SERPER_API_KEY=your-serper-key

# 6.Run the crew

python src/your_project/main.py
