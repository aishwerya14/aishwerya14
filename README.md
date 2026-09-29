<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F2937,100:4F46E5&height=190&section=header&text=Aishwerya&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Senior%20Frontend%20%2F%20Full-Stack%20Engineer&descAlignY=58&descSize=18" alt="Aishwerya — Senior Frontend / Full-Stack Engineer" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=20&pause=1200&color=4F46E5&center=true&vCenter=true&width=720&lines=Frontend+platforms+built+for+scale;Production+AI+and+agentic+systems;React+%E2%80%A2+TypeScript+%E2%80%A2+Next.js+%E2%80%A2+Node.js+%E2%80%A2+GraphQL" alt="Focus areas" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aishwerya/"><img src="https://img.shields.io/badge/LinkedIn-aishwerya-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://img.shields.io/badge/Experience-6%2B%20years-4F46E5?style=flat" alt="6+ years" />
  <img src="https://img.shields.io/badge/MS-Information%20Systems%20Management-1F2937?style=flat" alt="MS" />
</p>

---

## About

I'm a senior engineer with 6+ years of experience building frontend platforms and full-stack products. I care about the parts users never notice but always feel: rendering performance, accessible components, predictable state, and API contracts that let teams move independently.

More and more of my work is in **AI and agentic systems**. I design agent workflows with LangGraph, the OpenAI SDK, and the Model Context Protocol (MCP), and I build them to production standards: typed, observable, testable, and integrated into the product experience.

---

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,ts,nextjs,vue,js,html,css,tailwind&theme=dark" alt="Frontend" /><br/>
  <img src="https://skillicons.dev/icons?i=nodejs,graphql,jest,aws,azure,docker,git&theme=dark" alt="Backend and infrastructure" />
</p>

| Area | Technologies |
|---|---|
| **Frontend** | React, TypeScript, Next.js, Vue.js, design systems, accessibility, web performance |
| **Backend & APIs** | Node.js, GraphQL, REST, serverless (AWS Lambda) |
| **AI / Agentic** | LangGraph, OpenAI SDK, Model Context Protocol (MCP), tool calling, evaluation |
| **Cloud & Delivery** | AWS, Azure, Docker, CI/CD, Jest |

---

## How I architect AI features

```mermaid
flowchart LR
    UI["React / Next.js UI"] --> API["Node.js · GraphQL"]
    API --> ORCH["LangGraph orchestrator"]
    ORCH --> LLM["LLM · OpenAI SDK"]
    ORCH --> MCP["MCP tool servers"]
    MCP --> DATA[("Internal APIs & data")]
    ORCH --> OBS["Tracing · evals · guardrails"]
    ORCH -- "streamed, typed results" --> API
```

The model is just one component. The engineering work lives in the parts around it: typed tool contracts, streaming UI, fallbacks, and evaluation.

---

## Engineering principles

<details>
<summary><b>Performance is a product feature</b></summary>
<br/>

Profile before optimizing. Most React performance problems come from where state lives, not from missing `useMemo`. I track Core Web Vitals and interaction latency as first-class metrics, with budgets enforced in CI.

</details>

<details>
<summary><b>Treat LLMs as unreliable I/O</b></summary>
<br/>

Every model call gets schema-validated outputs, timeouts, retries, and a deterministic fallback path. Agent behavior is covered by evals and traces, so a regression gets caught before a user sees it.

</details>

<details>
<summary><b>Platforms win on adoption, not component count</b></summary>
<br/>

A design system or shared frontend platform is only as good as its developer experience: clear APIs, strong typing, documentation, and a migration path. I optimize for the teams who consume it.

</details>

<details>
<summary><b>Contracts before code</b></summary>
<br/>

A well-designed GraphQL schema or MCP tool interface lets frontend, backend, and AI work proceed in parallel. I invest early in the interface, because it outlives the implementation.

</details>

---

## Currently focused on

- Agentic workflows that are **reliable in production**, not just impressive in demos
- Frontend architecture for **streaming, AI-driven interfaces**
- Scalable component systems and **developer experience**

---

<p align="center">
  Open to conversations about frontend architecture, AI systems, and engineering leadership.<br/>
  <a href="https://www.linkedin.com/in/aishwerya/"><b>Connect on LinkedIn →</b></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4F46E5,100:1F2937&height=110&section=footer" alt="" />
</p>
