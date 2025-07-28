# crewai-agents
This repository showcases a basic setup using [CrewAI](https://github.com/joaomdmoura/crewai), a framework for orchestrating autonomous AI agents with distinct roles and tasks.The project includes sample agents, tasks, and tools for quick testing and learning.

## ⚙️ Quick Setup

```bash
# 1. Clone the Repo
git clone https://github.com/dincho-kostadinov/crewai-agents
cd crewai-agents

# 2. Create virtual environment
python -m venv .venv
!!! should select your version of the Python from the .venv not the global one.
for Visual studio code ctrl+shift+p select "Select interpeter" and chose the python from .venv/Scripts/python.exe 

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
python crew_yaml.py
```

### Run Jupyter Notebooks (Optional)
This project includes Jupyter notebooks for testing agents, experimenting with tasks, and visualizing results.

```bash
pip install notebook

and download the required extension for Visual studio to run the notebooks there.
