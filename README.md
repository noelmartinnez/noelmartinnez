<!-- ═══════════════════════════════════════════════════════════════
     noelmartinnez · profile runtime v2026.09
     This README is rendered as an agent trace. Read it top to bottom.
     ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0d1117,50:1f6feb,100:8957e5&text=noel.martinez&fontColor=e6edf3&fontSize=52&fontAlignY=38&desc=backend%20%C2%B7%20applied%20AI%20%C2%B7%20production%20LLM%20systems&descAlignY=60&descSize=16&animation=fadeIn" width="100%" />

<a href="https://noelmartinez.es">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&multiline=false&width=620&lines=%3E+initializing+agent%3A+noel.martinez;%3E+loading+context%3A+backend+%2B+LLMs+in+production;%3E+tools%3A+python%2C+java%2C+docker%2C+postgres%2C+llms;%3E+status%3A+ready.+awaiting+your+prompt_" alt="typing" />
</a>

<br/>

<a href="https://noelmartinez.es"><img src="https://img.shields.io/badge/web-noelmartinez.es-0d1117?style=for-the-badge&logo=googlechrome&logoColor=58a6ff&labelColor=0d1117" /></a>
<a href="https://linkedin.com/in/noelmartinezpomares"><img src="https://img.shields.io/badge/linkedin-noelmartinezpomares-0d1117?style=for-the-badge&logo=linkedin&logoColor=58a6ff&labelColor=0d1117" /></a>
<img src="https://img.shields.io/badge/based_in-Alicante,_ES-0d1117?style=for-the-badge&logo=googlemaps&logoColor=58a6ff&labelColor=0d1117" />

</div>

---

### `▍ system_prompt`

```yaml
agent: noel.martinez
role: Backend Software Engineer
specialization: applied AI — LLMs that have to survive production, not just demos
languages: [es-ES (native), en (training daily 🏋️)]
principles:
  - boring infra, clever product
  - if it's not observable, it's not deployed
  - measure the model, don't trust the vibe
  - consistency > intensity   # learned this under a barbell, applies to code too
```

---

### `▍ trace` &nbsp; <sub>click each step to expand</sub>

<details>
<summary><code>🛠️ tool_call → experience.query(sort="recent")</code></summary>
<br/>

```json
[
  {
    "company": "Fundamentia",
    "role": "Backend Software Engineer",
    "period": "2025-03 → 2026-08",
    "shipped": [
      "SimplyData — Intelligent Document Processing running in production at major Spanish banks",
      "Lead backend dev on a European project: AI/LLM-powered entity anonymization"
    ],
    "context": "mission-critical, regulated, zero tolerance for silent failures"
  },
  {
    "company": "Altia",
    "role": "Backend & Infrastructure Engineer",
    "period": "2024-09 → 2025-03"
  },
  {
    "education": "BSc Computer Engineering — Universidad de Alicante",
    "thesis": "9/10"
  }
]
```

</details>

<details>
<summary><code>🧠 tool_call → architecture.render("how I think about LLM pipelines")</code></summary>
<br/>

```mermaid
flowchart LR
    A[📄 raw documents] --> B[ingest + OCR]
    B --> C{router}
    C -->|structured| D[deterministic parsers]
    C -->|messy| E[LLM extraction]
    E --> F[schema validation]
    D --> F
    F -->|fail| G[retry / fallback / human review]
    F -->|pass| H[(PII anonymization)]
    H --> I[📊 evals + observability]
    I --> J[✅ production API]
    G --> C
```

> [!NOTE]
> The LLM is one box in the diagram. Everything around it is what makes it shippable.

</details>

<details>
<summary><code>🧰 tool_call → stack.list()</code></summary>
<br/>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,spring,fastapi,postgres,redis,docker,kubernetes,linux,git,githubactions,azure&perline=6&theme=dark" />
</p>

`llms` · `rag` · `structured outputs` · `evals` · `pii anonymization` · `document ai` · `rest apis` · `ci/cd`

</details>

<details>
<summary><code>🔭 tool_call → now.get()</code></summary>
<br/>

```diff
+ building personal projects around agents, evals and document AI
+ going deeper on distributed systems and LLM infra
+ english: daily reps, same as the gym
! open to conversations: backend with real applied AI, Alicante/Elche, hybrid or remote
```

</details>

<details>
<summary><code>🏋️ tool_call → offline_mode.status()</code></summary>
<br/>

```text
┌──────────────────────────────────────────────┐
│  when not shipping code: training.            │
│  same rules apply → progressive overload,     │
│  recovery, no skipped sessions.               │
│  most of my best debugging happens mid-set.   │
└──────────────────────────────────────────────┘
```

</details>

---

### `▍ telemetry`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/noelmartinnez/noelmartinnez/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/noelmartinnez/noelmartinnez/output/github-snake.svg" width="90%" alt="contribution snake" />
</picture>

</div>

---

### `▍ user_input`

<div align="center">

Got a question, an idea or a role? Prompt me directly — it opens an issue in this repo and I answer every one.

<a href="https://github.com/noelmartinnez/noelmartinnez/issues/new?title=%5Bprompt%5D%20&body=Hi%20Noel%2C%20">
  <img src="https://img.shields.io/badge/▶_send_a_prompt-1f6feb?style=for-the-badge&logoColor=white" />
</a>

<br/><br/>

<sub><code>response.finish_reason = "stop"</code> · tokens well spent · thanks for reading</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:8957e5,50:1f6feb,100:0d1117" width="100%" />

</div>
