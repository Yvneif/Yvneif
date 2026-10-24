<!-- ─────────────────────────────────────────────────────────────────────
     Profile README — Mike Kenneth S. Rivera (@Yvneif)
     Format: a GitHub Actions workflow run. The whole page reads as one.

     Quick tweak guide:
     • Job list & statuses → the ```diff "run overview" block. Keep the
       dot columns aligned (name padded to 14 chars, 12 dots).
     • Job sections → each "## ✓ `job-name`" maps 1:1 to a line in the
       overview. If you add a job, add it to the yaml header + overview +
       footer summary so the counts still add up.
     • Log timestamps in the cloud-devops block are flavor — bump them
       when you ship something new.
     • Run statistics → delete the <details> at the bottom if you'd
       rather not depend on third-party stat services.
     • Icon rows come from skillicons.dev — no generic `sql` slug exists;
       the SQLite icon stands in for it.
   ───────────────────────────────────────────────────────────────────── -->

<h1 align="center">Mike Kenneth S. Rivera</h1>

<p align="center">
  <sub>Associate Software QA Engineer · Qstrike Innovations · Angeles City, PH</sub>
</p>

```yaml
# .github/workflows/profile.yml
# maintainer: @Yvneif

name: mike-kenneth-s-rivera

on:
  profile_view:
    types: [recruiter, fellow_dev, curious_passerby]
  schedule:
    - cron: "0 6 * * *"   # one new thing learned, daily

permissions:
  contents: read           # least privilege, always

jobs:
  whoami:
  philosophy:
  artifacts:
  environment:
  credentials:
  cloud-devops:
  notify:
```

<p align="center">
  <sub><b>Run #4731</b> · branch <code>main</code> · triggered 2026-10-25T05:41:12Z · runner: <code>kenneth-latest</code></sub>
</p>

```diff
+ PASS whoami         ............ 4s
+ PASS philosophy     ............ 1s
+ PASS artifacts      ............ 11m 32s
+ PASS environment    ............ 3s
+ PASS credentials    ............ 2s
  RUN  cloud-devops   ............ running
+ PASS notify         ............ 1s
```

## ✓ `whoami`

I'm an Associate Software QA Engineer at Qstrike Innovations, where I run functional, regression, smoke, and UAT testing on production web apps, tracked end to end in Jira and Xray. Somewhere along the way I started building more tooling than test cases — automated checks, visual regression runs, CI gates — because I'd rather catch a break in a build log than in a bug report.

## ✓ `philosophy`

- `risk-first` — Coverage that mirrors how the product is actually used beats coverage that only inflates a number.
- `fail-loudly` — A test that no build depends on is documentation, not a safety net.
- `document-tradeoffs` — Every tool has cases it handles badly, and those belong in the README next to the happy path rather than hidden in a wiki nobody reads.
- `leave-a-trail` — Review decisions, migrations and release notes are part of the deliverable, not cleanup for later.

## ✓ `artifacts`

Four artifacts uploaded to this run:

### 📦 [ThesisArchive](https://github.com/Yvneif/ThesisArchive)

A thesis archive for schools that need a controlled publishing workflow: students submit PDF manuscripts, a faculty review board approves or returns them with a full audit trail, and approved work becomes a public, searchable catalog.

<img alt="ASP.NET Core 8" src="https://img.shields.io/badge/ASP.NET_Core_8-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
<img alt="EF Core" src="https://img.shields.io/badge/EF_Core-512BD4?style=flat-square" />
<img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
<img alt="xUnit" src="https://img.shields.io/badge/xUnit-512BD4?style=flat-square" />
<img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
<img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />

### 📦 [QA-as-Code Starter](https://github.com/Yvneif/QA-as-Code-Starter)

A clone-and-go Playwright + TypeScript suite built around a Page Object Model, running a three-browser GitHub Actions matrix (Chromium, Firefox, WebKit) — so a regression shows up as a red build instead of surfacing two sprints later.

<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
<img alt="Page Object Model" src="https://img.shields.io/badge/Page_Object_Model-000000?style=flat-square" />
<img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />

### 📦 [CrossBrowser-Check](https://github.com/Yvneif/CrossBrowser-Check)

A CLI that captures a URL in Chromium, Firefox and WebKit across desktop, tablet and mobile viewports, pixel-diffs every capture against an accepted baseline, and writes a self-contained HTML gallery with a draggable before/after slider. Nine combinations in under two minutes, with CI-ready exit codes.

<img alt="Node.js" src="https://img.shields.io/badge/Node.js_20%2B-339933?style=flat-square&logo=node.js&logoColor=white" />
<img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
<img alt="pixelmatch" src="https://img.shields.io/badge/pixelmatch-444444?style=flat-square" />
<img alt="License" src="https://img.shields.io/badge/License-MIT-A6A6A6?style=flat-square" />

### 📦 [RicePest](https://github.com/Yvneif/RicePest)

Group thesis project: a fine-tuned ResNet50 model that identifies rice pests from camera or uploaded images and recommends control measures — shipped as an installable, offline-capable PWA, so field use doesn't depend on signal.

<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img alt="Flask" src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />
<img alt="TensorFlow" src="https://img.shields.io/badge/Keras_%2F_TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
<img alt="PWA" src="https://img.shields.io/badge/PWA-5A0FC8?style=flat-square" />

<details>
<summary><b>📦 Additional artifacts</b> — coursework and side projects (screenshots on the <a href="https://kriv-portfolio.vercel.app/projects">portfolio</a>)</summary>
<br/>

- **Angeles City CSWDO CMS Website** — a site for the City Social Welfare and Development Office of Angeles City, managing social welfare data across barangays.
- **Financial Report Dashboard** and **COVID-19 Dashboard** — BI dashboards in Power BI and SAP Analytics Cloud.

</details>

## ✓ `environment`

<sub>runner image: <code>kenneth-latest</code> — everything below pre-installed and battle-tested</sub>

**Languages**

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=cs,py,js,ts,php&theme=dark" />
    <img src="https://skillicons.dev/icons?i=cs,py,js,ts,php&theme=light" alt="C#, Python, JavaScript, TypeScript, PHP" />
  </picture>
</p>

**Backend, data, cloud & tooling**

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=dotnet,sqlite,laravel,tailwind,docker,githubactions,git,aws&theme=dark" />
    <img src="https://skillicons.dev/icons?i=dotnet,sqlite,laravel,tailwind,docker,githubactions,git,aws&theme=light" alt="ASP.NET Core, SQLite, Laravel, Tailwind CSS, Docker, GitHub Actions, Git, AWS" />
  </picture>
</p>

**QA & testing**

<p align="center">
  <img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
  <img alt="Selenium" src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" />
  <img alt="Vitest" src="https://img.shields.io/badge/Vitest-729B1B?style=flat-square&logo=vitest&logoColor=white" />
  <img alt="xUnit" src="https://img.shields.io/badge/xUnit-512BD4?style=flat-square" />
  <img alt="pytest" src="https://img.shields.io/badge/pytest-0A9ED9?style=flat-square&logo=pytest&logoColor=white" />
  <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
  <img alt="ESLint" src="https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white" />
  <img alt="Prettier" src="https://img.shields.io/badge/Prettier-1A2B34?style=flat-square&logo=prettier&logoColor=F7B93E" />
</p>

**Data & BI**

<p align="center">
  <img alt="Power BI" src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square" />
  <img alt="Tableau" src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" />
  <img alt="SAP Analytics Cloud" src="https://img.shields.io/badge/SAP_Analytics_Cloud-0FAAFF?style=flat-square&logo=sap&logoColor=white" />
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
</p>

## ✓ `credentials`

- ✓ **AWS Certified AI Practitioner** — Amazon Web Services
- ✓ **Cisco CCNA** — Introduction to Networks · Switching, Routing & Wireless Essentials · Enterprise Networking, Security & Automation
- ✓ **DataCamp** — 15+ courses across Python, SQL, Git & GitHub, data engineering fundamentals, containers & virtualization, and AI agents
- ✓ **SAP Analytics Cloud** — SAP

<sub>Full list, with credentials, on the <a href="https://kriv-portfolio.vercel.app/certificates">portfolio</a>.</sub>

## ⏳ `cloud-devops`

> A pipeline is still a system whose failure modes you get to design around, and finding them early is the part of QA I already enjoy — the same instinct, one layer upstream, before a bad change reaches production.

```
05:41:20.113  aws        IAM · EC2 · S3 · CloudWatch — and what good IaC looks like
05:41:22.874  docker     container fundamentals — image → registry → deploy
05:41:25.431  actions    GitHub Actions beyond test workflows
05:41:28.902  linux/net  the CCNA courses are doing their part
```

*…job still running — certifications, side projects, and picking apart how the systems I test are built and deployed underneath.*

## ✓ `notify`

Notifying all channels:

<p align="center">
  <a href="https://kriv-portfolio.vercel.app/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-kriv--portfolio.vercel.app-000000?style=flat-square&logo=vercel&logoColor=white" /></a>
  <a href="https://linkedin.com/in/mike-kenneth-rivera"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-mike--kenneth--rivera-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/Yvneif"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-Yvneif-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>

```diff
+ ✔ 6 passed · 1 running · 0 failed · 0 flaky · run #4731 completed
```

<details>
<summary><b>▸ Expand: run statistics</b></summary>
<br/>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Yvneif&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github&theme=tokyonight" />
    <img height="170" src="https://github-readme-stats.vercel.app/api?username=Yvneif&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Yvneif&hide_border=true&locale=en&theme=github-dark-blue" />
    <img height="170" src="https://streak-stats.demolab.com?user=Yvneif&hide_border=true&locale=en" alt="GitHub streak" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Yvneif&layout=compact&hide_border=true&langs_count=8&theme=tokyonight" />
    <img width="44%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yvneif&layout=compact&hide_border=true&langs_count=8" alt="Top languages" />
  </picture>
</p>

</details>
