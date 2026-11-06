<!--
  GitHub profile README for Parmasanandgarlic
  Drop this file into the Parmasanandgarlic/Parmasanandgarlic repo as README.md
  Animation note: GitHub strips JavaScript and CSS animation, so every moving
  element below is an animated SVG/GIF image service — that's what actually plays.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b2e,55:2f3252,100:31748f&height=190&section=header&text=Michael%20Goulden&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Systems%20architect%20%C2%B7%20AI-agent%20orchestrator%20%C2%B7%20Surrey,%20BC&descAlignY=58&descSize=17" alt="Michael Goulden — systems architect, AI-agent orchestrator, Surrey, BC" width="100%" />

<a href="https://github.com/Parmasanandgarlic">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1100&color=C4A7E7&center=true&vCenter=true&width=720&lines=Founder+of+FarmDash+%E2%80%94+farmdash.one;Preflight+for+autonomous+capital;Zero+custody.+No+private+keys.+Ever.;Discover+%E2%86%92+Simulate+%E2%86%92+Enforce+%E2%86%92+You+sign;I+direct+the+agents.+I+review+and+release+the+work." alt="Founder of FarmDash — preflight for autonomous capital" />
</a>

<br/>

<a href="https://farmdash.one"><img src="https://img.shields.io/badge/FarmDash-farmdash.one-c4a7e7?style=for-the-badge&logoColor=1a1b2e" alt="FarmDash — farmdash.one" /></a>
<a href="https://x.com/SpicoliAndreti"><img src="https://img.shields.io/badge/X-@SpicoliAndreti-242642?style=for-the-badge&logo=x&logoColor=ebbcba" alt="X — @SpicoliAndreti" /></a>
<img src="https://img.shields.io/badge/Based-Surrey%2C%20BC-31748f?style=for-the-badge&logoColor=white" alt="Based in Surrey, BC" />
<img src="https://komarev.com/ghpvc/?username=Parmasanandgarlic&color=9ccfd8&style=for-the-badge&label=Profile%20views" alt="Profile views" />

</div>

> *"Do you have the patience to wait until your mud settles and the water is clear?"* — Lao Tzu

<div align="center">
<table>
<tr>
<td><img src="https://wttr.in/Vancouver.png?m" alt="Weather in Vancouver" /></td>
<td><img src="https://wttr.in/San+Jose+Costa+Rica.png?m" alt="Weather in San Jose, Costa Rica" /></td>
</tr>
</table>
</div>

---

## What I do

I'm a founder and systems architect who builds by directing AI coding agents — I set the product direction and the architecture, spell out the task boundaries and acceptance criteria, then review, integrate, and release the work myself. No inflated claims: if it's listed here, it's shipped or it's labelled as in progress.

- **FarmDash** — zero-custody decision infrastructure for autonomous DeFi agents. My main build, below.
- **Pacific Yew Automations** — automation and agent systems for business workflows.
- **Lilly Lasso** — in progress: a DeFi-specific harness and control room, hosted by Lilly, with the FarmDash tools built in.

My working rules: one canonical source of truth, verified outcomes over reported claims, and explicit approval before scope expands.

---

## 🐴 FarmDash — preflight for autonomous capital

**Zero-custody infrastructure for DeFi agents: map the opportunity, simulate the route, enforce the authority boundary — then the user signs. FarmDash never holds private keys and never takes custody.**

<div align="center">

<a href="https://farmdash.one"><img src="https://img.shields.io/badge/Visit-farmdash.one-f6c177?style=for-the-badge&logoColor=1a1b2e" alt="Visit farmdash.one" /></a>

</div>

FarmDash started as a DeFi airdrop and points tracker. It is now an API, MCP, and OpenClaw platform that gives an autonomous agent a safe way to act on-chain: intelligence and simulation first, execution only inside limits the user set in advance. Think Oregon Trail / Silk Road for agents — scout the trail, check the wagon, *then* roll.

### How an agent uses it

| Stage | What happens |
|---|---|
| **Discover** | Map opportunities across protocols — airdrops, points, yield, routes |
| **Simulate** | Preview the route and its asset changes before anything is signed |
| **Enforce** | Check the action against the user's authority boundaries and policy |
| **Execute** | Prepare the transaction for the user to sign — preparation is not submission, and simulation is not execution |

### The pieces

| Piece | What it does |
|---|---|
| **Trail Heat** | Opportunity intelligence — where the activity, points, and risk actually are |
| **Wagon Steward** | Stewardship layer for positions and routes on the trail |
| **Camp Guard** | The guard at the boundary — policy and safety checks before action |
| **Signal Architect** | Typed yes/no signals an agent can act on, instead of vibes |
| **Strategy Objects / FarmDashIntent** | A strategy expressed as a typed, signable intent — not a blank cheque |
| **Evidence model** | Every reading is labelled observed, derived, stale, or unavailable — and the system fails closed when it doesn't know |

### FarmDash by the numbers

| | |
|---|---|
| MCP tools | **94** — MCP server v5.0.0, stdio |
| OpenClaw skills | **10** |
| Protocols covered | **80** |
| OpenAPI operations | **54** primary · **75** across four documents |
| Invariants | **73** |

### Standards, simulation, and payments

- **Signing and intent:** EIP-191 / EIP-712 typed signatures, ERC-8196, Strategy Objects and FarmDashIntent
- **Simulation:** Alchemy `simulateAssetChanges` — see the balance changes before you sign
- **Agent commerce:** x402 and ACP — information calls are priced cheap, about **$0.01–$0.50**, with execution economics kept separate
- **Surfaces:** REST API, MCP tools, and OpenClaw skills, with TypeScript and Python agent kits
- **Site stack:** Vercel hosting, Supabase database

<div align="center">

<img src="https://img.shields.io/badge/TypeScript-31748f?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Python-242642?style=for-the-badge&logo=python&logoColor=f6c177" alt="Python" />
<img src="https://img.shields.io/badge/MCP-94_tools-c4a7e7?style=for-the-badge&logoColor=1a1b2e" alt="MCP — 94 tools" />
<img src="https://img.shields.io/badge/OpenAPI-75_ops-9ccfd8?style=for-the-badge&logo=openapiinitiative&logoColor=1a1b2e" alt="OpenAPI — 75 operations" />
<img src="https://img.shields.io/badge/Vercel-1a1b2e?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
<img src="https://img.shields.io/badge/Supabase-2f3252?style=for-the-badge&logo=supabase&logoColor=9ccfd8" alt="Supabase" />

</div>

> **Tool discovery does not equal execution authority.** An agent finding a tool is not an agent being allowed to use it — that distinction is the whole product.

---

## 🤠 Next: Lilly Lasso — the control room

Lilly Lasso is the DeFi-specific harness I'm building next, branded like *Big Shot* from Cowboy Bebop — bounty-board energy, a host who runs the board. Lilly is the character and host; the control room *is* the harness. The end goal is simple to say and hard to build: **every FarmDash tool, built into the harness** — discover, simulate, and enforce from one seat, with Lilly calling the board.

*Status: in design / early build. See you, space cowboy.*

---

## Also building

- **Pacific Yew Automations** — automation and agent systems across the tools businesses already run: Jobber, ServiceTitan, HubSpot, Attio, QuickBooks, and Sage, with human approval gates where money or customers are involved.
- **AutoPromo** — a sellable desktop product for promotion workflows, including the open-source Community Edition pinned below.

## How I build

I orchestrate a small fleet instead of pretending to be a 20-person team:

<div align="center">

<img src="https://img.shields.io/badge/Hermes-coding_agent-242642?style=for-the-badge&logoColor=c4a7e7" alt="Hermes" />
<img src="https://img.shields.io/badge/OpenCode-coding_agent-242642?style=for-the-badge&logoColor=c4a7e7" alt="OpenCode" />
<img src="https://img.shields.io/badge/Codex-coding_agent-242642?style=for-the-badge&logoColor=c4a7e7" alt="Codex" />
<img src="https://img.shields.io/badge/Antigravity-coding_agent-242642?style=for-the-badge&logoColor=c4a7e7" alt="Antigravity" />
<img src="https://img.shields.io/badge/Direction_%2B_review-me-ebbcba?style=for-the-badge&logoColor=1a1b2e" alt="Direction and review — me" />

</div>

Precise instructions, one canonical checkout, clean worktree hygiene, no waiting loops, and no dependence on GitHub Actions. Publishing and directory claims stay aligned with shipped source truth — if the listing says it, the code does it.

---

## Pinned work

| Project | What it is |
|---|---|
| [AutoPromo-CommunityEdition](https://github.com/Parmasanandgarlic/AutoPromo-CommunityEdition) | Open-source edition that runs locally on your machine, for individuals managing a single account. TypeScript. |
| [arcademinter](https://github.com/Parmasanandgarlic/arcademinter) | Generate custom vanity addresses on Solana and EVM chains, with AWS KMS-secured minting. JavaScript. |
| [deadlockmatchtutor](https://github.com/Parmasanandgarlic/deadlockmatchtutor) | Deadlock AfterMatch — a production-grade, open-source analytics engine that turns raw match data from Valve's Deadlock into actionable intelligence for players, coaches, and developers. JavaScript. |
| [wallet-rescue](https://github.com/Parmasanandgarlic/wallet-rescue) | Emergency toolkit for recovering a crypto wallet compromised via an EIP-7702 delegation attack — multi-chain delegation revocation, sweeper-bot bypass, ERC-20 approval cleanup, and more. JavaScript. |

---

## GitHub, animated

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Parmasanandgarlic&show_icons=true&hide_border=true&title_color=c4a7e7&icon_color=f6c177&text_color=ebbcba&bg_color=1a1b2e" alt="Michael's GitHub stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Parmasanandgarlic&layout=compact&hide_border=true&title_color=c4a7e7&text_color=ebbcba&bg_color=1a1b2e" alt="Most used languages" height="165" />

<br/>

<img src="https://streak-stats.demolab.com?user=Parmasanandgarlic&theme=transparent&hide_border=true&stroke=c4a7e7&ring=f6c177&fire=f6c177&currStreakLabel=c4a7e7&sideLabels=9ccfd8&currStreakNum=ffffff&sideNums=ffffff&dates=ebbcba" alt="GitHub contribution streak" />

</div>

<!-- Snake: this image appears after you add the one-time Action in the setup note at the bottom of this file. Until then it renders as a broken image — delete these three lines if you don't want it. -->
<div align="center">
<img src="https://raw.githubusercontent.com/Parmasanandgarlic/Parmasanandgarlic/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake animation" width="100%" />
</div>

---

## Find me

<div align="center">

<a href="https://farmdash.one"><img src="https://img.shields.io/badge/Web-farmdash.one-c4a7e7?style=for-the-badge&logoColor=1a1b2e" alt="farmdash.one" /></a>
<a href="https://x.com/SpicoliAndreti"><img src="https://img.shields.io/badge/X-@SpicoliAndreti-242642?style=for-the-badge&logo=x&logoColor=ebbcba" alt="X — @SpicoliAndreti" /></a>
<a href="https://github.com/Parmasanandgarlic"><img src="https://img.shields.io/badge/GitHub-Parmasanandgarlic-31748f?style=for-the-badge&logo=github&logoColor=white" alt="GitHub — Parmasanandgarlic" /></a>

<p><em>SpicoliAndreti, everywhere else :)</em></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b2e,55:2f3252,100:31748f&height=110&section=footer" alt="" width="100%" />

</div>

<!--
  SETUP NOTE — the snake (delete this comment after setup, or keep it, it's invisible)

  1. In the Parmasanandgarlic/Parmasanandgarlic repo, create:
     .github/workflows/snake.yml
  2. Paste this in:

     name: Generate snake animation
     on:
       schedule: [{ cron: "0 0 * * *" }]
       workflow_dispatch:
     jobs:
       generate:
         runs-on: ubuntu-latest
         permissions: { contents: write }
         steps:
           - uses: Platane/snk/svg-only@v3
             with:
               github_user_name: Parmasanandgarlic
               outputs: |
                 dist/github-contribution-grid-snake-dark.svg?palette=github-dark
           - uses: crazy-max/ghaction-github-pages@v4
             with:
               target_branch: output
               build_dir: dist
             env:
               GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  3. Run it once from the Actions tab (workflow_dispatch), and the snake above goes live.
     Note: Michael's own rule is no dependence on GitHub Actions for his product repos —
     this one is only a profile decoration, regenerated daily.
-->
