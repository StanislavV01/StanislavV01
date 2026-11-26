<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F00FF,100:00D4FF&height=200&section=header&text=Stanislav%20Verbytskyi&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20Full-stack%20TypeScript&descAlignY=58&descSize=18" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=A855F7&center=true&vCenter=true&width=620&lines=Building+LLM-powered+products+end+to+end;AI+agents+%E2%80%A2+RAG+%E2%80%A2+tool+use+%E2%80%A2+MCP;React+%E2%80%A2+Next.js+%E2%80%A2+Node.js+%E2%80%A2+Web3;From+prototype+to+production" alt="Typing SVG" /></a>

<br/>

[![Email](https://img.shields.io/badge/Email-verbytskiystanislav%40gmail.com-A855F7?style=for-the-badge&logo=gmail&logoColor=white)](mailto:verbytskiystanislav@gmail.com)
![Location](https://img.shields.io/badge/Warsaw-Poland-00D4FF?style=for-the-badge&logo=googlemaps&logoColor=white)
![Open to work](https://img.shields.io/badge/Open_to-AI_roles-22C55E?style=for-the-badge)

</div>

---

## ⚡ About me

```ts
const stanislav = {
  role: "AI Engineer · Full-stack TypeScript",
  location: "Warsaw, Poland 🇵🇱",
  building: ["LLM apps", "AI agents", "RAG pipelines", "MCP servers"],
  background: ["React", "React Native", "Next.js", "Node.js", "Web3 / DeFi"],
  superpower: "taking AI features from demo to production",
  openTo: "AI / full-stack AI roles — remote EU or hybrid Warsaw",
};
```

I ship products end to end: the model integration, the backend that keeps it reliable, and the UI people actually use. Years of production web, mobile and Web3 work mean my AI features come with typed APIs, tests and clean deploys — not just a demo.

---

## ⚓ Flagship: [seaworthy](https://github.com/StanislavV01/seaworthy)

> **Your coding agent says "done". seaworthy checks.**

Deterministic quality gates for coding agents — a **Claude Code plugin** and an **Orca extension**. Agents end their turn with "done!" while tests fail, CI is red or a failing test was quietly skipped. seaworthy turns "please run the tests" from a prompt into a gate:

- ✅ your project's own checks must pass **for the exact code** being committed and pushed
- 🛡 diff-guard blocks deleted/skipped tests, `@ts-ignore`, loosened configs — until *you* approve
- 👀 an independent reviewer agent, pinned to the same code, must approve
- 🔁 CI watched until green, failures excerpted with secrets redacted, retries capped
- 🔒 enforced by hooks + git hooks + signed state — **81 red-team bypass attempts blocked**, incl. 24 found by an independent review

[![CI](https://github.com/StanislavV01/seaworthy/actions/workflows/ci.yml/badge.svg)](https://github.com/StanislavV01/seaworthy) ![tests](https://img.shields.io/badge/tests-285_passing-3fb950?style=flat-square) ![deps](https://img.shields.io/badge/runtime_deps-0-blue?style=flat-square)

`Claude Code` `Orca` `hooks` `agent safety` `JS/TS · C++ · Python · Go`

---

## 🚧 Building now

| | Project | What it does | Stack |
|---|---|---|---|
| 🤖 | [**DeFi Agent**](https://github.com/StanislavV01/defi-agent) ![MVP](https://img.shields.io/badge/MVP-A855F7?style=flat-square) | AI agent that reads your Aave positions, explains risk in plain language and prepares transactions for you to sign | TypeScript · LLM tool calling · viem · Next.js |
| 📚 | **Docs RAG** | Ask questions over any documentation, get answers with citations to the exact source | Next.js · embeddings · pgvector · streaming |

<sub>⭐ Star or watch to follow along.</sub>

---

## 🏆 Shipped

### [🔌 defi-mcp](https://github.com/StanislavV01/defi-mcp) &nbsp;![new](https://img.shields.io/badge/new-A855F7?style=flat-square) ![CI](https://github.com/StanislavV01/defi-mcp/actions/workflows/ci.yml/badge.svg)
MCP server that gives Claude, Cursor or any AI agent read-only eyes on DeFi: Aave V3 positions, markets across 5 chains, and **what-if health-factor simulation** before anyone signs a transaction. Typed tools, multicall reads, unit-tested risk math.

`MCP` `TypeScript` `viem` `zod` `AI agents`

<table>
<tr>
<td width="50%" valign="top">

### [🏦 aave-position-builder](https://github.com/StanislavV01/aave-position-builder)
Opens a collateralized Aave V3 borrow on Base in **one transaction**, sized to a target health factor, with eMode detection. Server-side RPC proxy keeps keys out of the browser, live position events over WebSocket.

`React` `wagmi` `viem` `Fastify` `WebSocket` `Vitest`

</td>
<td width="50%" valign="top">

### [🔄 DeX-app](https://github.com/StanislavV01/DeX-app)
Decentralized exchange front end running against mainnet.

`React` `TypeScript` `Vite`

[**▶ Live demo**](https://de-x-app.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [📦 my-turborepo](https://github.com/StanislavV01/my-turborepo)
Monorepo with shared packages and a deployed web app.

`Turborepo` `Next.js` `TypeScript`

[**▶ Live demo**](https://my-turborepo-webapp-smoky.vercel.app)

</td>
<td width="50%" valign="top">

### [📱 react-native-custom-template](https://github.com/StanislavV01/react-native-custom-template)
Opinionated starter for new React Native apps.

`React Native` `TypeScript`

</td>
</tr>
</table>

---

## 🛠 Tech stack

<div align="center">

**AI / LLM**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Vercel AI SDK](https://img.shields.io/badge/AI_SDK-000000?style=for-the-badge&logo=vercel&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-6366F1?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-0EA5E9?style=for-the-badge)
![Agents](https://img.shields.io/badge/AI_Agents-F97316?style=for-the-badge)

**Core**

<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,express,postgres,mongodb,redux,vite&perline=10" />

**Infra & tooling**

<img src="https://skillicons.dev/icons?i=aws,docker,vercel,git,github,pnpm,vitest&perline=10" />

</div>

---

## 📊 GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=StanislavV01&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=StanislavV01&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=StanislavV01&theme=tokyo-night&hide_border=true&area=true" width="100%" />

</div>

---

<div align="center">

**Let's build something smart together** 🚀

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D4FF,100:7F00FF&height=100&section=footer" />

</div>
