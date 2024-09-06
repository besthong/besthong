

                    __   __    __       _______..___________.    _______    ______       __  .___________.
                   |  | |  |  |  |     /       ||           |   |       \  /  __  \     |  | |           |
                   |  | |  |  |  |    |   (----``---|  |----`   |  .--.  ||  |  |  |    |  | `---|  |----`
             .--.  |  | |  |  |  |     \   \        |  |        |  |  |  ||  |  |  |    |  |     |  |     
             |  `--'  | |  `--'  | .----)   |       |  |        |  '--'  ||  `--'  |    |  |     |  |     
              \______/   \______/  |_______/        |__|        |_______/  \______/     |__|     |__|    
                             
                                안녕하세요. 고민 할 시간도 중요하지만 일단 해보는게 더 중요한 홍정훈 입니다.

<p align="center">
  <a href="https://hongjunghoon.com">
    <img src="https://img.shields.io/badge/TechBlog-F7DF1E?style=for-the-badge&&logoColor=white">
  </a>
</p>

# About me👇🏻

```python
from dataclasses import dataclass

@dataclass
class Member:
name: str
job: str
development_fields: list
languages: list
backend_skills: list
devops_skills: list
collaboration_tools: list
interests: list

def introduce(member: Member):
print(f"👋 {member.name}, {member.job}\n"
 f"🔭 Development: {', '.join(member.development_fields)} | "
 f"☕ Languages: {', '.join(member.languages)} | "
 f"🔧 Backend: {', '.join(member.backend_skills)} | "
 f"♾️ DevOps: {', '.join(member.devops_skills)} | "
 f"📑 Tools: {', '.join(member.collaboration_tools)} | "
 f"🎯 Interests: {', '.join(member.interests)}")

if __name__ == "__main__":
junghoon = Member("홍정훈", "Software engineer🧑🏽‍💻", ["Back-end🔭"], ["Java☕"], ["Python"]
           ["Python🌱", "Django", "FastAPI🛵"],
           ["Ubuntu🐺", "Github Actions♾️", "Postgresql🐘", "Docker🐋", "AWS EC2☁️"],
           ["Slack📑", "Notion", "Github project", "Git", "IntelliJ"],
           ["음악🎧", "책📖", "등산🏔️"])

introduce(junghoon)
```

<!--
**besthong/besthong** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
