<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:1e1b4b,40:4c1d95,100:a78bfa&height=300&section=header&text=ANUJITH%20BALAN&fontSize=68&fontColor=ffffff&fontAlignY=38&desc=%F0%9F%8E%A5%20watch%20%E2%80%A2%20%F0%9F%8E%99%EF%B8%8F%20listen%20%E2%80%A2%20%F0%9F%93%9D%20read%20%E2%80%A2%20%F0%9F%A7%A0%20understand&descSize=20&descAlignY=62&animation=twinkling" />

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=18&duration=2800&pause=900&color=C4B5FD&center=true&vCenter=true&width=760&height=50&lines=%24+booting+anujith.exe+...;%5B+OK+%5D+Python+loaded+%F0%9F%90%8D;%5B+OK+%5D+Curiosity+at+100%25+%E2%9A%A1;%5B+OK+%5D+Malayalam+AI+module+online+%F0%9F%8E%A5;Hi.+I+teach+machines+to+catch+sarcasm.+%F0%9F%99%8C" alt="boot sequence"/>

<br/><br/>

<a href="mailto:balananujith@gmail.com"><img src="https://img.shields.io/badge/📧_Email-balananujith@gmail.com-7c3aed?style=for-the-badge&labelColor=1e1b4b"/></a>
<a href="https://linkedin.com/in/balananujith"><img src="https://img.shields.io/badge/LinkedIn-say_hi-7c3aed?style=for-the-badge&logo=linkedin&labelColor=1e1b4b"/></a>
<a href="https://github.com/balananujith"><img src="https://img.shields.io/github/followers/balananujith?style=for-the-badge&logo=github&color=7c3aed&labelColor=1e1b4b"/></a>

</div>

<br/>

<div align="center">

### ⚡ TL;DR

**M.Tech CSE @ Pondicherry University** 🎓 · **Kerala born** 🌴 · **Python first** 🐍
**Building:** an AI that watches Malayalam videos and knows when someone is *not* being nice 😏

</div>

---

## 🎮 CHARACTER SHEET

<div align="center">

| 🧙 CLASS | 🌍 HOME BASE | 🗣️ LANGUAGES UNLOCKED |
|:---:|:---:|:---:|
| **AI Builder** | Kerala, India 🇮🇳 | English · Malayalam · Hindi · Tamil *(beginner)* |

</div>

```text
╔════════════════════════════════════════════════════╗
║  ANUJITH BALAN                      LVL: M.Tech 🎓 ║
╠════════════════════════════════════════════════════╣
║  🐍 Python ............ ▰▰▰▰▰▰▰▰▰▰  MAIN WEAPON    ║
║  🧠 ML / Deep Learning  ▰▰▰▰▰▰▰▰▱▱                 ║
║  👁️ Video + CNN ....... ▰▰▰▰▰▰▰▰▱▱                 ║
║  🗣️ NLP ............... ▰▰▰▰▰▰▰▱▱▱                 ║
║  ⚙️ C++ / Java / JS ... ▰▰▰▰▰▰▱▱▱▱                 ║
║  🌐 Flask / Django .... ▰▰▰▰▰▰▱▱▱▱                 ║
║  ☕ Dark mode ......... ▰▰▰▰▰▰▰▰▰▰  (light = bugs 🐛)║
╠════════════════════════════════════════════════════╣
║  QUEST LOG: MalHate-MM 🎥          STATUS: ACTIVE  ║
╚════════════════════════════════════════════════════╝
```

---

## 🔥 BOSS FIGHT: MalHate-MM

> *Hate speech doesn't always shout. Sometimes it smiles and says the opposite of what it means.*

Most detectors only **read** text. But a video says things in **three ways at once**: words, voice, and what's on screen. Sarcasm hides in the gap between them.

So my system uses all three. 👇

```mermaid
flowchart LR
    A(["🎥 Malayalam video"]) --> B["📝 Text<br/>what is said"]
    A --> C["🎙️ Speech<br/>how it's said"]
    A --> D["👁️ Visuals<br/>what you see"]
    B --> E{{"🧠 Uncertainty-aware<br/>fusion"}}
    C --> E
    D --> E
    E -->|"😎 confident"| F["✅ Auto label"]
    E -->|"🤔 not sure"| G["🙋 Human review"]
    style A fill:#4c1d95,color:#fff,stroke:#a78bfa
    style E fill:#6d28d9,color:#fff,stroke:#c4b5fd
    style F fill:#065f46,color:#fff,stroke:#34d399
    style G fill:#92400e,color:#fff,stroke:#fbbf24
```

**Think of it like a courtroom ⚖️**
Three witnesses (text, speech, visuals) give statements. The judge (fusion model) weighs them. If they disagree and the judge isn't sure, the case goes to a human instead of a guess.

<details>
<summary><b>🕵️ Click to try: can YOU spot the sarcasm?</b></summary>

<br/>

Someone posts a video with the caption **"Wow, amazing service 👏"**

Their face is flat. Their voice is dripping with annoyance. The clip shows a 3-hour queue.

- 📝 **Text says:** positive ✅
- 🎙️ **Voice says:** angry 😒
- 👁️ **Video says:** nope 🙃

A text-only model says "nice review!" 🤦
A multimodal model catches that the three signals disagree.

**That mismatch is exactly what MalHate-MM is built to find, in Malayalam.**

</details>

**What I'm building:**
- 🎬 A **labelled Malayalam video dataset**
- 🧠 An **uncertainty-aware fusion framework**
- 🙋 A **human-in-the-loop** step for low-confidence clips

---

## 🗺️ SIDE QUESTS

<table>
<tr>
<td width="50%" valign="top">

### 🕵️ Video Truth Sentinel
`MISSION: catch the fakes` · ✅ **COMPLETED**

CNN system that checks videos **frame by frame** for fake or manipulated content.
I led the team: split tasks, tracked progress, shipped it end to end.

`CNN` `Deep Learning` `Video Analysis`
**Role:** 👑 Team Leader · B.Tech Major

</td>
<td width="50%" valign="top">

### 📺 YouTube Video Summarizer
`MISSION: skip the 40 min intro` · ✅ **COMPLETED**

Paste a video, get a short summary. Grabs the transcript, lets Gemini do the squeezing.

`Python` `Gemini API` `YouTube Transcript API`
**Type:** 🤖 GenAI tool

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Algorithm Visualizer
`MISSION: make sorting watchable` · ✅ **COMPLETED**

Desktop app that shows every step of sorting and searching. Change array size, pause, resume, reset.

`Python` `Tkinter`
**Role:** 👑 Team Leader · B.Tech Mini

</td>
<td width="50%" valign="top">

### 🎬 Movie Recommender
`MISSION: end "what do we watch?"` · ✅ **COMPLETED**

Tell it what you like, it picks what's next.

`Python` `Flask` `HTML` `CSS` `JS`
**Type:** 🌐 Web app

</td>
</tr>
</table>

---

## 🧰 INVENTORY

<div align="center">

![Python](https://img.shields.io/badge/Python-1e1b4b?style=for-the-badge&logo=python&logoColor=c4b5fd)
![C++](https://img.shields.io/badge/C++-1e1b4b?style=for-the-badge&logo=cplusplus&logoColor=c4b5fd)
![C](https://img.shields.io/badge/C-1e1b4b?style=for-the-badge&logo=c&logoColor=c4b5fd)
![Java](https://img.shields.io/badge/Java-1e1b4b?style=for-the-badge&logo=openjdk&logoColor=c4b5fd)
![JavaScript](https://img.shields.io/badge/JavaScript-1e1b4b?style=for-the-badge&logo=javascript&logoColor=c4b5fd)

![TensorFlow](https://img.shields.io/badge/CNN_Deep_Learning-1e1b4b?style=for-the-badge&logo=tensorflow&logoColor=c4b5fd)
![scikit-learn](https://img.shields.io/badge/Machine_Learning-1e1b4b?style=for-the-badge&logo=scikit-learn&logoColor=c4b5fd)
![NLP](https://img.shields.io/badge/NLP-1e1b4b?style=for-the-badge&logoColor=c4b5fd)
![Multimodal](https://img.shields.io/badge/Multimodal_AI-1e1b4b?style=for-the-badge&logoColor=c4b5fd)
![OCR](https://img.shields.io/badge/OCR-1e1b4b?style=for-the-badge&logoColor=c4b5fd)
![Gemini](https://img.shields.io/badge/Gemini_API-1e1b4b?style=for-the-badge&logo=googlegemini&logoColor=c4b5fd)

![Flask](https://img.shields.io/badge/Flask-1e1b4b?style=for-the-badge&logo=flask&logoColor=c4b5fd)
![Django](https://img.shields.io/badge/Django-1e1b4b?style=for-the-badge&logo=django&logoColor=c4b5fd)
![HTML](https://img.shields.io/badge/HTML-1e1b4b?style=for-the-badge&logo=html5&logoColor=c4b5fd)
![CSS](https://img.shields.io/badge/CSS-1e1b4b?style=for-the-badge&logo=css3&logoColor=c4b5fd)
![Tkinter](https://img.shields.io/badge/Tkinter-1e1b4b?style=for-the-badge&logoColor=c4b5fd)

![MySQL](https://img.shields.io/badge/MySQL-1e1b4b?style=for-the-badge&logo=mysql&logoColor=c4b5fd)
![MongoDB](https://img.shields.io/badge/MongoDB-1e1b4b?style=for-the-badge&logo=mongodb&logoColor=c4b5fd)
![Git](https://img.shields.io/badge/Git-1e1b4b?style=for-the-badge&logo=git&logoColor=c4b5fd)
![GitHub](https://img.shields.io/badge/GitHub-1e1b4b?style=for-the-badge&logo=github&logoColor=c4b5fd)
![VS Code](https://img.shields.io/badge/VS_Code-1e1b4b?style=for-the-badge&logo=visualstudiocode&logoColor=c4b5fd)

</div>

<div align="center">

🧠 **Core stuff:** DSA · OOP · Operating Systems · Computer Networks · DBMS · SDLC · MVC

</div>

---

## 🛤️ THE JOURNEY SO FAR

```mermaid
flowchart LR
    A["🎓 2020<br/>B.Tech CSE<br/>UCE Kariavattom"] --> B["🥇 SIH<br/>Medal + Best<br/>Performer"]
    B --> C["💼 Aug–Nov 2023<br/>ML Intern<br/>iNeuron"]
    C --> D["🏅 Jun 2024<br/>HackerRank<br/>SWE Intern Cert"]
    D --> E["🎓 2025<br/>M.Tech CSE<br/>Pondicherry Univ"]
    E --> F["🎥 Now<br/>MalHate-MM"]
    style A fill:#312e81,color:#fff,stroke:#a78bfa
    style B fill:#312e81,color:#fff,stroke:#a78bfa
    style C fill:#4c1d95,color:#fff,stroke:#a78bfa
    style D fill:#4c1d95,color:#fff,stroke:#a78bfa
    style E fill:#6d28d9,color:#fff,stroke:#c4b5fd
    style F fill:#7c3aed,color:#fff,stroke:#ddd6fe
```

<details>
<summary><b>💼 What I did at iNeuron</b></summary>

<br/>

Machine Learning Intern (Aug – Nov 2023). Built a **Book Recommendation System** using machine learning algorithms.

</details>

<details>
<summary><b>🛠️ Workshops I've leveled up in</b></summary>

<br/>

- 🔍 Cyber Forensics (NSS UCEK with CDAC)
- 📊 Data Science (NIT Calicut, 2023)
- ☁️ Cloud Computing (Mar Athanasius College of Engineering)
- ⚛️ Web Development with React (Alchemy IEDC, College of Engineering Attingal)

</details>

<details>
<summary><b>🤝 Beyond code</b></summary>

<br/>

Member of the **National Service Scheme (NSS)**, doing community service activities.

</details>

---

## 🏆 TROPHY SHELF

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=balananujith&theme=darkhub&no-frame=true&no-bg=true&margin-w=12&row=1&column=6"/>

<br/>

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=balananujith&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d0d1a&title_color=a78bfa&icon_color=7c3aed&text_color=e2e8f0&ring_color=a78bfa"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=balananujith&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0d0d1a&title_color=a78bfa&text_color=e2e8f0"/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=balananujith&theme=midnight-purple&hide_border=true&background=0d0d1a&stroke=6d28d9&ring=a78bfa&fire=f59e0b&currStreakLabel=a78bfa&sideLabels=a78bfa&dates=6b7280"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=balananujith&bg_color=0d0d1a&color=a78bfa&line=6d28d9&point=f59e0b&hide_border=true&area=true&area_color=6d28d9"/>

</div>

---

## 📡 SIGNAL ME

I'm looking for software and AI roles where I can ship reliable, well-tested work and keep learning in a fast team. If you've got a problem, a collab idea, or just want to nerd out on multimodal AI, ping me. 👋

<div align="center">

<a href="mailto:balananujith@gmail.com"><img src="https://img.shields.io/badge/📧_Email_me-7c3aed?style=for-the-badge&labelColor=1e1b4b"/></a>
<a href="https://linkedin.com/in/balananujith"><img src="https://img.shields.io/badge/LinkedIn-connect-7c3aed?style=for-the-badge&logo=linkedin&labelColor=1e1b4b"/></a>

<br/><br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=15&pause=1500&color=A78BFA&center=true&vCenter=true&width=600&lines=When+the+AI+isn't+sure%2C+ask+a+human.;Thanks+for+scrolling+all+the+way+down.+%F0%9F%92%9C" alt="footer"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4c1d95,50:6d28d9,100:a78bfa&height=130&section=footer&animation=twinkling"/>

</div>
