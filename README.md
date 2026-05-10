# `~/workspace/manas-patil/MAIN`

<details open>
  <summary><b>🗂️ Explorer (Click to collapse)</b></summary>
  &nbsp;&nbsp;&nbsp;&nbsp;📂 <b>src/</b><br>
  &nbsp;&nbsp;&nbsp;&nbsp;┣━━ 📄 <a href="#-profilepy">profile.py</a><br>
  &nbsp;&nbsp;&nbsp;&nbsp;┣━━ 📄 <a href="#-skillspy">skills.py</a><br>
  &nbsp;&nbsp;&nbsp;&nbsp;┗━━ 📄 <a href="#-life_and_researchpy">life_and_research.py</a><br>
  &nbsp;&nbsp;&nbsp;&nbsp;📂 <b>bin/</b><br>
  &nbsp;&nbsp;&nbsp;&nbsp;┗━━ 📟 <a href="#-terminal">telemetry.sh</a><br>
</details>

<br>

### 📄 `profile.py`
```python
class DeveloperProfile:
    def __init__(self):
        self.status = "Currently building AI from the math up (understanding and building AI from the ground up from scratch)."
        self.location = "Bardoli, Gujarat, India"
        self.mission = "I don't just use APIs; I break systems, learn the math, and build deep tech from the ground up."
        
    def get_research_background(self):
        return {
            "role": "Small Researcher",
            "publications": [
                "Data-Driven Rockfall Assessment using Synthetic Training and CNN–XGBoost Integration"
            ]
        }
```

### 📄 `skills.py`
```python
import torch
import torch.nn as nn

class ManasTechStack(nn.Module):
    def __init__(self):
        super(ManasTechStack, self).__init__()
        
        # 1. Input Layer: Core Languages
        self.languages = torch.tensor(["Python", "JavaScript", "Java", "C++"])
        
        # 2. Hidden Layers: Deep Learning & AI Weights
        self.ai_ml_models = nn.Sequential(
            nn.Linear("TensorFlow", "PyTorch"),
            nn.Linear("scikit-learn", "XGBoost"),
            nn.Linear("pandas", "NumPy")
        )
        self.ai_tools = torch.tensor(["RAG Pipelines", "Gemini API", "LiveKit", "LangChain", "ChromaDB"])
        
        # 3. Hidden Layers: Infrastructure & Backend
        self.backend = nn.Sequential(
            nn.Linear("Node.js", "Express.js"),
            nn.Linear("FastAPI", "TiDB"),
            nn.Linear("MongoDB", "MySQL"),
            nn.Dropout("Redis (RQ)") 
        )
        self.devops_tools = torch.tensor(["Git", "GitHub", "Postman", "Cloudinary", "Firebase"])
        
        # 4. Output Layer: Frontend Interface
        self.frontend = torch.tensor(["React.js", "Tailwind CSS", "Material UI"])

    def forward(self, input_data):
        return "Scalable AI Systems & Full-Stack Architectures"
```

### 📄 `life_and_research.py`
```python
def get_technical_achievements():
    return [
        "Secured Rs 1,50,000 at UTU Idea Hunt for an ECG predictive model.",
        "Presented Data-Driven Rockfall Assessment using CNN-XGBoost at the 7th MIND 2025 International Conference in Jaipur."
    ]

def get_hobbies():
    return ["Travelling", "Listening to music", "Playing badminton"]

if __name__ == "__main__":
    achievements = get_technical_achievements()
    hobbies = get_hobbies()
    print("Executing life sequence... success.")
```

### 📟 `Terminal`
```zsh
❯ ./fetch_github_telemetry.sh
Loading stats from GitHub API... [OK]
```

<p align="center">
  <a href="https://github.com/patilmanas04">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=patilmanas04&hide_border=true&theme=onedark" alt="GitHub Streak" />
  </a>
</p>

```zsh
❯ ./initiate_contact.sh
Porting transmission lines...
```

<p align="center">
  <a href="https://linkedin.com/in/patilmanas" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://dev.to/patilmanas" target="_blank">
    <img src="https://img.shields.io/badge/DEV.TO-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" alt="DEV.TO" />
  </a>
  <a href="https://instagram.com/patilmanas04" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</p>
