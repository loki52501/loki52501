<div align="center">

<!-- Animated name banner -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&duration=3500&pause=1200&color=00D4FF&center=true&vCenter=true&repeat=true&width=900&height=65&lines=Lokesh+Srinivasaperumal;AI+Engineer+%7C+LLM+Evaluation+%26+Safety;AI+Reliability+%26+Inference+Systems;Applied+ML+%7C+Threat+Detection+%7C+Cloud" alt="Typing SVG" />
</a>

<br/>

<!-- Social badges -->
<a href="https://linkedin.com/in/lkslokesh">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://lkslokesh.com">
  <img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=firefox&logoColor=00D4FF"/>
</a>
<a href="mailto:lokeshlks01@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/loki52501">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=loki52501&style=flat-square&color=00D4FF&label=PROFILE+VIEWS" alt="Profile Views"/>

</div>

---

<!-- Animated divider -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## ⚡ `whoami`

```python
class Lokesh:
    name       = "Lokesh Srinivasaperumal"
    education  = ["M.S. Cybersecurity @ Penn State (GPA 3.7, May 2026)",
                  "Integrated M.S. IT @ Anna University (GPA 3.3)"]
    roles      = ["AI Engineer", "LLM Evaluation Researcher",
                  "AI Reliability Engineer", "Applied ML Engineer"]
    focus      = ["LLM faithfulness & sycophancy evaluation",
                  "Adversarial robustness & alignment empirics",
                  "AI-powered threat detection & IDS",
                  "Inference systems & cloud-native ML pipelines"]
    certs      = ["Cisco CCNA", "CompTIA Security+"]
    currently  = "Hunting for roles where AI safety meets production systems"
    fun_fact   = "Daily driving Arch Linux — btw 🐧"
```

> *"How do you know when a system's stated behavior reflects its actual internal state?"*  
> — The question driving my research across LLM alignment, IDS, and distributed systems.

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🧠 Research & AI Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔍 LLM Sycophancy Evaluator
**`Llama-3.2-3B · PyTorch · Streamlit`**

Built a paired-prompt evaluation framework measuring **3 sycophancy behaviors** across 30 prompt pairs:
- Agreement bias: **45%** · Pressure capitulation: **40%** · Flattery resistance: **80%**
- Keyword-based scorers with weighted JSON classification
- Discovered context-dependent capitulation: model abandons correct positions on some facts (flat Earth) while holding firm on others (Pluto)
- Full harness + Streamlit dashboard + **13 unit tests** on GitHub

</td>
<td width="50%" valign="top">

### 🧩 Chain-of-Thought Faithfulness Evaluation
**`Llama-3-8B · BIG-Bench-Hard · HuggingFace`**

Investigating whether Llama-3-8B's stated reasoning **drives** its answers or is post-hoc rationalization:
- Replicating Turpin et al. (2023) & Lanham et al. (2023) methodology
- Biasing-feature perturbation: injecting wrong-answer hints, measuring CoT acknowledgment vs. silent conformance
- Paired CoT logging + bias-acknowledgement tagging
- Results & code → [lkslokesh.com](https://lkslokesh.com)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ AI-Powered DDoS Detection (Capstone)
**`BiLSTM · 1D Residual CNN · PyTorch · BCCC-Cloud-DDoS-2024`**

Production-grade intrusion detection ensemble on **700K+ flows**:
- **94.11% accuracy** on 3-class classification (Attack / Benign / Suspicious)
- 318 raw features → 86 via selection; sliding temporal windows for sequence modeling
- Confidence-based escalation: auto-classifies **85% of traffic** at high confidence, routes ambiguous flows for review
- Architecture seeded from UNSW-NB15 research at Anna University

</td>
<td width="50%" valign="top">

### 📚 SQ3R AI Study System (Chrome Extension)
**`TypeScript · React · Node.js · SQLite · FSRS-4.5`**

Browser-native AI study platform transforming any page or PDF into structured flashcards:
- Supports **local Ollama + cloud LLMs** (Claude, OpenAI, Gemini, DeepSeek)
- **FSRS-4.5 spaced-repetition** scheduling via ts-fsrs for dynamic intervals
- Finite-state batch review machine with mutex-locked queue states across service workers
- Pomodoro interrupt system with browse-time popup cards (no extension open required)

</td>
</tr>
</table>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🏗️ Engineering Projects

<div align="center">

| Project | Stack | Highlight |
|:--------|:------|:----------|
| **🤖 OpenClaw** | Node.js, K8s, CI/CD | Multi-agent RAG system on Kubernetes with full CI/CD |
| **🎬 Video Streaming Platform** | MinIO, HEVC, FFmpeg | Adaptive HEVC transcoding with object-storage backend |
| **📚 E-Library** | React, React Native, FastAPI | Cross-platform library management (web + mobile) |
| **🩸 Blood Donor App** | Spring Boot, PostgreSQL | Microservice donor matching with notification system |
| **⚡ Static Site Generator** | C++ | Zero-dependency SSG from scratch |
| **🌐 QUIC Router Simulation** | Python | Protocol-level simulation of QUIC routing |
| **🌾 Lokesh Agro Foods Platform** | React, FastAPI, ML | Produce grading via image classification + billing automation |

</div>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 💼 Experience

<table>
<tr>
<td width="10%" align="center">🎓</td>
<td>

**Instructional Assistant — Data Structures & Algorithms**  
*Pennsylvania State University · Aug 2024 – Present*  
Teaching Java & Haskell to 100+ graduate students across DSA and Discrete Mathematics. Weekly instruction, office hours, and iterated problem sets with the instructor based on class-wide performance analysis.

</td>
</tr>
<tr>
<td align="center">🔬</td>
<td>

**AI Research Intern — Network Intrusion Detection**  
*Anna University, College of Engineering Guindy · Feb 2023 – Jul 2024*  
Deep-learning IDS pipeline on UNSW-NB15 with LSTM + 1D CNN. Applied SMOTE for class-imbalance handling and temporal window analysis — directly seeded the architecture of the 94% DDoS capstone.

</td>
</tr>
<tr>
<td align="center">☁️</td>
<td>

**Platform Engineer Intern**  
*Tvastr*  
AWS compliance engine across 1,000+ accounts; Elasticsearch query optimization for infrastructure observability pipelines.

</td>
</tr>
<tr>
<td align="center">🌾</td>
<td>

**ML Software Engineer**  
*Lokesh Agro Foods*  
Image classification for produce quality grading; automated billing and inventory systems for family-owned organic food business.

</td>
</tr>
</table>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🛠️ Tech Stack

<div align="center">

### Languages
<img src="https://skillicons.dev/icons?i=python,cpp,java,ts,js,bash&theme=dark"/>

### AI / ML
<img src="https://skillicons.dev/icons?i=pytorch,sklearn&theme=dark"/>

![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![RAG](https://img.shields.io/badge/RAG-00D4FF?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
![FSRS](https://img.shields.io/badge/FSRS--4.5-6C63FF?style=flat-square)

### Backend & Frontend
<img src="https://skillicons.dev/icons?i=fastapi,spring,react,nextjs,nodejs&theme=dark"/>

### Infrastructure & Cloud
<img src="https://skillicons.dev/icons?i=aws,kubernetes,docker,linux,git,github&theme=dark"/>

### Security & Networking
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Snort](https://img.shields.io/badge/Snort-CC0000?style=flat-square)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square)
`QUIC` · `TCP/IP` · `SIEM` · `Elasticsearch`

### Research Focus
![LLM Eval](https://img.shields.io/badge/LLM%20Evaluation-00D4FF?style=flat-square)
![Adversarial](https://img.shields.io/badge/Adversarial%20Prompting-FF4B4B?style=flat-square)
![CoT](https://img.shields.io/badge/Chain--of--Thought%20Faithfulness-6C63FF?style=flat-square)
![Sycophancy](https://img.shields.io/badge/Sycophancy%20Measurement-FFD700?style=flat-square)
![Alignment](https://img.shields.io/badge/Empirical%20Alignment-00FF87?style=flat-square)

</div>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📊 GitHub Stats

<div align="center">

<a href="https://git.io/streak-stats">
  <img src="https://streak-stats.demolab.com?user=loki52501&theme=tokyonight&hide_border=true&background=0D1117&ring=00D4FF&fire=00D4FF&currStreakLabel=00D4FF" width="68%" alt="Streak"/>
</a>

<br/><br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=loki52501&theme=tokyonight" width="68%"/>

<br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=loki52501&theme=tokyonight" width="33%"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=loki52501&theme=tokyonight" width="33%"/>

<br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=loki52501&theme=tokyonight" width="33%"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=loki52501&theme=tokyonight&utcOffset=-5" width="33%"/>

</div>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🏅 Certifications

<div align="center">

<img src="https://img.shields.io/badge/Cisco-CCNA-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white"/>
&nbsp;&nbsp;
<img src="https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=for-the-badge&logo=comptia&logoColor=white"/>

</div>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Snake animation -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/loki52501/loki52501/output/github-snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/loki52501/loki52501/output/github-snake.svg" alt="Snake animation"/>
  </picture>
</div>

---

<div align="center">

### 🚀 Open to Roles In

![AI Engineer](https://img.shields.io/badge/AI%20Engineer-00D4FF?style=for-the-badge)
![AI Reliability Engineer](https://img.shields.io/badge/AI%20Reliability%20Engineer-6C63FF?style=for-the-badge)
![Applied ML Engineer](https://img.shields.io/badge/Applied%20ML%20Engineer-00FF87?style=for-the-badge)
![AI Solutions Architect](https://img.shields.io/badge/AI%20Solutions%20Architect-FF6B35?style=for-the-badge)
![LLM Evaluation](https://img.shields.io/badge/LLM%20Evaluation%20%26%20Safety-FFD700?style=for-the-badge)

<br/>

**OPT available ~June 2026 · Open to relocation**

<br/>

<a href="https://linkedin.com/in/lkslokesh">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://lkslokesh.com">
  <img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=firefox&logoColor=00D4FF"/>
</a>
<a href="mailto:lokeshlks01@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br/><br/>

<sub>Built with focus, coffee, and a healthy suspicion of post-hoc rationalization ☕</sub>

</div>

<!--
  ╔══════════════════════════════════════════════════════════════╗
  ║  🐍 Snake Animation Setup                                   ║
  ║                                                              ║
  ║  1. Go to loki52501/loki52501 → Actions tab                  ║
  ║  2. Create .github/workflows/snake.yml with:                 ║
  ║                                                              ║
  ║  name: Generate Snake                                        ║
  ║  on:                                                         ║
  ║    schedule:                                                 ║
  ║      - cron: "0 0 * * *"                                     ║
  ║    workflow_dispatch:                                         ║
  ║  jobs:                                                       ║
  ║    build:                                                     ║
  ║      runs-on: ubuntu-latest                                  ║
  ║      steps:                                                  ║
  ║        - uses: Platane/snk@v3                                ║
  ║          with:                                               ║
  ║            github_user_name: loki52501                       ║
  ║            outputs: |                                        ║
  ║              dist/github-snake.svg                           ║
  ║              dist/github-snake-dark.svg?palette=github-dark  ║
  ║        - uses: crazy-max/ghaction-github-pages@v3.1.0        ║
  ║          with:                                               ║
  ║            target_branch: output                             ║
  ║            build_dir: dist                                   ║
  ║          env:                                                ║
  ║            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}         ║
  ║                                                              ║
  ║  3. Run workflow manually once                               ║
  ╚══════════════════════════════════════════════════════════════╝
-->
