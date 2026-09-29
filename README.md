# Hey, I'm Pratik 👋

```console
pratik@bangkok ~ % whoami
infra guy · senior software engineer, infra operations @ agoda
```

I love infrastructure. Honestly, infrastructure automation is the most fun part of my day. Give me a manual process that everyone is a little scared of, and I will want to turn it into something that runs by itself, with a dry run, a canary, and a way back.

The thing I love most is **Go and Kubernetes controllers**. You tell the cluster what the world should look like, and the controller keeps pushing reality until it agrees. That idea never gets old for me.

[![Portfolio](https://img.shields.io/badge/pratik.dev-222?style=flat-square&logo=gnubash&logoColor=white)](https://portfolio.pratikghose1999.workers.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square)](https://www.linkedin.com/in/pratikghose)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:pratikghose1999@gmail.com)

### 🐉 Quick facts

| | |
|---|---|
| **Based in** | Bangkok 🇹🇭 |
| **Day job** | Keeping Linux fleets, Kubernetes, and telemetry honest |
| **Naming scheme** | Dragon Ball. Everything. You'll see. |
| **Known weakness** | DNS. It is always DNS. |
| **Fuel** | Chai ☕ |

### 🏆 A few things I'm proud of

- **Ten thousand drifts to zero.** Production Kubernetes at Agoda had drifted away from what the repos said: more than **10,000** drifts and orphans. I built a drift platform and we got it to **zero in one month**.
- **Patching in minutes, not hours.** I moved Linux patching from Rundeck to GitLab and AWX. Most teams use it now, and parallel patch windows went from **hours to 10–20 minutes**.
- **Never blind again.** An OpenTelemetry rollout across **6,000 servers** once left operators blind for hours. So I added canaries, readiness gates, and rollback, and now a bad rollout stops small.
- **20 TB → 2 TB.** At Highspot I ran Prometheus Operator in production, and recording rules and filtering brought daily metrics down from **20 TB to 2 TB**. Retiring redundant observability infra saved an estimated **$720K+ a year**.
- **Flags for everyone.** Also at Highspot: I built the company-wide LaunchDarkly platform, so every team ships behind off-by-default feature flags.
- **Logging on a diet.** At ThoughtSpot I cut logging cost by **38%**, mostly by catching logs that were overflowing and switching off telemetry nobody was reading.

<sub>Before that: 300+ reusable APIs at Apisero, and Terraform libraries for Azure at EPAM.</sub>

### 🧪 What I'm building on the side

**Capsule Corp** *(private)*. Yes, it's named after Bulma's company. It's my crew of AI agents that plan, build, review, and fix their own incidents on a schedule. Korin writes the post-mortems, and Kami's Lookout watches the dashboards. Don't think of it as a small side project. I want it to work like a whole engineering team.

**Scouter** *(private)*. I take a lot of raw photos on a Sony Alpha 7 and an Olympus OM-D E-M10 Mark III. Lightroom got too expensive, so I moved to darktable, and I'm honestly not that good at it yet. So I'm building an agent I can talk to: I say "warmer" or "lift the shadows", and darktable changes live in front of me. No AI re-rendering my picture. It's still my photo, just edited faster.

And some small tools I use every day:

| Project | What it does |
|---|---|
| [ccusage-report](https://github.com/pratikgh0se/ccusage-report) | An 8-page dashboard showing where my Claude Code money goes. `brew install`-able from [the tap](https://github.com/pratikgh0se/homebrew-ccusage-report) |
| [claude-efficiency-hooks](https://github.com/pratikgh0se/claude-efficiency-hooks) | Hooks that stop agents from burning tokens on wasteful patterns |
| [auto-docs-skill](https://github.com/pratikgh0se/auto-docs-skill) | Keeps docs and changelogs current as I commit, so nobody has to remember |
| [meta-prompt-skill](https://github.com/pratikgh0se/meta-prompt-skill) | Generates prompt templates using Anthropic's metaprompt technique |
| [obsidian-second-brain](https://github.com/pratikgh0se/obsidian-second-brain) | My fork of a plain-markdown memory for coding agents. I got tired of re-explaining my projects every session |

<sub>Also private: MCP servers so my agents can talk to YouTube and Instagram.</sub>

### 🗺️ Where I'm headed

From infra to AI research. I've planned it as a multi-year self-study that starts in October 2026. Infra taught me how systems break. Now I want to understand how models learn.

### 💬 Talk to me about

Kubernetes controllers · reconcile loops · why your alert fired at 3 a.m. · safe rollouts · observability bills · photography · agents doing real ops work

---

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000?style=flat-square&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

<sub>If it's toil, I'll automate it. If it's DNS, I'll sigh first, then automate it.</sub>
