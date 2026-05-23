<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=26&duration=3000&pause=1000&color=A855F7&center=true&vCenter=true&repeat=true&width=960&height=60&lines=Lokesh+Srinivasaperumal;C%2B%2B+at+heart%2C+Python+%26+JS+by+trade;Tinkering+with+mech+interp+%26+CUDA;Building+LLMs+from+scratch+for+fun" alt="Typing SVG" />
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

## 👋 hey, i'm lokesh

i write C++ because i like knowing where my memory lives. python and js pay the bills and ship the demos. rust is the new toy on my desk — half-learned, half-loved, fully humbling.

right now i'm deep in **mechanistic interpretability** — poking at transformer internals, residual streams, attention heads, trying to figure out what these models are *actually* doing under the hood instead of what they *say* they're doing. there's a difference, and the gap is where most of the interesting stuff hides.

on the side i'm picking up **CUDA**, getting comfortable with kernels, memory hierarchies, and the general vibe of writing code that runs on a few thousand threads at once. parallel programming on GPU clusters is genuinely fun in a way i didn't expect — it's like puzzle-solving where the puzzle pushes back.

i've built LLMs from scratch (yes, the whole stack — tokenizer, attention, training loop, the works) and shipped a few AI-native apps. i like building things that don't work yet more than things that already do.

```cpp
// the stack, roughly
auto me = Developer {
    .heart       = "C++",
    .daily       = {"Python", "JavaScript"},
    .learning    = "Rust",
    .tinkering   = {"mech interp", "CUDA", "GPU clusters"},
    .built       = {"LLMs from scratch", "AI-native apps"},
    .obsession   = "what's actually happening inside the model"
};
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🔮 a thought i can't shake

when i think about LLMs, i don't think about chatbots. i think about **oracles**.

the ancient ones — Delphi, Cumae, the seers kings consulted before marching to war. people brought them the biggest questions of their lives and walked away convinced. and for centuries, empires were built and burned on the strength of that conviction.

the oracles weren't always wrong. that's the unsettling part. they were *often* right, just often enough that doubting them felt unreasonable. and when they were wrong, the ashes were enormous.

LLMs feel like that to me. they're genuinely intelligent — not in the cute "look what it did" way, but in the *this-is-actually-reasoning* way. and we're starting to consult them on real things. real decisions. real lives.

but here's what keeps me up:

- **evaluation isn't a solved problem.** it's not even close. the benchmarks shift, the failure modes shift, the goalposts shift. we're grading the oracle with a ruler that keeps changing length.
- **there's no moral compass in there.** not a broken one — *none*. whatever ethics show up are stitched on from the outside, and the stitching is loose.
- **and yet they're smart enough to be persuasive.** which is the exact combination that got empires into trouble the first time around.

so that's the thread running through most of what i build — interpretability work, evaluation harnesses, sycophancy probes, CoT faithfulness tests. not because i think AI is bad, but because i think *we don't actually know what it's doing yet*, and pretending we do is how the ashes happen.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🛠️ stuff i've built

<table>
<tr>
<td width="50%" valign="top">

### 🧠 LLM Sycophancy + CoT Faithfulness Suite
**`Llama-3 · PyTorch · BIG-Bench-Hard`**

does the model actually believe what it says? probably not always. this suite tests for it — agreement bias, pressure capitulation, flattery resistance, and whether chain-of-thought reasoning is real reasoning or theater. extends Turpin and Lanham's work onto Llama-3-8B.

</td>
<td width="50%" valign="top">

### 🔬 Mech Interp Tinkering
**`ARENA · TransformerLens · residual stream probes`**

working through Neel Nanda's curriculum, ARENA chapter 1, attention head analysis, the whole linear algebra rabbit hole. extending CoT faithfulness into residual stream probing — if the model's CoT lies, does the residual stream tell the truth?

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🐾 OpenClaw — Multi-Agent RAG on K8s
**`Node.js · Kubernetes · ChromaDB`**

multi-agent RAG system that actually runs in production. agent pods scale independently, ChromaDB for the vector side, GitHub Actions → Docker → K8s for the boring-but-important part.

</td>
<td width="50%" valign="top">

### 📚 SQ3R AI Study Agent
**`TypeScript · React · FSRS-4.5 · Multi-LLM`**

chrome extension that turns any page or PDF into spaced-repetition flashcards. routes between local Ollama and cloud LLMs, FSRS-4.5 scheduling, a pomodoro agent that ambushes you with due cards.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌊 DDoS Detection IDS
**`BiLSTM · 1D Residual CNN · PyTorch`**

ensemble IDS on 700K+ network flows. 94.11% accuracy on 3-class. confidence-gated routing so the model doesn't pretend to be sure when it isn't — same theme as the LLM work, different stack.

</td>
<td width="50%" valign="top">

### ⚡ Other Stuff Worth Mentioning
zero-dependency static site generator in C++, QUIC router simulation, HEVC video streaming platform with MinIO, a microservice blood donor app, an agro-foods produce-grading ML pipeline for the family business. mostly side quests.

</td>
</tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 💼 where i've been

- **Instructional Assistant — DSA & Discrete Math** · Penn State · *Aug 2024 – present*
- **AI Research Intern — Network IDS** · Anna University CEG · *Feb 2023 – Jul 2024*
- **Platform Engineer Intern** · Tvastr · AWS compliance automation across 1000+ accounts
- **ML Engineer** · Lokesh Agro Foods · image classification for produce grading, family-owned organic foods business

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🧰 what i use

<div align="center">

### languages
<img src="https://skillicons.dev/icons?i=cpp,python,ts,js,rust,bash&theme=dark"/>

C++ for serious work · Python and JS for everything else · Rust because it's time

### ML / LLM
<img src="https://skillicons.dev/icons?i=pytorch,sklearn&theme=dark"/>

![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![TransformerLens](https://img.shields.io/badge/TransformerLens-A855F7?style=flat-square)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)

### infra
<img src="https://skillicons.dev/icons?i=aws,kubernetes,docker,linux,git,github&theme=dark"/>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📊 the github numbers

<div align="center">

<a href="https://git.io/streak-stats">
  <img src="https://streak-stats.demolab.com?user=loki52501&theme=tokyonight&hide_border=true&background=0D1117&ring=A855F7&fire=A855F7&currStreakLabel=A855F7" width="68%"/>
</a>

<br/><br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=loki52501&theme=tokyonight" width="33%"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=loki52501&theme=tokyonight" width="33%"/>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<div align="center">

### 📫 say hi

<a href="https://linkedin.com/in/lkslokesh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://lkslokesh.com"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=vercel&logoColor=A855F7"/></a>
<a href="mailto:lokeshlks01@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br/><br/>

<sub><i>the oracles weren't always wrong. that was the problem.</i></sub>

</div>
