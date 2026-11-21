<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=rect&color=0D1117&height=180&section=header&text=ANKIT%20KUMAR%20PATEL&fontSize=38&fontColor=00E599&fontAlignY=38&desc=Systems%20Engineer%20%E2%80%A2%20Predictive%20Telemetry%20%E2%80%A2%20Distributed%20Backends&descAlignY=58&descSize=16&descColor=94A3B8" width="100%" alt="Header" />

  <p align="center">
    <a href="https://www.nituk.ac.in/"><img src="https://img.shields.io/badge/NIT_Uttarakhand-Systems_Engineering-00E599?style=flat-square&logo=google-classroom&logoColor=black&labelColor=0D1117" alt="NITUK" /></a>
    <a href="https://github.com/open-telemetry/opentelemetry-go-contrib/pull/10077"><img src="https://img.shields.io/badge/CNCF-OpenTelemetry_Contributor-4285F4?style=flat-square&logo=cncf&logoColor=white&labelColor=0D1117" alt="CNCF" /></a>
    <a href="https://cs50.harvard.edu/certificates/19ed713f-176d-4549-94ea-95e6044f8cdf"><img src="https://img.shields.io/badge/Harvard_University-CS50_Python_Certified-A51C30?style=flat-square&logo=harvard&logoColor=white&labelColor=0D1117" alt="Harvard" /></a>
    <a href="https://huggingface.co/The-AnkitPatel"><img src="https://img.shields.io/badge/Hugging_Face-The--AnkitPatel-FFD21E?style=flat-square&logo=huggingface&logoColor=black&labelColor=0D1117" alt="Hugging Face" /></a>
    <a href="https://www.linkedin.com/in/the-ankitkumarpatel/"><img src="https://img.shields.io/badge/LinkedIn-the--ankitkumarpatel-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn" /></a>
    <a href="https://ankitkumarpatel.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-Live-00E599?style=flat-square&logo=netlify&logoColor=black&labelColor=0D1117" alt="Portfolio" /></a>
    <a href="https://leetcode.com/u/theankitpatel/"><img src="https://img.shields.io/badge/LeetCode-theankitpatel-FFA116?style=flat-square&logo=leetcode&logoColor=black&labelColor=0D1117" alt="LeetCode" /></a>
    <a href="mailto:ankitkumarpatel357@gmail.com"><img src="https://img.shields.io/badge/Email-Direct-EA4335?style=flat-square&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email" /></a>
    <img src="https://komarev.com/ghpvc/?username=The-AnkitPatel&style=flat-square&color=00E599&labelColor=0D1117" alt="Views" />
  </p>

</div>

---

B.Tech CSE student at **National Institute of Technology, Uttarakhand (Class of 2028)**. I architect distributed backends, high-throughput financial settlement ledgers, and predictive telemetry infrastructure, and contribute upstream to **CNCF OpenTelemetry**, **Layer5 / Meshery (CNCF)**, and Linux kernel tooling.

- 🌐 **Upstream Contributor to @open-telemetry (CNCF)** — Go runtime tracing instrumentation & OTLP decoders approved by Google maintainers (`#10076`, `#10077`).
- ⚡ **Shipped upstream fixes in Meshery (CNCF)** eliminating TCP socket and file-descriptor leaks across 5 CLI commands (`#22724`, merged into master).
- 🏛️ **Solo Architect & Operator** of NIT Uttarakhand's official enterprise infrastructure (**LeaveDesk**, 700+ DAU, 99.9% uptime SLA on bare-metal servers).
- 🔬 **Research Intern at IIT Roorkee** in eBPF kernel network queuing kinetics (M/M/1/K buffer forecasting).
- 🎓 **Harvard University Certified** in CS50 Programming with Python (100% verified grade).

---

<div align="center">
  <table border="0" width="100%">
    <tr>
      <td width="25%" align="center">
        <h1><b>35+</b></h1>
        <p><b>Merged & Approved PRs</b><br/><sub>across CNCF & systems repos</sub></p>
      </td>
      <td width="25%" align="center">
        <h1><b>CNCF</b></h1>
        <p><b>OpenTelemetry & Meshery</b><br/><sub>Layer5 / CNCF upstream</sub></p>
      </td>
      <td width="25%" align="center">
        <h1><b>700+</b></h1>
        <p><b>Daily Active Users</b><br/><sub>LeaveDesk (NITUK live server)</sub></p>
      </td>
      <td width="25%" align="center">
        <h1><b>99.9%</b></h1>
        <p><b>Production SLA</b><br/><sub>Zero deadlocks via row-locks</sub></p>
      </td>
    </tr>
  </table>
</div>

---

### 💼 Open-Source Experience

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">🌐 CNCF OpenTelemetry — Upstream Contributor</h3>
      <p><b><a href="https://github.com/open-telemetry/opentelemetry-go-contrib">open-telemetry/opentelemetry-go-contrib</a></b> • <i>Go, OTLP, Middleware</i></p>
      <ul>
        <li><b>PR #10077 (Approved by Google maintainer dashpole & dmathieu; 28/28 CI passed):</b> Fixed AWS SDK v2 tracing instrumentation, exempting 3xx redirects from false-positive span errors per OTel Semantic Conventions v1.26.0.</li>
        <li><b>PR #10076 (Approved by Google maintainer dashpole):</b> Corrected OTLP exporter unmarshaler to support omitted and null endpoints across JSON/YAML decoders per v1.0.0 schema, preventing dialer panics.</li>
        <li><b>PR #10096:</b> Engineered <code>RouteMiddleware</code> in <code>otelhttp</code> to preserve route telemetry across request-cloning middleware; synchronized concurrent access with <code>sync.RWMutex</code>.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">⚡ Meshery (CNCF) / Layer5 — Upstream Contributor</h3>
      <p><b><a href="https://github.com/meshery/meshery">meshery/meshery</a></b> • <i>Go, CLI, Cloud Native Management</i></p>
      <ul>
        <li><b>PR #22724 (Merged into master by maintainer pontusringblom):</b> Eliminated TCP socket and file-descriptor leaks across 5 CLI commands in <code>meshery/meshery</code> via deterministic HTTP response body draining (<code>utils.SafeClose</code>).</li>
        <li><b>PR #26 (Merged):</b> High-performance HTTP benchmarking tooling for Meshery in <code>layer5io/gowrk2</code>.</li>
        <li><b>PR #22 (Merged):</b> Programmatically generated CLI aliases and issue discovery pipelines in <code>layer5io/mesheryctl-aliases</code>.</li>
        <li><b>PR #8276:</b> Official Community Member Profile on Layer5 platform with verified DCO sign-offs.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🏛️ Engineering Cockpit & Blueprint

<div align="center">

| Operational Domain | Technical Focus & Systems Depth |
| :--- | :--- |
| **Distributed Telemetry & Prediction** | Multi-horizon early-warning failure forecasting (5m, 15m, 30m), TreeSHAP feature attributions, Isotonic Calibration, Conformal Prediction. |
| **Autonomous Agent Runtimes** | Terminal-native code editing engines, LSP AST parsing, multi-provider LLM orchestration (Anthropic, OpenAI, OpenRouter, Gemini, Ollama), sandboxed CI/CD. |
| **High-Throughput Backends** | Transactional ACID seat/gatepass allocation engines, PostgreSQL row-level locks (RLS & SELECT FOR UPDATE), POSIX sockets, Redis caching, Celery queues, FastAPI. |
| **Mission-Critical Client Systems** | React 19, TypeScript, responsive incident-response cockpits, low-latency live telemetry streams, offline-resilient local sync. |

</div>

---

### 🚀 Production Flagship Systems

<table>
  <tr>
    <td width="50%">
      <h3 align="left">🏢 LeaveDesk — NIT Uttarakhand Campus Gatepass & Security Engine</h3>
      <p><b>Production Institutional Platform (<a href="https://leavedesk.nituk.ac.in">leavedesk.nituk.ac.in</a>)</b> • <i>Live on Official University Server</i></p>
      <ul>
        <li>Engineered end-to-end leave management and campus perimeter security platform for <b>NIT Uttarakhand</b> (700+ active students & faculty, 99.9% uptime).</li>
        <li><b>Multi-Tier Authorization:</b> Multi-level approval pipeline orchestrating state flow across Students &rarr; Faculty Advisors &rarr; Wardens.</li>
        <li><b>Concurrency & ACID:</b> Enforced state transitions via PostgreSQL row-level locking (<code>SELECT FOR UPDATE</code>) eliminating race conditions under peak traffic.</li>
        <li><b>Dynamic Verification:</b> Cryptographic QR-code validation for physical security checkpoints with anti-replay timestamp verification.</li>
        <li>Automated instant guardian/warden email notifications, dynamic PDF leave pass compilation, and institutional analytics.</li>
      </ul>
      <p><code>PostgreSQL 17</code> • <code>Supabase RLS</code> • <code>TypeScript</code> • <code>React</code> • <code>Tailwind CSS</code> • <code>Vercel</code></p>
    </td>
    <td width="50%">
      <h3 align="left">⚡ NetPredict — Autonomous Network Telemetry Intelligence</h3>
      <p><b>Congestion & Link Failure Forecaster (<a href="https://netpredict-cockpit.vercel.app">Live Cockpit</a> • <a href="https://netpredict-docs.vercel.app/docs">Docs Portal</a>)</b></p>
      <ul>
        <li>Predicts network link congestion and buffer overflow <b>5m, 15m, and 30m in advance</b> before packet loss impacts throughput.</li>
        <li><b>Root-Cause Explainability:</b> Evaluates queue buildup and latency slopes using <b>TreeSHAP</b> feature attribution with Conformal Prediction uncertainty intervals.</li>
        <li><b>Dual Ingestion Engine:</b> Live hardware socket counter polling paired with zero-overhead browser simulation.</li>
        <li>Interactive <i>"What-If"</i> simulation lab allowing operators to test rerouting and buffer adjustments with live feedback.</li>
      </ul>
      <p><code>Python 3.12</code> • <code>FastAPI</code> • <code>React 19</code> • <code>TypeScript</code> • <code>LightGBM</code> • <code>TreeSHAP</code> • <code>Docker</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="left">🤖 Agav — Terminal-Native Autonomous AI Agent</h3>
      <p><b>CLI Coding Assistant for Real Repositories (<a href="https://github.com/prapaa-ai/agav">github.com/prapaa-ai/agav</a>)</b></p>
      <ul>
        <li>Terminal-native agent engineered to inspect, refactor, and test multi-file codebases directly from the CLI.</li>
        <li><b>Multi-Provider Engine:</b> Swappable LLM orchestration supporting Anthropic, OpenAI, OpenRouter, Gemini, and local-first Ollama models with mid-session switching.</li>
        <li>Evaluated on competitive benchmarks including <b>Terminal-Bench 2.1 (84.7%)</b> and SWE-bench Live.</li>
        <li>Sandboxed command execution, automated git branching, AST inspection, and non-interactive CI/CD mode.</li>
      </ul>
      <p><code>Python</code> • <code>TypeScript</code> • <code>Linux PTY</code> • <code>Docker</code> • <code>AST Parsing</code> • <code>LLM Tooling</code></p>
    </td>
    <td width="50%">
      <h3 align="left">🏔️ HimRide — State Transit Scheduling & Fleet Logistics</h3>
      <p><b>High-Concurrency Booking & Dispatch Infrastructure (Govt. of Uttarakhand)</b></p>
      <ul>
        <li>Production multi-tier state transit booking platform coordinating routes, passenger seat reservations, and fleet telematics.</li>
        <li>Engineered low-latency seat matrix allocation with transactional ACID integrity to prevent race conditions during peak travel demand.</li>
        <li>Raised financial settlement throughput 3x (230 &rarr; 695/s) and cut p99 latency 12x (1.8s &rarr; 146ms) via append-only ledger entries.</li>
      </ul>
      <p><code>NestJS</code> • <code>TypeScript</code> • <code>PostgreSQL</code> • <code>Redis Pub/Sub</code> • <code>Uber H3</code> • <code>Expo</code> • <code>Docker Compose</code></p>
    </td>
  </tr>
</table>

---

### 🐍 Real-Time Contribution Telemetry

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/The-AnkitPatel/The-AnkitPatel/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/The-AnkitPatel/The-AnkitPatel/output/snake.svg" />
  <img alt="GitHub Snake Animation" src="https://raw.githubusercontent.com/The-AnkitPatel/The-AnkitPatel/output/snake-dark.svg" width="100%" />
</picture>

</div>

---

### 🛠️ Technical Arsenal

<div align="center">

| Core Infrastructure | Verified Technologies |
| :--- | :--- |
| **Languages** | `Go (Golang)` `C++20` `Python 3.12` `TypeScript` `JavaScript` `SQL` `Bash` |
| **Telemetry & Predictive ML** | `OpenTelemetry` `LightGBM` `TreeSHAP` `Isotonic Calibration` `Conformal Prediction` `PyTorch` `Pandas` |
| **Backend & Cloud Architecture** | `NestJS` `FastAPI` `Node.js` `PostgreSQL 16` `Redis Pub/Sub` `Docker` `Docker Compose` `Nginx` `gRPC` |
| **Frontend & Cockpit Systems** | `React 19` `Tailwind CSS` `Next.js` `Vite` `Chart.js` `Recharts` `Responsive UI/UX` |
| **DevOps & Developer Tooling** | `Git` `GitHub Actions CI/CD` `Linux Internals` `POSIX Sockets` `GDB` `strace` `Playwright` |

</div>

<br/>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=go,cpp,c,python,ts,js,postgres,redis,docker,linux,bash,git,githubactions,fastapi,react,nextjs,tailwind,postman&perline=9&theme=dark" alt="Skills" />
  </a>
</p>

---

### 📊 GitHub Activity Analytics

<div align="center">
  <table border="0" width="100%">
    <tr>
      <td width="50%" align="center">
        <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=The-AnkitPatel&show_icons=true&include_all_commits=true&count_private=true&theme=transparent&hide_border=true&title_color=00E599&text_color=94A3B8&icon_color=00E599" width="100%" alt="GitHub Stats" />
      </td>
      <td width="50%" align="center">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=The-AnkitPatel&theme=transparent&mode=weekly&timezone=Asia/Kolkata&hide_border=true&stroke=00E599&ring=00E599&fire=00E599&currStreakLabel=00E599" width="100%" alt="Streak" />
      </td>
    </tr>
    <tr>
      <td colspan="2" align="center">
        <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=The-AnkitPatel&layout=compact&card_width=800&theme=transparent&hide_border=true&title_color=00E599&text_color=94A3B8" alt="Top Languages" />
      </td>
    </tr>
  </table>
</div>
