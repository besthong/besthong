                __   __    __       _______..___________.    _______    ______       __  .___________.
               |  | |  |  |  |     /       ||           |   |       \  /  __  \     |  | |           |
               |  | |  |  |  |    |   (----``---|  |----`   |  .--.  ||  |  |  |    |  | `---|  |----`
         .--.  |  | |  |  |  |     \   \        |  |        |  |  |  ||  |  |  |    |  |     |  |     
         |  `--'  | |  `--'  | .----)   |       |  |        |  '--'  ||  `--'  |    |  |     |  |     
          \______/   \______/  |_______/        |__|        |_______/  \______/     |__|     |__|    


         그냥 하다보면 될거같아

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
minsuk = Member("홍정훈", "Software engineer🧑🏽‍💻", ["Back-end🔭"], ["Java☕"], ["Python"]
           ["Python🌱", "Django", "FastAPI🛵"],
           ["Ubuntu🐺", "Github Actions♾️", "Postgresql🐘", "Docker🐋", "AWS EC2☁️"],
           ["Slack📑", "Notion", "Github project", "Git", "IntelliJ"],
           ["음악🎧", "책📖", "등산🏔️"])

introduce(minsuk)
```

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=besthong&layout=compact)

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
