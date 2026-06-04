<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Aryan%20Kumar%20Rai&fontSize=48&fontColor=fff&animation=twinkling&fontAlignY=38&desc=AI%20Engineer%20%E2%80%A2%20Builder%20%E2%80%A2%20Problem%20Solver&descAlignY=58&descSize=18"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aryankumarrai)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aryankumarrai)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/aryankumarrai)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aryansam1829@gmail.com)

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=6AD3F7&center=true&vCenter=true&width=650&lines=Building+AI+that+actually+ships+🚀;Enterprise+AI+%7C+AI+Automation+%7C+RAG;CS+%40+VIT+Bhopal+—+AI+%26+ML+Specialization;Back+on+the+DSA+grind+💡)](https://git.io/typing-svg)

</div>

---

## 👤 About Me

```python
aryan = {
    "education":   "B.Tech CS (AI & ML) @ VIT Bhopal  |  CGPA: 8.25  |  2024–2028",
    "location":    "India 🇮🇳",
    "focus":       ["Enterprise AI", "AI Automation", "RAG Pipelines", "Async Backend Systems"],
    "published":   ["IJIRT 2025", "IJFMR 2025"],
    "hackathons":  "10+ events | 1st Runner-Up @ Summer of Codefest '25",
    "dsa":         "Rebuilding daily C++ problem-solving — back in the grind 💪",
    "motto":       "Less tutorial. More production."
}
```

I build things that run in the real world — AI pipelines that classify leads in **< 3 seconds**, QR-authenticated medicine verification published in a journal, and voice-enabled chatbots with zero backend cost. If it's not shipping, it's just a side project.

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & Frameworks**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**AI / ML**

![Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=for-the-badge&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Pipelines-FF6F00?style=for-the-badge&logo=databricks&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-00BCD4?style=for-the-badge&logo=openai&logoColor=white)

**Cloud & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 Lead Automation System
`Python` `FastAPI` `Gemini AI` `n8n` `Celery` `Redis` `PostgreSQL`

An AI-powered lead processing pipeline with multi-intent classification and confidence scoring — processes each lead **end-to-end in < 3 seconds**.

- 5-node n8n workflow with idempotency (zero duplicate DB entries on webhook retries)
- Async endpoints via Celery + Redis returning task IDs in **< 50ms** with 3-attempt auto-retry
- Keyword-based fallback classification for graceful degradation when AI API is down

[→ GitHub](https://github.com/aryankumarrai) · [→ Demo](https://drive.google.com/file/d/1P2EhAt2KdkhKJZMQVUaX9uryMD7xisPX/view?usp=drivesdk)

</td>
<td width="50%" valign="top">

### 💊 PharmaKrypt
`React` `Vite` `Firebase` `Tailwind CSS`

End-to-end medicine authentication via cryptographic QR serialization and geofenced verification — validates in **< 2 seconds** using in-browser jsQR scanning.

- One-scan enforcement via Firestore atomic transactions (zero duplicate-scan exploits)
- Zero backend cost — fully serverless React + Firebase stack
- **Published in IJIRT (2025)**

[→ GitHub](https://github.com/aryankumarrai) · [→ Paper](https://ijirt.org/article?manuscript=196615) · [→ Live](https://www.pharmakrypt.app/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 Kryptonite — GenZ AI Chatbot
`Python` `Flask` `Google Gemini` `Web Speech API`

Decoupled full-stack voice chatbot — Flask API on Render + React on Vercel — with two-way hands-free voice conversation using browser-native Web Speech API. No external speech SDK.

- Zero database cost via client-side session storage
- Privacy-first: no user data retained between sessions

[→ GitHub](https://github.com/aryankumarrai) · [→ Live](https://kryptonite-bot.vercel.app/)

</td>
<td width="50%" valign="top">

### 📋 RubricAI
`AI` `Automated Evaluation`

AI-driven automated assignment evaluation system with structured rubric-based scoring — built to reduce manual grading overhead.

- **Published in IJFMR (2025)**

[→ Paper](https://www.ijfmr.com/papers/2025/5/56763.pdf)

</td>
</tr>
</table>

---

## 🏆 Achievements

| | |
|---|---|
| 🥈 | **1st Runner-Up** — Summer of Codefest '25 Hackathon @ VIT Bhopal |
| 🏅 | **Finalist in majority** of 10+ hackathons across 2024–2026 |
| 📝 | **Published** in IJIRT & IJFMR (2025) — AI and security systems research |
| 👨‍💻 | **Tech Team Lead** @ iCreate VITB — infrastructure for 300+ participants |

---

## 📊 GitHub Stats

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=aryankumarrai&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true"/>
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aryankumarrai&layout=compact&theme=tokyonight&hide_border=true"/>

<br/>

<img src="https://streak-stats.demolab.com?user=aryankumarrai&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D"/>

</div>

---

## 🧩 LeetCode Progress

<div align="center">

[![LeetCode Stats](https://leetcard.jacoblin.cool/aryankumarrai?theme=dark&font=Karma&ext=contest)](https://leetcode.com/u/aryankumarrai)

> 🎯 **Solving in C++. Back on the grind — building consistency one problem at a time.**

</div>

---

## 📬 Let's Connect

Got a cool project idea, want to collaborate, or just want to talk AI?

<div align="center">

**[📧 aryansam1829@gmail.com](mailto:aryansam1829@gmail.com)** &nbsp;·&nbsp; **[💼 LinkedIn](https://www.linkedin.com/in/aryankumarrai)** &nbsp;·&nbsp; **[🐙 GitHub](https://github.com/aryankumarrai)**

</div>

<br/>

<div align="center">

*"The best way to predict the future is to build it."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>

</div>
