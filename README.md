<div align="center">

# Hi, I'm Surenjanath Singh 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=7AA2F7&center=true&vCenter=true&width=700&lines=Data+%26+Solutions+Engineer;I+build+AI+systems+for+regulated+industries;LLM+agents+advise.+Deterministic+gates+decide.;Local-first.+Sovereign.+Verifiable+by+design.;Built+in+Trinidad+%26+Tobago+%F0%9F%87%B9%F0%9F%87%B9)](https://surenjanath.dev)

📍 Trinidad & Tobago 🇹🇹 (UTC-4) · 🌐 [surenjanath.dev](https://surenjanath.dev) · 🖼️ [Portfolio](https://surenjanath.github.io)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/surenjanath)
[![Medium](https://img.shields.io/badge/Medium-%23000000.svg?&style=for-the-badge&logo=medium&logoColor=white)](https://surenjanath.medium.com)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?&style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/SurenjanathSinghLC)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/surenjanath)

![Profile views](https://komarev.com/ghpvc/?username=surenjanath&color=6366f1&style=for-the-badge)
![Followers](https://img.shields.io/github/followers/surenjanath?style=for-the-badge&color=7aa2f7)
![Stars](https://img.shields.io/github/stars/surenjanath?style=for-the-badge&color=bb9af7)

</div>

I build the systems insurance companies actually run on: policy administration, claims platforms, regulatory reporting, and — increasingly — AI systems designed for environments where a wrong answer has legal consequences.

---

## 🧠 How I think about AI in production

Most AI demos fall apart in regulated environments because the LLM has the final word. My core pattern inverts that: **LLM agents advise, a deterministic rules engine decides.** Agents handle retrieval, interpretation, and drafting; a code-level gate with binding authority validates every decision against explicit business and statutory rules before anything is committed. You get the flexibility of language models with the auditability regulators require.

```text
┌─────────────────────────────────────────────────────────────┐
│                    THE DETERMINISTIC GATE                   │
│                                                             │
│   🤖 Agent 1 ──┐                                            │
│   🤖 Agent 2 ──┼──▶  advisory findings  ──▶  🛡️ RULES GATE  │
│   🤖 Agent 3 ──┘     (retrieve, draft,       (binding       │
│                       interpret)              authority)    │
│                                                    │        │
│                                          ✅ commit or       │
│                                          ❌ reject + audit  │
└─────────────────────────────────────────────────────────────┘
```

This is the architecture behind my current work in multi-agent claims adjudication, and it shapes everything I build — local-first, sovereign, and verifiable by design.

## 🔒 Production systems I've shipped

My day job is building proprietary platforms for an insurance group operating across the Caribbean and South America. The code is private, but the systems are real and in production:

- **Multi-agent AI claims adjudication** — LLM agents in advisory roles with a deterministic engine as binding authority, jurisdiction-aware document retrieval across multiple territories
- **Regulatory reporting automation** — consolidates financial data across 15 territories and populates quarterly statutory returns (life & general), cutting the finance team's workload ~80%
- **Policy administration platform** — Django system managing 29,000+ policies with a REST API, built by reverse-engineering the legacy system it replaced
- **Multi-territory loyalty platform** — partner portal, customer mobile app, and admin system spanning 4 territories and 120+ partner locations, with anti-fraud rotating QR codes
- **Broker-facing insurance portal** — TT$1.5M+ in premium processed since launch
- **Claims lifecycle portal, bank reconciliation engine, pension management system** — each replacing 100+ hours/month of manual work

Sole engineer across the full lifecycle: development, deployment, infrastructure (nginx, SSL/TLS, DNS), and production support.

## 🧪 Public work you can actually read

The repos here are where I test ideas on my own time — mostly local-first AI:

<div align="center">

[![neural-analyst](https://github-readme-stats.vercel.app/api/pin/?username=surenjanath&repo=neural-analyst&theme=tokyonight&hide_border=true)](https://github.com/surenjanath/neural-analyst)
[![FormulaSpark](https://github-readme-stats.vercel.app/api/pin/?username=surenjanath&repo=FormulaSpark&theme=tokyonight&hide_border=true)](https://github.com/surenjanath/FormulaSpark)

[![AgriShield](https://github-readme-stats.vercel.app/api/pin/?username=surenjanath&repo=AgriShield&theme=tokyonight&hide_border=true)](https://github.com/surenjanath/AgriShield)
[![Actuarial_Loss_system_ai](https://github-readme-stats.vercel.app/api/pin/?username=surenjanath&repo=Actuarial_Loss_system_ai&theme=tokyonight&hide_border=true)](https://github.com/surenjanath/Actuarial_Loss_system_ai)

[![PriceTracker-Pricesmart](https://github-readme-stats.vercel.app/api/pin/?username=surenjanath&repo=PriceTracker-Pricesmart&theme=tokyonight&hide_border=true)](https://github.com/surenjanath/PriceTracker-Pricesmart)
[![Maritime-Ports-DB-Builder](https://github-readme-stats.vercel.app/api/pin/?username=surenjanath&repo=Maritime-Ports-DB-Builder&theme=tokyonight&hide_border=true)](https://github.com/surenjanath/Maritime-Ports-DB-Builder)

</div>

| Project | What it proves |
|---|---|
| **neural-analyst** | Privacy-focused desktop app: autonomous web crawling + local RAG, no cloud dependency |
| **FormulaSpark** | Local LLMs (Ollama) translating natural language into Excel formulas, with direct Excel integration |
| **AgriShield** | Climate intelligence & parametric insurance risk platform for Caribbean agriculture |
| **Actuarial Loss System AI** | Applying AI to actuarial loss analysis — where my degree meets my stack |
| **PriceTracker-Pricesmart** | Zero-touch data pipeline on GitHub Actions: daily scrape → SQL → committed analysis |
| **Maritime Ports DB Builder** | Relational schema design & data modeling from ethically scraped maritime data |

## 📊 GitHub at a glance

<div align="center">

![Suren's GitHub stats](https://github-readme-stats.vercel.app/api?username=surenjanath&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=surenjanath&theme=tokyonight&hide_border=true&layout=compact&langs_count=8)

![GitHub Streak](https://streak-stats.demolab.com?user=surenjanath&theme=tokyonight&hide_border=true)

</div>

### 🔬 Deep profile analysis

<div align="center">

![Profile summary](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=surenjanath&theme=tokyonight)

![Commits per day](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=surenjanath&theme=tokyonight&utcOffset=-4)
![Stats](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=surenjanath&theme=tokyonight)

![Repos per language](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=surenjanath&theme=tokyonight)
![Commits per language](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=surenjanath&theme=tokyonight)

![Contribution graph](https://github-readme-activity-graph.vercel.app/graph?username=surenjanath&theme=tokyo-night&hide_border=true&area=true)

![Trophies](https://github-profile-trophy.vercel.app/?username=surenjanath&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7)

</div>

### 🐍 Watch the snake eat my contributions

<div align="center">

![Snake animation](https://raw.githubusercontent.com/surenjanath/surenjanath/output/github-contribution-grid-snake-dark.svg)

</div>

### 🏙️ Contribution skyline (3D)

<div align="center">

![3D contribution graph](https://raw.githubusercontent.com/surenjanath/surenjanath/main/profile-3d-contrib/profile-night-rainbow.svg)

</div>

### 📈 Full metrics

<div align="center">

![Metrics](https://raw.githubusercontent.com/surenjanath/surenjanath/main/github-metrics.svg)

</div>

## ✍️ Latest from my Medium

<!-- BLOG-POST-LIST:START -->- 📝 [How I Used Python to Reconcile $508k in Corrupted Annuity Data](https://surenjanath.medium.com/how-i-used-python-to-reconcile-508k-in-corrupted-annuity-data-b387678b6c49?source=rss-419c230b2ecf------2) — Apr 11, 2026- 📝 [Claims Determination: An Actuarial Loss Dashboard Where Django Meets Local AI Agents](https://surenjanath.medium.com/claims-determination-an-actuarial-loss-dashboard-where-django-meets-local-ai-agents-43a89a355aed?source=rss-419c230b2ecf------2) — Apr 10, 2026- 📝 [The biggest flaw in most AI chats? Amnesia and Chaos.](https://surenjanath.medium.com/the-biggest-flaw-in-most-ai-chats-amnesia-and-chaos-d468a9fd6cf2?source=rss-419c230b2ecf------2) — Sep 8, 2025- 📝 [My Journey Building a Mobile Full-Stack ETL Pipeline: From Idea to Production](https://surenjanath.medium.com/my-journey-building-a-mobile-full-stack-etl-pipeline-from-idea-to-production-1c24f8d10a5b?source=rss-419c230b2ecf------2) — Aug 21, 2025- 📝 [Building DragonMail: A Journey into Temporary Email Apps with React Native and Expo](https://surenjanath.medium.com/building-dragonmail-a-journey-into-temporary-email-apps-with-react-native-and-expo-f02890e7a3cd?source=rss-419c230b2ecf------2) — May 20, 2025<!-- BLOG-POST-LIST:END -->

## 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama_/_Local_LLMs-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**AI engineering:** Multi-agent orchestration · RAG · prompt & eval design · Cursor / Claude Code

**Background:** BSc Actuarial Science, University of the West Indies, St Augustine — I speak both risk and code.

## 🎻 Beyond the code

Born and raised in Trinidad and Tobago, and it shows — in the humor, the music, and the projects (half my scrapers exist because I wanted local T&T data that didn't exist anywhere).

- 🎵 I produce and release music — dark atmospheric, Caribbean-inflected, always experimenting
- 🎻 Violin, when the code compiles
- 🐾 My love for animals is unconditional
- 📈 Actuarial science degree, engineer's heart — mathematics and money still fascinate me
- 📹 I've taught Python on [YouTube](https://www.youtube.com/channel/UCbDL7RSxZIJnhFBRay-JrWQ)

### 🎧 What I'm listening to

<div align="center">

[![Spotify](https://spotify-github-profile.kittinanx.com/api/view?uid=21zlc5j5zc3zhd3lie7tkbruq&cover_image=true&theme=novatorem&show_offline=false&background_color=1a1b27&interchange=false)](https://open.spotify.com/user/21zlc5j5zc3zhd3lie7tkbruq)

</div>

---

<div align="center">

### 💭 Random dev wisdom

![Dev quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

💬 Open to conversations about **AI in regulated industries**, **data sovereignty in the Caribbean**, and **remote engineering roles** (UTC-4, aligns with US Eastern).

💻 Made with ❤️ by **Surenjanath**

⭐ *If something here helps you, star it — the snake gets hungrier.*

</div>
