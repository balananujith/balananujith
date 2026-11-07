<div align="center">

<img src="./assets/banner.svg" alt="Anujith Balan: I teach AI to watch, listen and read Malayalam videos" width="100%"/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=18&duration=2800&pause=900&color=C4B5FD&center=true&vCenter=true&width=760&height=50&lines=%24+booting+anujith.exe+...;%5B+OK+%5D+Python+loaded+%F0%9F%90%8D;%5B+OK+%5D+Curiosity+at+100%25+%E2%9A%A1;%5B+OK+%5D+Malayalam+AI+module+online+%F0%9F%8E%A5;Hi.+I+teach+machines+to+catch+sarcasm.+%F0%9F%99%8C" alt="boot sequence"/>

<br/>

<a href="mailto:balananujith@gmail.com"><img src="https://img.shields.io/badge/📧_Email-balananujith@gmail.com-7c3aed?style=for-the-badge&labelColor=1e1b4b"/></a>
<a href="https://linkedin.com/in/balananujith"><img src="https://img.shields.io/badge/LinkedIn-say_hi-7c3aed?style=for-the-badge&logo=linkedin&labelColor=1e1b4b"/></a>
<a href="https://github.com/balananujith"><img src="https://img.shields.io/github/followers/balananujith?style=for-the-badge&logo=github&color=7c3aed&labelColor=1e1b4b"/></a>

</div>

<img src="./assets/divider.svg" width="100%" alt=""/>

## 🎯 PICK YOUR PLAYER

Short on time? Open the one that sounds like you. 👇

<details>
<summary><b>🧑‍💼 I'm a recruiter / hiring manager</b></summary>

<br/>

**10-second version:**
- 🎓 M.Tech CSE student at Pondicherry University (2025 to 2027), B.Tech CSE from UCE Kariavattom (2024)
- 🐍 Python first, plus C++, C, Java, JavaScript
- 🤖 Hands-on with ML, deep learning (CNNs), NLP and multimodal AI
- 💼 ML Intern at iNeuron, HackerRank Software Engineer Intern certified
- 👑 Led student teams on two projects and shipped both
- 🥇 Medal + Best Performer certificate at the Smart India Hackathon internal round (team)
- 📬 Open to software and AI roles: [balananujith@gmail.com](mailto:balananujith@gmail.com)

</details>

<details>
<summary><b>🤝 I'm a collaborator / researcher</b></summary>

<br/>

I'm working on **multimodal hate and offensive content detection for Malayalam videos**, combining text, speech and visuals, with an **uncertainty-aware fusion** step that sends shaky predictions to humans.

Into low-resource language AI, video understanding or human-in-the-loop systems? Let's talk. 💬

</details>

<details>
<summary><b>🎓 I'm a student who wants to learn</b></summary>

<br/>

Start here:
1. 📊 Build something visual (my Algorithm Visualizer taught me more than any textbook)
2. 🎬 Make a small recommender app with Flask
3. 🧠 Then try a CNN on video frames

Ask me anything, I like explaining things with analogies. 🙌

</details>

<details>
<summary><b>🍔 Secret menu</b></summary>

<br/>

```bash
$ sudo hire anujith
[sudo] password for recruiter: ********
✔ Permission granted.
✔ Next step: email balananujith@gmail.com
```

</details>

<img src="./assets/divider.svg" width="100%" alt=""/>

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

<img src="./assets/divider.svg" width="100%" alt=""/>

## 🔥 BOSS FIGHT: MalHate-MM

> *Hate speech doesn't always shout. Sometimes it smiles and says the opposite of what it means.*

Most detectors only **read** text. But a video speaks in **three ways at once**: words, voice, and what's on screen. Sarcasm hides in the gap between them.

<div align="center">

<img src="./assets/fusion.svg" alt="MalHate-MM pipeline: text, speech and visuals go into a fusion model that either auto-labels or sends the clip to human review" width="100%"/>

</div>

**Think of it like a courtroom ⚖️**
Three witnesses (text, speech, visuals) give statements. The judge (the fusion model) weighs them. If they disagree and the judge isn't sure, the case goes to a human instead of a guess.

<details>
<summary><b>🕵️ Click to try: can YOU spot the sarcasm?</b></summary>

<br/>

Someone posts a video with the caption **"Wow, amazing service 👏"**

Their face is flat. Their voice is dripping with annoyance. The clip shows a 3-hour queue.

- 📝 **Text says:** positive ✅
- 🎙️ **Voice says:** angry 😒
- 👁️ **Video says:** nope 🙃

A text-only model says "nice review!" 🤦
A multimodal model notices the three signals disagree.

**That mismatch is exactly what MalHate-MM is built to find, in Malayalam.**

</details>

**What I'm building:**
- 🎬 A **labelled Malayalam video dataset**
- 🧠 An **uncertainty-aware fusion framework**
- 🙋 A **human-in-the-loop** step for low-confidence clips

<img src="./assets/divider.svg" width="100%" alt=""/>

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

<img src="./assets/divider.svg" width="100%" alt=""/>

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

🧠 **Core stuff:** DSA · OOP · Operating Systems · Computer Networks · DBMS · SDLC · MVC

</div>

<img src="./assets/divider.svg" width="100%" alt=""/>

## 📜 PATCH NOTES

```diff
# anujith.changelog

+ v2020  Started B.Tech CSE at University College of Engineering, Kariavattom
+ v2023  Data Science workshop at NIT Calicut
+ v2023  ML Intern at iNeuron (Aug to Nov): shipped a Book Recommendation System
+ v2023  Smart India Hackathon internal round: medal + Best Performer (team)
+ v2024  HackerRank Software Engineer Intern certification (June)
+ v2024  Graduated B.Tech, shipped Video Truth Sentinel as team leader
+ v2025  Started M.Tech CSE at Pondicherry University
+ v2025  Launched MalHate-MM, still in active development

- known issue: AI models that miss sarcasm
! patch in progress: multimodal fusion + human review
```

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

<img src="./assets/divider.svg" width="100%" alt=""/>

## 🏆 TROPHY SHELF

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=balananujith&theme=darkhub&no-frame=true&no-bg=true&margin-w=12&row=1&column=6"/>

<br/>

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=balananujith&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d0d1a&title_color=a78bfa&icon_color=7c3aed&text_color=e2e8f0&ring_color=a78bfa"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=balananujith&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0d0d1a&title_color=a78bfa&text_color=e2e8f0"/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=balananujith&theme=midnight-purple&hide_border=true&background=0d0d1a&stroke=6d28d9&ring=a78bfa&fire=f59e0b&currStreakLabel=a78bfa&sideLabels=a78bfa&dates=6b7280"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=balananujith&bg_color=0d0d1a&color=a78bfa&line=6d28d9&point=f59e0b&hide_border=true&area=true&area_color=6d28d9"/>

</div>

<img src="./assets/divider.svg" width="100%" alt=""/>

## 📡 SIGNAL ME

I'm looking for software and AI roles where I can ship reliable, well-tested work and keep learning in a fast team. If you've got a problem, a collab idea, or just want to nerd out on multimodal AI, ping me. 👋

<div align="center">

<a href="mailto:balananujith@gmail.com"><img src="https://img.shields.io/badge/📧_Email_me-7c3aed?style=for-the-badge&labelColor=1e1b4b"/></a>
<a href="https://linkedin.com/in/balananujith"><img src="https://img.shields.io/badge/LinkedIn-connect-7c3aed?style=for-the-badge&logo=linkedin&labelColor=1e1b4b"/></a>

<br/><br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=15&pause=1500&color=A78BFA&center=true&vCenter=true&width=600&lines=When+the+AI+isn't+sure%2C+ask+a+human.;Thanks+for+scrolling+all+the+way+down.+%F0%9F%92%9C" alt="footer"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4c1d95,50:6d28d9,100:a78bfa&height=130&section=footer&animation=twinkling"/>

</div>
