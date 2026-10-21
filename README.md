<div align="center">

<img src="assets/header.svg" width="100%" alt="Sanjay Azhagan. AI systems engineer, B.Tech CSE at IIITDM Kancheepuram, class of 2028"/>

<br/>

<a href="https://sanjayazhagan.tech"><img src="https://img.shields.io/badge/Portfolio-1F3864?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/sanjay-azhagan-85a8622a6"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:sanjayazhagan@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.kaggle.com/sanjayazhagan"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"/></a>

<br/><br/>

<img src="assets/terminal.svg" width="82%" alt="Terminal: whoami, current research, experience at Montra Electric and DM8, and achievements"/>

</div>

<img src="assets/divider.svg" width="100%" alt=""/>

<h2 align="center">✦ Featured work ✦</h2>

<table>
<tr>
<td width="50%" valign="top">

### ⚖️ VeriLaw AI
**A legal contract auditor where client data never leaves the gateway.**

- PII is scrubbed at an Express gateway **before** any model sees the document
- LangGraph map-reduce: a supervisor fans clauses out to parallel LLM workers with exponential backoff, then a reviewer writes the summary
- Self-hosted on Azure with Docker and Nginx

`TypeScript` `FastAPI` `LangGraph` `React` `PostgreSQL` `Redis`

<a href="https://sanjayazhagan.tech/veri-law/"><img src="https://img.shields.io/badge/Live_demo-7EE7C7?style=flat-square&logo=googlechrome&logoColor=0B1D3A" alt="Live demo"/></a>
<a href="https://www.youtube.com/watch?v=4te5t5ihVNs"><img src="https://img.shields.io/badge/Video-FF0000?style=flat-square&logo=youtube&logoColor=white" alt="Video"/></a>
<a href="https://github.com/Sanjayazhagan/VeriLaw-AI"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white" alt="Code"/></a>

</td>
<td width="50%" valign="top">

### 🎮 Legion of Minds
**A strategy game where every troop is an RL agent you train on your own CPU.**

- PPO written from scratch in Rust: no ML libraries, no GPU, up to **7,500 steps/s** on 4 cores
- Each unit is its own neural network (90 inputs, 21 actions), trained by self-play
- Axum + PostgreSQL backend re-runs every raid deterministically, so a tampered client can't fake a win

`Rust` `PPO` `Axum` `PostgreSQL` `OpenGL` `Docker`

<a href="https://github.com/Sanjayazhagan/Legion-of-Minds"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧮 RLAIF with GRPO
**Teaching a 0.5B model to reason through math, on free GPUs.**

- Fine-tuned Qwen2.5-0.5B-Instruct on GSM8K with GRPO and programmatic rewards
- **100%** format compliance and **48%** accuracy on two free T4 GPUs

`PyTorch` `TRL` `verifiers` `GSM8K`

<a href="https://www.kaggle.com/code/sanjayazhagan/notebookcd87299d49"><img src="https://img.shields.io/badge/Kaggle_notebook-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle notebook"/></a>

</td>
<td width="50%" valign="top">

### 📡 SmartScan · SIH 2026
**A radio-band scheduler for electronic-warfare receivers (team project).**

- I built the benchmark on the Alan Turing Institute radar dataset
- Won **222 of 250 missions** against UCB1 and Thompson sampling, with ~9× fewer band switches

`Python` `NumPy` `NMF` `Multi-armed bandits`

<a href="https://github.com/Sanjayazhagan/Smart_scan"><img src="https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white" alt="Code"/></a>

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>

**[StudySphere](https://github.com/Sanjayazhagan/Study-Sphere)**: a notes-sharing platform built at the Vashist Hackathon. An AI grades uploaded notes and rewards good contributions with tokens, which members spend on RAG queries over the shared notes. Built with Node.js, PostgreSQL, Pinecone and LangChain.

</details>

<h2 align="center">✦ Now researching ✦</h2>

> [!NOTE]
> **Adversarial AI agents for automated game testing.** An LLM "tester" explores 3D games looking for failures while a planner agent learns to survive them, so the two improve against each other.
>
> So far: the Phase 1 benchmark on SuperTuxKart (PPO, NVIDIA NitroGen and LLM-planner baselines against a scripted oracle) and the Phase 2 open-world setup in Craftium. I'm also co-authoring a survey on reinforcement learning for game QA.

<h2 align="center">✦ Experience ✦</h2>

<table>
<tr>
<td width="50%" valign="top">

**Software Engineering Intern (AI Systems)**<br/>
Montra Electric · May – Jul 2026

Redis pub/sub backend orchestrating AI jobs for 50+ concurrent users, an execution harness for AI coding agents with rate limiting and idempotent retries, and a Docker sandbox for running AI-generated code safely.

</td>
<td width="50%" valign="top">

**Full-Stack Developer Intern**<br/>
DM8 · Dec 2025 – May 2026

Led end-to-end development of a SvelteKit freelance platform, from UI requirements to Docker production deployment.

</td>
</tr>
</table>

<h2 align="center">✦ Tech stack ✦</h2>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,cpp,rust,pytorch,react,nextjs,svelte,tailwind,nodejs,express,fastapi,postgres,redis,docker,azure,nginx,linux,git,githubactions&perline=10" alt="Python, TypeScript, C++, Rust, PyTorch, React, Next.js, Svelte, Tailwind, Node.js, Express, FastAPI, PostgreSQL, Redis, Docker, Azure, Nginx, Linux, Git, GitHub Actions"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square" alt="Pinecone"/>
  <img src="https://img.shields.io/badge/GRPO_·_PPO_·_QLoRA-6E40C9?style=flat-square" alt="GRPO, PPO, QLoRA"/>
</p>

<h2 align="center">✦ Contribution snake ✦</h2>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sanjayazhagan/Sanjayazhagan/output/github-snake-dark.svg"/>
    <img alt="A snake eating Sanjay's GitHub contribution graph" src="https://raw.githubusercontent.com/Sanjayazhagan/Sanjayazhagan/output/github-snake.svg" width="100%"/>
  </picture>
</p>

<img src="assets/footer.svg" width="100%" alt="Thanks for visiting"/>
