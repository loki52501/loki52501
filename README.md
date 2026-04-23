<div align="center">

<!-- Hero typing banner -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=26&duration=3000&pause=1000&color=A855F7&center=true&vCenter=true&repeat=true&width=960&height=60&lines=Lokesh+Srinivasaperumal;AI+Engineer+%E2%80%94+Agentic+Systems+%26+LLM+Infra;Designing+Multi-Agent+Pipelines+%26+AI+Solutions;AI+Solutions+Architect+%7C+Applied+ML+%7C+Cloud" alt="Typing SVG" />
</a>

<br/>

<a href="https://linkedin.com/in/lkslokesh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://lkslokesh.com"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=vercel&logoColor=A855F7"/></a>
<a href="mailto:lokeshlks01@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/loki52501"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=loki52501&style=flat-square&color=A855F7&label=PROFILE+VIEWS"/>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## ⚡ `whoami`

```python
class Lokesh:
    title      = "AI Engineer · Agentic Systems Designer · AI Solutions Architect"
    education  = [
        "M.S. Cybersecurity Operations & Technology — Penn State (3.7 GPA, May 2026)",
        "Integrated M.S. Information Technology — Anna University (3.3 GPA)",
    ]
    building   = [
        "Multi-agent RAG pipelines on Kubernetes",
        "LLM evaluation pipelines for sycophancy, CoT faithfulness & adversarial robustness",
        "AI-native security systems — threat detection, anomaly detection, IDS",
        "Browser-native AI tools with spaced-repetition & adaptive scheduling",
    ]
    stack      = ["Python", "PyTorch", "HuggingFace", "LangChain", "FastAPI",
                  "Docker", "Kubernetes", "AWS", "RAG", "ChromaDB", "Ollama"]
    certs      = ["Cisco CCNA", "CompTIA Security+"]
    philosophy = "Agents that reason well must also reason honestly."
    status     = "OPT-ready June 2026 · Open to relocation · Targeting AI infra & agentic roles"
```

<br/>

> **"How do you know when a system's stated behavior reflects its actual internal state?"**
>
> *This question connects everything I build — from IDS pipelines that detect hidden attack patterns, to LLM evaluators that catch post-hoc rationalization, to agentic systems that need auditable decision trails.*

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🤖 Agentic AI Systems

> Projects where I architect, orchestrate, and ship multi-agent and LLM-powered systems end-to-end.

<table>
<tr>
<td width="50%" valign="top">

### 🐾 OpenClaw — Multi-Agent RAG on K8s
**`Node.js · Kubernetes · RAG · ChromaDB · CI/CD`**

Production multi-agent RAG system deployed on Kubernetes:
- Agent orchestration layer with retrieval, synthesis, and response agents
- ChromaDB vector store with semantic chunking pipeline
- Full CI/CD — GitHub Actions → Docker → K8s rolling deploys
- Designed for horizontal scale: agent pods scale independently on load

</td>

</tr>
<tr>


</tr>
<tr>
<td width="50%" valign="top">

### 📚 SQ3R AI Study Agent — Chrome Extension
**`TypeScript · React · Node.js · SQLite · FSRS-4.5 · Multi-LLM`**

Browser-native AI agent transforming any page or PDF into a full study system:
- **Multi-LLM routing**: local Ollama or cloud (Claude, OpenAI, Gemini, DeepSeek)
- **FSRS-4.5** spaced-repetition with dynamic stability & difficulty curves
- Finite-state review machine with mutex-locked batch queue across service workers
- Pomodoro interrupt agent auto-surfaces due cards without opening the extension

</td>
<td width="50%" valign="top">

### 🧠 LLM Sycophancy + CoT Faithfulness Suite
**`Llama-3.2-3B / 3-8B · PyTorch · BIG-Bench-Hard · Streamlit`**

Two-part LLM evaluation suite probing internal alignment:
- **Sycophancy harness**: agreement bias **45%**, pressure capitulation **40%**, flattery resistance **80%**
- **CoT faithfulness**: biasing-feature perturbation on BIG-Bench-Hard — does the chain of thought verbalize or silently conform?
- Extends Turpin et al. (2023) & Lanham et al. (2023) on Llama-3-8B
- Full harness + Streamlit dashboard + 13 unit tests on GitHub

</td>
</tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🏗️ Agentic System Architecture — How I Design AI Solutions

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                       AGENTIC AI SOLUTION BLUEPRINT                         ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   USER / APP  ──►  [ API Gateway / Prompt Interface ]                        ║
║                              │                                               ║
║                     ┌────────▼────────┐                                      ║
║                     │  Planner Agent  │  ← Task decomposition                ║
║                     │  (Orchestrator) │  ← Tool selection                    ║
║                     └────────┬────────┘  ← Confidence gating                ║
║                              │                                               ║
║          ┌───────────────────┼───────────────────┐                          ║
║          ▼                   ▼                   ▼                          ║
║   [ Retrieval Agent ]  [ Synthesis Agent ]  [ Action Agent ]                ║
║     ChromaDB / RAG      LLM reasoning         Tool APIs                     ║
║          │                   │                   │                          ║
║          └───────────────────┼───────────────────┘                          ║
║                              │                                               ║
║                     ┌────────▼────────┐                                      ║
║                     │  Eval / Monitor │  ← Sycophancy & CoT faithfulness     ║
║                     │     Layer       │  ← Behavioral consistency checks     ║
║                     │  (LLM harness)  │  ← Confidence-based escalation       ║
║                     └────────┬────────┘                                      ║
║                              │                                               ║
║                     [ Audit Log / Response ]  ──►  USER                      ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🛡️ AI Security & Threat Detection

<table>
<tr>
<td width="50%" valign="top">

### 🌊 DDoS Detection IDS (Capstone)
**`BiLSTM · 1D Residual CNN · PyTorch · BCCC-Cloud-DDoS-2024`**

Ensemble IDS on **700K+ network flows**:
- **94.11% accuracy** — Attack / Benign / Suspicious (3-class)
- 318 features → 86 via selection; sliding temporal windows
- Confidence escalation auto-classifies **85% of traffic**, routes uncertain flows for review
- Architecture lineage: UNSW-NB15 research → refined for cloud DDoS

</td>
<td width="50%" valign="top">

### 🔬 Network IDS Research — Anna University
**`LSTM · 1D CNN · SMOTE · UNSW-NB15`**

Foundational deep-learning IDS pipeline:
- LSTM + 1D CNN with SMOTE for minority attack class balance
- Temporal window analysis directly seeded DDoS capstone architecture
- AI Research Intern, Anna University (2023–2024)

</td>
</tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🔧 Engineering & Platform Projects

<div align="center">

| Project | Stack | What It Does |
|:--------|:------|:-------------|
| **🎬 Video Streaming Platform** | MinIO, HEVC, FFmpeg | Adaptive HEVC transcoding, object-storage backend |
| **📚 E-Library** | React, React Native, FastAPI | Cross-platform library management (web + mobile) |
| **🩸 Blood Donor App** | Spring Boot, PostgreSQL | Microservice donor matching + notification system |
| **⚡ Static Site Generator** | C++ | Zero-dependency SSG from scratch |
| **🌐 QUIC Router Simulation** | Python | Protocol-level simulation of QUIC routing |
| **🌾 Agro Foods Platform** | React, FastAPI, ML | Produce grading via image classification + billing automation |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 💼 Experience

<table>
<tr>
<td width="8%" align="center"><br/>🎓</td>
<td>

**Instructional Assistant — Data Structures & Algorithms**  
*Pennsylvania State University · Aug 2024 – Present*  
Teaching Java & Haskell to 100+ graduate students across DSA and Discrete Mathematics. Weekly instruction and office hours on algorithmic correctness and asymptotic complexity.

</td>
</tr>
<tr>
<td align="center">🔬</td>
<td>

**AI Research Intern — Network Intrusion Detection**  
*Anna University, College of Engineering Guindy · Feb 2023 – Jul 2024*  
Deep-learning IDS pipeline on UNSW-NB15 (LSTM + 1D CNN + SMOTE). Temporal window analysis directly seeded the 94.11% accuracy DDoS capstone architecture.

</td>
</tr>
<tr>
<td align="center">☁️</td>
<td>

**Platform Engineer Intern**  
*Tvastr*  
AWS compliance automation engine spanning 1,000+ accounts. Elasticsearch query optimization for infrastructure observability at scale.

</td>
</tr>
<tr>
<td align="center">🌾</td>
<td>

**ML Software Engineer**  
*Lokesh Agro Foods*  
Image classification for produce quality grading. Automated billing and inventory systems for family-owned organic food business.

</td>
</tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🛠️ Tech Stack

<div align="center">

### Languages
<img src="https://skillicons.dev/icons?i=python,cpp,java,ts,js,bash&theme=dark"/>

### AI / LLM / Agentic Systems
<img src="https://skillicons.dev/icons?i=pytorch,sklearn&theme=dark"/>

![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/RAG_Pipelines-A855F7?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-CC785C?style=flat-square)
![Multi-Agent](https://img.shields.io/badge/Multi--Agent_Orchestration-00FF87?style=flat-square)
![FSRS](https://img.shields.io/badge/FSRS--4.5-6C63FF?style=flat-square)

### Backend & APIs
<img src="https://skillicons.dev/icons?i=fastapi,spring,nodejs&theme=dark"/>

### Frontend
<img src="https://skillicons.dev/icons?i=react,nextjs,ts&theme=dark"/>

### Cloud & Infrastructure
<img src="https://skillicons.dev/icons?i=aws,kubernetes,docker,linux,git,github&theme=dark"/>

![Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![SQS](https://img.shields.io/badge/AWS_SQS-FF9900?style=flat-square)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### Security & Networking
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Snort](https://img.shields.io/badge/Snort-CC0000?style=flat-square)
`TCP/IP` · `QUIC` · `SIEM` · `Nmap` · `Elasticsearch`

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📊 GitHub Stats

<div align="center">

<a href="https://git.io/streak-stats">
  <img src="https://streak-stats.demolab.com?user=loki52501&theme=tokyonight&hide_border=true&background=0D1117&ring=A855F7&fire=A855F7&currStreakLabel=A855F7" width="68%"/>
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

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🏅 Certifications

<div align="center">

<img src="https://img.shields.io/badge/Cisco-CCNA-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white"/>
&nbsp;&nbsp;
<img src="https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=for-the-badge&logo=comptia&logoColor=white"/>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Contribution snake -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/loki52501/loki52501/output/github-snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/loki52501/loki52501/output/github-snake.svg" alt="Snake animation"/>
  </picture>
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<div align="center">

### 🚀 Open to Roles In

![AI Engineer](https://img.shields.io/badge/AI%20Engineer-A855F7?style=for-the-badge)
![Agentic Systems Designer](https://img.shields.io/badge/Agentic%20Systems%20Designer-7C3AED?style=for-the-badge)
![AI Solutions Architect](https://img.shields.io/badge/AI%20Solutions%20Architect-6D28D9?style=for-the-badge)
![LLM Infra Engineer](https://img.shields.io/badge/LLM%20Infrastructure-00D4FF?style=for-the-badge)
![AI Security Engineer](https://img.shields.io/badge/AI%20Security%20Engineer-FF4B4B?style=for-the-badge)

<br/>

**OPT-ready ~June 2026 · Open to relocation · US work authorized**

<br/>

<a href="https://linkedin.com/in/lkslokesh">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://lkslokesh.com">
  <img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=vercel&logoColor=A855F7"/>
</a>
<a href="mailto:lokeshlks01@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br/><br/>

<sub>Agents that reason well must also reason honestly. ☕</sub>

</div>

<!--
  ╔══════════════════════════════════════════════════════════════╗
  ║  🐍 SNAKE ANIMATION SETUP                                   ║
  ║                                                              ║
  ║  Create .github/workflows/snake.yml:                         ║
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
  ╚══════════════════════════════════════════════════════════════╝
-->
