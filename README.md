<!-- DARSHIT PATEL | PROFILE README | RECRUITER-OPTIMIZED -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:090B18,35:5B21B6,70:0EA5E9,100:22D3EE&height=200&section=header&text=PATEL%20DARSHIT&fontSize=52&fontAlignY=34&desc=AI%20SYSTEMS%20ENGINEER%20%E2%80%A2%20FULL-STACK%20DEVELOPER&descSize=18&descAlignY=58&animation=twinkling&fontColor=FFFFFF" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=2600&pause=700&color=22D3EE&center=true&vCenter=true&width=760&lines=Building+AI+systems+that+ship+to+real+users;Full-stack+%7C+LLM+%7C+RAG+%7C+Computer+Vision;Python+%2B+Next.js+%2B+Systems+Thinking" alt="Typing introduction" />

<br>

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-111827?style=for-the-badge&logo=google-chrome&logoColor=22D3EE)](https://darshitpatel.me/)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/darshitp091/)
[![Email](https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:darshitp091@gmail.com)
[![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/darshitp091)

<img src="https://komarev.com/ghpvc/?username=darshitp091&style=for-the-badge&color=5B21B6&label=PROFILE+VISITS" alt="Profile views" />

</div>

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Technologist.png" width="32" /> Player Profile

```text
╔════════════════════════════════════════════════════════════════════╗
║  PLAYER  : Darshit Patel                                          ║
║  CLASS   : AI Systems Builder + Full-Stack Developer              ║
║  BASE    : India                                                  ║
║  STUDY   : B.Tech Computer Science, NIMS University (2023–2027)   ║
║  QUEST   : Engineer useful, reliable, measurable AI products      ║
║  STATUS  : Open to internships, graduate roles, and collaborations║
╚════════════════════════════════════════════════════════════════════╝
```

I build end-to-end products that combine **Python, modern web engineering, language models, and applied computer vision**. My strongest work sits where software meets an operational problem: offline voice assistants, agent reliability middleware, real-time web platforms, browser automation, and AI-powered business tools.

I am not optimized for "demo-only" projects. I care about state management, failure modes, latency, local-first privacy, cost controls, observability, and a clear path from prototype to use.

### Profile Readme Formula: **C–A–T–I**

| Step | Recruiter-facing question | How I answer it |
|:---:|:---|:---|
| **C** | What problem existed? | Start with the real constraint or user pain. |
| **A** | What did you personally design/build? | Name the architecture, stack, and engineering decisions. |
| **T** | What trade-off did you manage? | Explain cost, latency, privacy, reliability, or complexity. |
| **I** | What changed because of the build? | State verified behavior, capability, or product outcome—never invent metrics. |

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Credit%20Card.png" width="32" /> Recruiter Quick View

| Dimension | Evidence |
|:---|:---|
| Primary stack | Python, TypeScript, JavaScript, Next.js, React, FastAPI, Node.js |
| AI / ML | RAG, LLM orchestration, Whisper fine-tuning, Ollama, Groq, LangGraph, PyTorch/LoRA |
| Applied vision | MediaPipe, OpenCV, hand gestures, eye-gaze tracking |
| Data / backend | PostgreSQL, Supabase, REST APIs, WebSockets, PL/pgSQL |
| AI infrastructure | Cost budgets, circuit-breaking, model fallback routing, local-first inference |
| Engineering habits | Typed interfaces, modular architectures, reproducible setup, README-first documentation |
| Portfolio | [darshit-portfolio-eta.vercel.app](https://darshit-portfolio-eta.vercel.app/) |

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" width="32" /> Flagship Build Log

### 01 | JARVIS — Privacy-First Spatial AI Assistant

<p>
  <a href="https://github.com/darshitp091/Jarvis"><img src="https://github-readme-stats.vercel.app/api/pin/?username=darshitp091&repo=Jarvis&theme=tokyonight&hide_border=true&border_radius=12" /></a>
</p>

**C — Context:** Typical desktop assistants depend on the cloud and do not provide rich, hands-free spatial control.

**A — Architecture:** Built a Python desktop control system with fine-tuned Whisper-style Hinglish speech understanding, MediaPipe hand tracking, eye-gaze tracking, neural TTS, Ollama/local model routing, cloud fallback, and OS automation.

**T — Trade-offs:** Balanced privacy and capability by prioritizing local inference while retaining explicit fallback paths for tasks that need more compute.

**I — Impact:** Demonstrates an end-to-end local AI workflow—from microphone input and vision signals to agent decisions and executable desktop actions—rather than a disconnected model demo.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square" />
  <img src="https://img.shields.io/badge/Ollama-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Privacy-first-22C55E?style=flat-square" />
</p>

---

### 02 | Agent Circuit Breaker — Reliability Middleware for AI Agents

**C — Context:** Multi-agent systems can loop, drift, and generate redundant tool calls until latency and API cost become uncontrolled.

**A — Architecture:** Designed middleware for LangGraph, CrewAI, and AutoGen workflows using semantic loop detection, TF-IDF cosine similarity, edit-distance analysis, state checkpoints, cost budgets, time-travel debugging, and PyTorch LoRA support.

**T — Trade-offs:** Added multiple detection signals instead of relying on one similarity rule, balancing false positives with the need to stop runaway execution quickly.

**I — Impact:** Moves agent reliability concerns outside the prompt and into a reusable middleware layer, making multi-agent behavior more observable and easier to control.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/CrewAI-FF4F00?style=flat-square" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TF--IDF-5B21B6?style=flat-square" />
  <img src="https://img.shields.io/badge/LoRA-22D3EE?style=flat-square" />
</p>

---

### 03 | TypeLively — Real-Time Typing Experience

<p>
  <a href="https://github.com/darshitp091/TypeLively"><img src="https://github-readme-stats.vercel.app/api/pin/?username=darshitp091&repo=TypeLively&theme=tokyonight&hide_border=true&border_radius=12" /></a>
</p>

**C — Context:** A typing game should feel immediate, retain accurate test state, and remain fair across concurrent users.

**A — Architecture:** Built with Next.js 16, React 19, TypeScript, Supabase real-time channels, a sliding word window, server-side bot rejection, and Web Audio for generated mechanical-keyboard feedback.

**T — Trade-offs:** Used a bounded DOM rendering window and real-time synchronization to protect low-latency interaction instead of rendering an entire test at once.

**I — Impact:** Combines live state, competitive leaderboards, audio feedback, and abuse resistance in one browser-native product.

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black" />
  <img src="https://img.shields.io/badge/WebSocket-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/Web_Audio-F107A3?style=flat-square" />
</p>

---

### 04 | BolKe — Voice-to-Storefront Pipeline

<p>
  <a href="https://github.com/darshitp091/BolKe"><img src="https://github-readme-stats.vercel.app/api/pin/?username=darshitp091&repo=BolKe&theme=tokyonight&hide_border=true&border_radius=12" /></a>
</p>

**C — Context:** Small-business owners need a faster route from spoken requirements to an industry-specific online presence.

**A — Architecture:** Built a distributed pipeline for speech capture, transcription, LLM inference, generated storefront structure, and dynamic React rendering across multiple business verticals.

**T — Trade-offs:** Designed provider fallback around inference availability while keeping the generated experience modular enough for different industries.

**I — Impact:** Turned a natural-language input workflow into a repeatable generation pipeline instead of a static landing-page template.

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Whisper-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/Ollama-111827?style=flat-square" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square" />
</p>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Joystick.png" width="32" /> More Missions

| Project | Mission | Core Engineering |
|:---|:---|:---|
| [Chess Engine](https://github.com/darshitp091/chess-engine) | Deterministic fixed-node chess engine for a 4 KB Python bounty | Search constraints, fixed-node logic, Python optimization |
| [Readme.3D](https://github.com/darshitp091/Readme.3D) | Immersive 3D README experience with AI-assisted documentation synthesis | Gemini integration, TypeScript, generated web UI |
| [YourCV](https://github.com/darshitp091/YourCV) | Open-source AI resume builder focused on ATS-friendly output | Google Gemini, LaTeX-style templates, JavaScript |
| [RoadSter Free Racing](https://github.com/darshitp091/RoadSter-Free-Racing) | Racing game experience | TypeScript, game-state design, frontend interaction |
| [Facebook Lead Follow-Up](https://github.com/darshitp091/Facebook-Lead-Finde-Follow-Ups) | Automated lead capture and personalized follow-up | n8n, Google Sheets, Gmail, OpenRouter |
| [WhatsApp Booking Assistant](https://github.com/darshitp091/Whatsapp-Booking-Assistant-Automation) | Booking automation workflow | Python, conversational automation, integrations |

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Wrench.png" width="32" /> Engineering Loadout

<div align="center">

### Languages & Runtime

<img src="https://skillicons.dev/icons?i=python,ts,js,java,html,css&theme=dark&perline=6" />

### Frameworks & Data

<img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,fastapi,postgres,supabase,tailwind&theme=dark&perline=7" />

### AI, Cloud & Tools

<img src="https://skillicons.dev/icons?i=pytorch,git,github,docker,gcp,vercel,vscode,linux&theme=dark&perline=8" />

</div>

### Skill XP

```text
Python & applied automation       ████████████████████░  94%
Full-stack TypeScript / Next.js   ██████████████████░░░  88%
LLM systems & orchestration       █████████████████░░░░  84%
Computer vision & multimedia AI   ████████████████░░░░░░  78%
RAG / vector databases / scaling  ██████████████░░░░░░░░  70%
```

> XP bars represent a personal learning map, not formal benchmarks or company ratings.

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" width="32" /> GitHub Telemetry

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=darshitp091&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs?username=darshitp091&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

<img src="https://streak-stats.demolab.com?user=darshitp091&theme=tokyonight&hide_border=true&border_radius=12" alt="GitHub streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=darshitp091&theme=tokyo-night&hide_border=true&area=true&radius=12" width="95%" alt="Contribution graph" />

</div>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Trophy.png" width="32" /> Certifications & Continuous Learning

- Google Cloud — Prompt Engineering & AI
- Google Cloud — Vertex AI Prompt Design
- Deloitte — Technology Consulting
- Deepening: RAG architectures, vector databases, distributed AI, Kubernetes, and production MLOps

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bullet%20Train.png" width="32" /> Current Build Queue

```mermaid
flowchart LR
    A[Reliable agent loops] --> B[Cost-aware orchestration]
    B --> C[Observability & debugging]
    C --> D[Production deployment]
```

- **Exploring:** RAG evaluation, vector search, distributed inference, Kubernetes
- **Strengthening:** system design, testing, deployment, data pipelines
- **Open to:** AI Engineer, Full-Stack Developer, Python Developer, and SDE internship opportunities

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Incoming%20Envelope.png" width="32" /> Establish Contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Darshit_Patel-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/darshitp091/)
[![Email](https://img.shields.io/badge/Gmail-darshitp091%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:darshitp091@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Explore_Projects-111827?style=for-the-badge&logo=google-chrome&logoColor=22D3EE)](https://darshit-portfolio-eta.vercel.app/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:090B18,35:5B21B6,70:0EA5E9,100:22D3EE&height=110&section=footer&text=BUILD.%20BREAK.%20LEARN.%20SHIP.&fontSize=24&fontAlignY=65&animation=twinkling&fontColor=FFFFFF" width="100%" />

</div>
