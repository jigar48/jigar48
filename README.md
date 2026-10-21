<div align="center">

<img src="1790136052252.jpg" alt="Jigar Prajapati: Intelligent Automation Solutions" width="100%"/>

# Jigar Prajapati

<a href="https://github.com/jigar48"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=4DA3FF&center=true&vCenter=true&width=700&lines=AI+agents+and+LLM+workflows+that+finish+the+task;Automation+and+RPA+that+replace+manual+work;Cloud+on+AWS%2C+containers+with+Docker+and+Podman;E-commerce+and+API+integrations+that+don%27t+fall+over" alt="Typing intro" /></a>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/buildaiwith-jigar-prajapati)
[![Upwork](https://img.shields.io/badge/Upwork-hire_me-14A800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/jigarprajapati4)
[![Portfolio](https://img.shields.io/badge/Portfolio-view_site-4da3ff?style=for-the-badge&logo=githubpages&logoColor=white)](https://jigar48.github.io/automatewithjigar/)
![Location](https://img.shields.io/badge/Ahmedabad-India-FF9933?style=for-the-badge&logo=googlemaps&logoColor=white)
![Status](https://img.shields.io/badge/Freelance-open_to_projects-4da3ff?style=for-the-badge)

</div>

---

## 👋 About me

```python
class Jigar:
    day_job    = "AI agents, automation, and cloud-backed integrations for businesses"
    night_job  = "Trading tools, SaaS side-products, and open-source dev utilities"
    since      = 2017   # started my own IT services company, freelancing since 2021
    philosophy = "If I do it twice, I script it. If I do it three times, I ship it."

    def currently(self):
        return [
            "wiring LLMs into real business workflows (not demo toys)",
            "building tools that catch breakage before customers do",
            "shipping small, useful dev utilities in public",
        ]

    def ask_me_about(self):
        return ["LLM routing across multiple models", "browser automation with Playwright",
                "AWS architecture and deployments", "FastAPI backends",
                "e-commerce platform integrations", "pharmacy system integrations"]
```

## ⚙️ What I build

| Lane | What it looks like |
|---|---|
| 🤖 **AI & agents** | LLM workflows, multi-model routing, agents that actually finish the task |
| 🔁 **Automation / RPA** | Playwright bots, scrapers, schedulers, alerting pipelines |
| ☁️ **Cloud & DevOps** | AWS (Lambda, SES, EventBridge, Auto Scaling, IAM, VPC networking), containers with Docker and Podman, Linux servers, CI/CD |
| 🔌 **APIs & backends** | FastAPI services, SQL, WebSocket feeds, third-party integrations that stay up |
| 💊 **Healthcare integrations** | Pharmacy management system (PMS) connectors, CRM sync, workflow bots |
| 📈 **Trading tooling** | Option-chain collectors, signal engines, dashboards, alerting |
| 🛒 **E-commerce** | Custom features and integrations on Adobe Commerce, Shopify, WooCommerce and Odoo |

## 🗂️ Selected work

Most of what I've built lives in private repositories, either for clients or as personal products. Here is what's inside. Happy to walk through architecture and demos on a call.

### 🧠 AI products & agents
- **Parenting advisor app (prototype)**: a multi-LLM routing backend that sends each question to the best-suited model, with a dashboard on top.
- **LLM workflow automation**: agents and pipelines that connect models to business tools, built for client teams.

<p align="center">
<img src="ai-routing.png" alt="Multi-LLM routing diagram" width="90%"/><br/>
<sub>Illustrative diagram, sample data only.</sub>
</p>

### 📣 Content & social automation
- **Instagram content engine**: generates captions, ranked hook options and branded images with an LLM (Groq, Llama 3.3 70B) and Pillow, then publishes single images, carousels and reels through the Instagram Graph API. Posts go through a review dashboard (FastAPI), and a cron-based autopilot publishes approved posts on schedule. Reach, saves and engagement are tracked per content pillar.
- **Shorts Factory**: a faceless YouTube Shorts pipeline: idea, script, scene plan, AI visuals, voice, assembly with kinetic captions, thumbnail and upload. Each stage waits for human approval, and runs resume from the last good step. Runs on FastAPI with SQLite and zero-cost defaults.
- **LinkedIn agent**: scrapes a profile, suggests improved content for review, applies approved changes with Playwright, plans a weekly posting strategy, generates branded visuals and auto-posts.

<p align="center">
<img src="instagram-engine.png" alt="Instagram content engine" width="90%"/>
</p>

<p align="center">
<img src="shorts-factory.png" alt="Shorts Factory pipeline" width="90%"/>
</p>

<p align="center">
<img src="linkedin-agent.png" alt="LinkedIn agent" width="90%"/>
</p>
<p align="center"><sub>Illustrative diagrams, sample data only.</sub></p>

### ☁️ Cloud & infrastructure
- **AWS**: serverless and scheduled workloads with Lambda and EventBridge, email delivery with SES, scaling with Auto Scaling, and secure networking with IAM, security groups and NAT.
- **Containers**: Docker and Podman setups for repeatable local, staging and production environments.

<p align="center">
<img src="aws-architecture.png" alt="AWS reference architecture" width="90%"/><br/>
<sub>Illustrative diagram, sample data only.</sub>
</p>

### 💊 Healthcare & pharmacy platforms
- **Pharmacy management system**: end-to-end platform work for a pharmacy business with 400+ stores, integrating multiple pharmacy management systems (PMS) including Pioneer and Liberty.
- **GoHighLevel (GHL) integrations**: syncing pharmacy and customer data with GHL for CRM and marketing automation.
- **RPA bots**: automation that handles repetitive pharmacy-side workflows end to end.

<p align="center">
<img src="pharmacy-integration.png" alt="Pharmacy systems integration diagram" width="90%"/><br/>
<sub>Illustrative diagram, sample data only.</sub>
</p>

### 📈 Trading & market data
*Personal research tools, not financial advice.*

<p align="center">
<img src="pulse-dashboard.png" alt="Illustrative mock-up of the Pulse dashboard" width="90%"/><br/>
<sub>Illustrative mock-up of the Pulse dashboard, sample data only.</sub>
</p>

- **Pulse**: a SENSEX daily directional-bias engine that scores seven public market signals into one composite bias, with a VIX gate and a second confidence-based shadow gate shown side by side. A paper-trading engine runs six averaging and sizing variants against the same entry and logs every cycle to SQLite, with a FastAPI dashboard. No broker API, free public data, paper trading only.
- **Theta Desk**: a SENSEX options-selling platform with live Greeks, a WebSocket feed, and Telegram alerts.
- **Theta Vault**: an option-chain snapshot collector built on Angel One SmartAPI, with a FastAPI dashboard.
- **NIFTY signal engine**: a signal generator that reads NSE option-chain data.
- **Option-chain strategy runner**: a NIFTY strategy that polls NSE's option-chain API.
- **Swing trading algo**: a rules-based swing-trading system for systematic entries and exits.

### 🛒 E-commerce platforms
Work across several platforms: Adobe Commerce (formerly Magento), Shopify, WooCommerce and Odoo. The harder Adobe Commerce builds:
- **Custom box studio**: a storefront experience where customers design their own custom box.
- **WhatsApp sticker integration**: connecting a WhatsApp sticker flow to the store.
- **Smart alert dashboard**: a dashboard that surfaces store alerts in one place.
- **Smart shipping rates for boxes**: shipping rates calculated for custom box orders.
- **Mobile OTP login**: phone-number sign-in over SMS (MSG91) for an Indian store.
- **Pharmacy network**: managing 400+ pharmacy stores.
- **Also**: DPDPA consent and multi-store routing, order and invoice fixes, containerised dev environments.

<p align="center">
<img src="commerce-builds.png" alt="Overview of complex e-commerce builds" width="90%"/>
</p>

<p align="center">
<img src="commerce-otp-flow.png" alt="Mobile OTP login flow" width="90%"/><br/>
<sub>Illustrative diagram, sample data only.</sub>
</p>

## 🧭 How I work

1. **Understand the process.** I map what your team does by hand today and where it loses time.
2. **Prototype fast.** A working version first, so you can react to something real.
3. **Harden and ship.** Error handling, logging, retries, alerts, and a handover you can run without me.
4. **Monitor.** Automation that fails silently is worse than none, so I build in alerts.

## 🛤️ Journey

| When | What |
|---|---|
| **2017** | Founded an IT services company and started delivering client projects |
| **2021 → now** | Freelance engineer: AI automation, pharmacy platforms, cloud deployments, and e-commerce stores for clients |
| **Now** | Moving deeper into AI agents, LLM workflows, and AI-powered SaaS |

## 🧰 Tech stack

<p>
<img src="https://skillicons.dev/icons?i=python,fastapi,ts,js,php,mysql,aws,docker,linux,git,githubactions,nginx" alt="Tech icons" />
</p>

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white)
![Adobe Commerce](https://img.shields.io/badge/Adobe_Commerce-FA0F00?style=flat-square&logo=adobe&logoColor=white)
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=flat-square&logo=woocommerce&logoColor=white)
![Shopify](https://img.shields.io/badge/Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white)
![Odoo](https://img.shields.io/badge/Odoo-714B67?style=flat-square&logo=odoo&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_%26_WebSocket_APIs-0d1117?style=flat-square&logo=fastapi&logoColor=4da3ff)
![RPA](https://img.shields.io/badge/RPA-0d1117?style=flat-square&logo=probot&logoColor=4da3ff)

## 🔭 Open-source tools I've shipped

- **[api-contract-diff](https://github.com/jigar48/api-contract-diff)**: catches removed endpoints, dropped response fields, and type changes between OpenAPI specs. CLI with readable reports and CI-friendly exit codes.

<p align="center">
<img src="oss-api-contract-diff.png" alt="Illustrative diagram of api-contract-diff" width="75%"/>
</p>

- **[checkout-canary](https://github.com/jigar48/checkout-canary)**: a config-driven Playwright monitor that walks a store from home page to the payment step on a GitHub Actions schedule. It alerts via Telegram, Slack or email and publishes a green/red status page with failure screenshots on GitHub Pages. Free, no server needed, with Adobe Commerce and WooCommerce presets.

<p align="center">
<img src="oss-checkout-canary.png" alt="Illustrative diagram of checkout-canary" width="75%"/>
</p>

- **[agent-gauntlet](https://github.com/jigar48/agent-gauntlet)**: a deterministic, no-LLM audit of a store's checkout journey. It runs the way an AI shopping agent does, with no human-like pauses, and reports where the journey breaks (early-action races, click-blocking overlays, login walls, bot challenges) with screenshots as evidence. It stops before payment and never places an order. Python and Playwright, early release (v0.1.0), MIT licensed.

<p align="center">
<img src="oss-agent-gauntlet.png" alt="Illustrative diagram of agent-gauntlet" width="75%"/>
</p>

- **[contact-cta-inspector](https://github.com/jigar48/contact-cta-inspector)**: a privacy-first Chrome extension (Manifest V3, TypeScript) that checks WhatsApp, phone and email links on a page for format problems, keeps general link observations separate, suggests fixes and copies a redacted report. Offline and deterministic: no network calls, accounts or analytics. MIT licensed.

<p align="center">
<img src="oss-contact-cta-inspector.png" alt="Illustrative diagram of contact-cta-inspector" width="75%"/>
</p>

- **[agent-risk-annotator](https://github.com/jigar48/agent-risk-annotator)**: local-first risk annotations for AI-agent-generated diffs. It prints one line per risky hunk (sensitive paths, deleted tests, fix-prone files, uncovered code, new dependencies, lockfile drift) so a reviewer knows where to look first. Rule-based, deterministic, no network calls. Ships as a TypeScript CLI, a Claude Code plugin and a GitHub Action. MIT licensed.

<p align="center">
<img src="oss-agent-risk-annotator.png" alt="Illustrative diagram of agent-risk-annotator" width="75%"/>
</p>

- **[awi (Agent Workflow Inspector)](https://github.com/jigar48/awi)**: an offline, deterministic linter for AI agent traces. It reads AWI JSON or OpenTelemetry exports and flags retry storms, repeated failing tool calls, execution cycles, runaway delegation and resource burn, with exit codes for CI gating. No accounts, LLM keys or network access. TypeScript, 1.0.0 release candidate, MIT licensed.

<p align="center">
<img src="oss-awi.png" alt="Illustrative diagram of Agent Workflow Inspector" width="75%"/>
</p>

- **[mcp-agent-mesh](https://github.com/jigar48/mcp-agentmesh)**: a single-file multi-agent pipeline for the terminal. An architect, a coder and a security auditor sub-agent work on a task using Gemini, with OWASP-based findings, a 0 to 100 score and an optional refine pass. Runs are saved locally in SQLite, and a mock mode runs without an API key. Python, MIT licensed.

<p align="center">
<img src="oss-mcp-agentmesh.png" alt="Illustrative diagram of mcp-agent-mesh" width="75%"/>
</p>

- **[logpulse-ai](https://github.com/jigar48/logpulse-ai)**: a terminal log debugger and incident copilot. It reads piped logs, a file, or a wrapped command that failed, masks listed secret and PII patterns locally, then asks Gemini for a root cause and a ready-to-apply git diff, and can export a post-mortem in Markdown. Python, MIT licensed.

<p align="center">
<img src="oss-logpulse-ai.png" alt="Illustrative diagram of logpulse-ai" width="75%"/>
</p>


<a href="https://buymeacoffee.com/buildwithjigar"><img src="https://img.shields.io/badge/Buy_me_a_coffee-support_open_source-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy me a coffee"/></a>

## 📊 GitHub activity

<p align="center">
<img src="https://streak-stats.demolab.com?user=jigar48&theme=dark&hide_border=true" alt="GitHub streak" height="150" />
</p>

## 🤝 Work with me

I take on freelance projects in AI automation, cloud and API integrations, and e-commerce platforms. If you have a repetitive process eating your team's week, or systems that need to talk to each other, see my [portfolio site](https://jigar48.github.io/automatewithjigar/), or reach out on [Upwork](https://www.upwork.com/freelancers/jigarprajapati4) or [LinkedIn](https://linkedin.com/in/buildaiwith-jigar-prajapati).

<div align="center">

<sub>Built by an automation engineer, so naturally this README is in a code block.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a1230,100:4da3ff&height=90&section=footer" alt="" width="100%"/>

</div>
