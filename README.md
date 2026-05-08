<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:6d28d9,50:7c3aed,100:4c1d95&height=250&section=header&text=ANUJITH%20BALAN&fontSize=72&fontColor=ffffff&fontAlignY=45&desc=Federated%20Learning%20Engineer%20%E2%80%A2%20Full%20Stack%20Developer%20%E2%80%A2%20Privacy%20Advocate&descSize=15&descAlignY=68&animation=fadeIn&stroke=a78bfa&strokeWidth=2" />

</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=16&pause=1200&color=A78BFA&center=true&vCenter=true&multiline=false&width=700&lines=🔐+%22The+model+trains+on+your+data.+Your+data+never+leaves.%22;⚡+Teaching+AI+to+learn+without+spying+since+day+one;🌐+Decentralize+the+model%2C+not+just+the+data;🛡️+Privacy-Preserving+AI+%7C+Zero+data+leaves+your+device;🚀+Building+the+future+where+AI+respects+humans" alt="Typing Animation"/>

</div>

<br/>

<div align="center">

[![Visits](https://visitor-badge.laobi.icu/badge?page_id=balananujith.visitor-badge&color=6d28d9&labelColor=1e1b4b&label=profile%20visits)](https://github.com/balananujith)&nbsp;&nbsp;
[![GitHub followers](https://img.shields.io/github/followers/balananujith?label=followers&style=flat&color=a78bfa&labelColor=1e1b4b&logo=github)](https://github.com/balananujith)&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-a78bfa?style=flat&logo=linkedin&labelColor=1e1b4b)](https://linkedin.com/in/balananujith)&nbsp;&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-reach%20me-a78bfa?style=flat&logo=gmail&labelColor=1e1b4b)](mailto:balananujith@gmail.com)

</div>

---

<br/>

## 🧠 The Manifesto

<table>
<tr>
<td width="55%">

### Why I build with Federated Learning

In a world where every app wants your data and every server is a breach away from disaster — **Federated Learning is the answer nobody expected.**

It flips the entire AI pipeline on its head:

- ❌ Old way: *Send your diary to a stranger. Ask them to read it. Trust them not to.*
- ✅ FL way: *The stranger comes to your house. Learns what they need. Leaves. Remembers the lesson, not your secrets.*

I'm obsessed with building systems where **intelligence and privacy coexist** — not as a tradeoff, but as a design principle.

> *"What if we could make AI smarter without making humans more vulnerable?"*
>
> — That question keeps me up at night. 🌙

</td>
<td width="45%">

```
╔═══════════════════════════════╗
║    TRADITIONAL AI PIPELINE    ║
╠═══════════════════════════════╣
║  📱 User Data                 ║
║       │                       ║
║       ▼                       ║
║  ☁️  Central Server           ║
║  (your data lives here now)   ║
║       │                       ║
║       ▼                       ║
║  🤖 Model (trained on YOU)    ║
║                               ║
║  Trust level: "trust me bro" ║
╚═══════════════════════════════╝

╔═══════════════════════════════╗
║    FEDERATED AI PIPELINE      ║
╠═══════════════════════════════╣
║  📱 Your Device               ║
║  (data NEVER leaves) 🔒       ║
║       │                       ║
║       │  only Δweights        ║
║       ▼                       ║
║  ☁️  Aggregator               ║
║  (sees math, not memories)    ║
║       │                       ║
║       ▼                       ║
║  🤖 Smarter Global Model ✅   ║
╚═══════════════════════════════╝
```

</td>
</tr>
</table>

---

<br/>

## ⚙️ How Federated Learning Actually Works

```
                        ┌─────────────────────────────────────────────────────┐
                        │              FEDERATED LEARNING ROUND r              │
                        └─────────────────────────────────────────────────────┘

  ROUND START
  ┌──────────┐
  │ 🌐 Global │ ──── broadcasts Wᵍ ─────────────────────────────────────────┐
  │  Model   │                                                              │
  └──────────┘                                                              │
       ▲                                                                    │
       │                      ┌─────────────────────────────────────────────▼──┐
       │                      │                CLIENT DEVICES                   │
       │                      │                                                │
       │              ┌───────┴──────┐  ┌──────────────┐  ┌───────────────┐   │
       │              │  📱 Device A  │  │  📱 Device B  │  │  📱 Device C  │   │
       │              │              │  │              │  │               │   │
       │              │ Local Data:  │  │ Local Data:  │  │ Local Data:   │   │
       │              │ 🔒 private   │  │ 🔒 private   │  │ 🔒 private    │   │
       │              │              │  │              │  │               │   │
       │              │  Trains on   │  │  Trains on   │  │  Trains on    │   │
       │              │  local data  │  │  local data  │  │  local data   │   │
       │              │  ε-DP noise  │  │  ε-DP noise  │  │  ε-DP noise   │   │
       │              │  injected 🛡️ │  │  injected 🛡️ │  │  injected 🛡️  │   │
       │              └──────┬───────┘  └──────┬───────┘  └───────┬───────┘   │
       │                     │                 │                   │           │
       │                     └────────┬────────┘                   │           │
       │                              │◄──────────────────────────┘           │
       │                   sends ΔW (gradients only)                          │
       │                   Raw data: NEVER transmitted ✅                      │
       │                              │                                        │
       │                     ┌────────▼────────┐                              │
       └─────────────────────│  🧠 Aggregator  │◄─────────────────────────────┘
                             │   FedAvg algo   │
                             │  Wᵍ⁺¹ = ΣwᵢΔWᵢ │
                             └─────────────────┘

  RESULT: Global model improves each round. Zero raw data ever centralized. 🎉
```

---

<br/>

## 🔬 FL Research Areas I Actively Explore

<table>
<tr>
<td align="center" width="25%">

### 🔀 Non-IID Data
*"When every device lives in a different world"*

Devices have **heterogeneous distributions**. A keyboard model trained on a doctor's phone learns medical jargon. On a teenager's phone — emojis. Making FL converge across these worlds is an open research problem.

**My approach:** FedProx regularization + personalized local layers

</td>
<td align="center" width="25%">

### 🛡️ Differential Privacy
*"Adding controlled noise to protect individuals"*

Even gradients can leak secrets. With **ε-DP**, we inject calibrated Gaussian noise so that no single user's data can be reverse-engineered — even by the server itself.

**My approach:** Rényi DP accounting + adaptive clipping

</td>
<td align="center" width="25%">

### ⚔️ Byzantine Robustness
*"When one bad actor tries to poison the whole model"*

A malicious client can send crafted gradients to manipulate the global model. **Robust aggregation** uses statistical methods to detect and reject outliers.

**My approach:** Krum + coordinate-wise median

</td>
<td align="center" width="25%">

### 📡 Communication Efficiency
*"Gradients are big. Networks are slow."*

Transmitting full model updates every round is expensive. **Gradient compression** — quantization, sparsification, sketching — cuts bandwidth by 100x without hurting convergence.

**My approach:** Top-k sparsification + error feedback

</td>
</tr>
</table>

---

<br/>

## 💻 Who I Am, In Code

```python
#!/usr/bin/env python3
# ─────────────────────────────────────────────────
#  ANUJITH BALAN  ·  Kerala, India 🇮🇳
# ─────────────────────────────────────────────────

class AnujithBalan:
    """
    Software Developer · FL Researcher · Problem Solver

    Core belief: Intelligence should not cost privacy.
    """

    name       : str  = "Anujith Balan"
    location   : str  = "Kerala, India 🇮🇳"
    available  : bool = True   # open to collaborations!

    research_focus = [
        "Federated Learning",
        "Privacy-Preserving ML",
        "Secure Aggregation Protocols",
        "Differential Privacy",
    ]

    current_stack = {
        "frontend"  : ["React", "Next.js", "TypeScript", "TailwindCSS"],
        "backend"   : ["Node.js", "Express", "Django", "Flask"],
        "ml"        : ["PyTorch", "TensorFlow", "scikit-learn", "OpenCV"],
        "databases" : ["MongoDB", "Firebase", "MySQL", "SQLite"],
        "infra"     : ["Docker", "AWS", "Linux", "Git"],
    }

    learning_now = ["Docker 🐳", "Supabase ⚡", "AWS ☁️"]

    @staticmethod
    def philosophy() -> str:
        return """
        The old model: ship user data to a server. Cross fingers. 🤞
        My model:      ship the AI to the user's data instead.    🚀

        Because 'trust me bro, it's secure' was never
        a real cybersecurity strategy. 💀
        """

    @staticmethod
    def fun_fact() -> str:
        return "Why do programmers prefer dark mode? Light attracts bugs! 🐛"

    def contact(self) -> dict[str, str]:
        return {
            "email"   : "balananujith@gmail.com",
            "github"  : "github.com/balananujith",
            "linkedin": "linkedin.com/in/balananujith",
        }


if __name__ == "__main__":
    me = AnujithBalan()
    print(me.philosophy())
    # → Let's build privacy-respecting AI together.
```

---

<br/>

## ⚒️ Arsenal

<div align="center">

### 🤖 ML · AI · Federated Learning
![Python](https://img.shields.io/badge/Python-20232A?style=for-the-badge&logo=python&logoColor=a78bfa)
![PyTorch](https://img.shields.io/badge/PyTorch-20232A?style=for-the-badge&logo=pytorch&logoColor=a78bfa)
![TensorFlow](https://img.shields.io/badge/TensorFlow-20232A?style=for-the-badge&logo=tensorflow&logoColor=a78bfa)
![scikit-learn](https://img.shields.io/badge/scikit--learn-20232A?style=for-the-badge&logo=scikit-learn&logoColor=a78bfa)
![OpenCV](https://img.shields.io/badge/OpenCV-20232A?style=for-the-badge&logo=opencv&logoColor=a78bfa)
![Anaconda](https://img.shields.io/badge/Anaconda-20232A?style=for-the-badge&logo=anaconda&logoColor=a78bfa)

### 🌐 Frontend · UI
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=a78bfa)
![Next.js](https://img.shields.io/badge/Next.js-20232A?style=for-the-badge&logo=next.js&logoColor=a78bfa)
![TypeScript](https://img.shields.io/badge/TypeScript-20232A?style=for-the-badge&logo=typescript&logoColor=a78bfa)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-20232A?style=for-the-badge&logo=tailwind-css&logoColor=a78bfa)
![Flutter](https://img.shields.io/badge/Flutter-20232A?style=for-the-badge&logo=flutter&logoColor=a78bfa)
![MUI](https://img.shields.io/badge/MUI-20232A?style=for-the-badge&logo=mui&logoColor=a78bfa)

### ⚙️ Backend · Databases
![Node.js](https://img.shields.io/badge/Node.js-20232A?style=for-the-badge&logo=node.js&logoColor=a78bfa)
![Express](https://img.shields.io/badge/Express-20232A?style=for-the-badge&logo=express&logoColor=a78bfa)
![Django](https://img.shields.io/badge/Django-20232A?style=for-the-badge&logo=django&logoColor=a78bfa)
![Flask](https://img.shields.io/badge/Flask-20232A?style=for-the-badge&logo=flask&logoColor=a78bfa)
![Firebase](https://img.shields.io/badge/Firebase-20232A?style=for-the-badge&logo=firebase&logoColor=a78bfa)
![MongoDB](https://img.shields.io/badge/MongoDB-20232A?style=for-the-badge&logo=mongodb&logoColor=a78bfa)
![MySQL](https://img.shields.io/badge/MySQL-20232A?style=for-the-badge&logo=mysql&logoColor=a78bfa)
![Spring](https://img.shields.io/badge/Spring-20232A?style=for-the-badge&logo=spring&logoColor=a78bfa)

### 🐳 DevOps · Cloud
![Docker](https://img.shields.io/badge/Docker-20232A?style=for-the-badge&logo=docker&logoColor=a78bfa)
![AWS](https://img.shields.io/badge/AWS-20232A?style=for-the-badge&logo=amazon-aws&logoColor=a78bfa)
![Linux](https://img.shields.io/badge/Linux-20232A?style=for-the-badge&logo=linux&logoColor=a78bfa)
![Git](https://img.shields.io/badge/Git-20232A?style=for-the-badge&logo=git&logoColor=a78bfa)
![GitHub](https://img.shields.io/badge/GitHub-20232A?style=for-the-badge&logo=github&logoColor=a78bfa)

</div>

---

<br/>

## 📊 GitHub In Numbers

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=balananujith&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d0d1a&title_color=a78bfa&icon_color=7c3aed&text_color=e2e8f0&ring_color=a78bfa"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=balananujith&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0d0d1a&title_color=a78bfa&text_color=e2e8f0"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=balananujith&theme=midnight-purple&hide_border=true&background=0d0d1a&stroke=6d28d9&ring=a78bfa&fire=f59e0b&currStreakLabel=a78bfa&sideLabels=a78bfa&dates=6b7280"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=balananujith&bg_color=0d0d1a&color=a78bfa&line=6d28d9&point=f59e0b&hide_border=true&area=true&area_color=6d28d9"/>

</div>

---

<br/>

## 🏥 Real-World FL Impact: Why This Matters Beyond Academia

<table>
<tr>
<th>🏥 Healthcare</th>
<th>📱 Mobile Keyboards</th>
<th>🏦 Finance</th>
<th>🚗 Autonomous Cars</th>
</tr>
<tr>
<td>

Hospitals collaboratively train cancer-detection models **without sharing a single patient record**.

Each hospital trains locally. Shares only weight updates. The global model becomes as good as if it had seen all data centrally.

**Patient privacy: 100% intact ✅**

</td>
<td>

Your phone's keyboard predicts your next word by training **on-device only**.

GBoard was one of the first FL deployments at scale — millions of phones, zero user messages sent to Google's servers.

**Your texts stay yours ✅**

</td>
<td>

Banks detect fraud patterns across institutions **without revealing transaction data** to competitors or regulators.

A model trained on federated data across 10 banks is far more robust than any single bank's model.

**Financial data stays siloed ✅**

</td>
<td>

Cars share learned driving patterns — road anomalies, edge cases, rare events — **without uploading video footage** of you driving.

Each car improves the fleet. The fleet improves each car. Nobody stores your commute.

**Location data stays local ✅**

</td>
</tr>
</table>

---

<br/>

## 📬 Let's Build Something Private & Powerful

<div align="center">

```
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│   Got an idea that needs privacy-preserving AI?              │
│   Building something where data sensitivity matters?         │
│   Just want to geek out about differential privacy?          │
│                                                              │
│   → Hit me up. I'm always down to collaborate. 🤝            │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

<br/>

[![Email](https://img.shields.io/badge/📧%20balananujith@gmail.com-1e1b4b?style=for-the-badge&logoColor=white)](mailto:balananujith@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/🔗%20LinkedIn-1e1b4b?style=for-the-badge)](https://linkedin.com/in/balananujith)
&nbsp;
[![GitHub Issues](https://img.shields.io/badge/💬%20Open%20an%20Issue-1e1b4b?style=for-the-badge)](https://github.com/balananujith/balananujith/issues)

<br/>

*"Ask me about Node.js · React · Firebase · Federated Learning · Privacy ML"*

</div>

---

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4c1d95,50:6d28d9,100:7c3aed&height=130&section=footer&text=Privacy%20is%20not%20a%20feature.%20It%27s%20a%20right.&fontSize=18&fontColor=e9d5ff&fontAlignY=65&animation=twinkling"/>

</div>
