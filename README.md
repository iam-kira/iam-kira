<h1 align="center">Konnichiwa 👋, I'm Vijay Biradar</h1>
<p align="center">
   Upcoming wealthiest man & AI Enthusiast from India
</p>

<div align="center">
  <img src="https://github.com/iam-kira/iam-kira/blob/main/Konichiwa.gif" width="700" alt="Welcome GIF"/>
</div>

---

## [About Me (click here)](https://iam-kira.github.io/vijaybiradar/)    💬
- ✨ Data Engineer at **Daimler Truck Innovation Center** (3+ years)
- 🤖 Building **Industrial AI + ETL automation** products at scale
- 📦 Owned **800+ production pipelines** and **30+ data products**
- ⚡ Reduced manual ETL effort by **80%** with AI-assisted platform engineering
- 🎯 2026+ Goals: **Grow into a Technical Lead and build toward becoming a startup CEO**
- 🎲 Fun fact: **Always thinking about goals**

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-%20Million%20lines%20of%20code-blue)

<div align="right">
  <img src="https://github.com/SP-XD/SP-XD/blob/main/images/dev-working_rounded.gif?raw=true" width="420" alt="Coding GIF"/>
</div>

## Currently Learning 📚
- Advanced Data Engineering & Distributed Systems Design
- Technical Leadership, Mentoring, and Engineering Management
- Product Thinking, Startup Strategy, and GTM Basics
- MLOps, LLMOps, and production-grade AI system architecture
- Decision-making with business metrics (cost, reliability, velocity)

## Career Snapshot 🚀
- **Current Role:** Data Engineer → Technical Lead (scope-based), Daimler Truck Innovation Center India
- **Domain:** Shopfloor digitalization, industrial analytics, ETL productization
- **Impact:** Pipeline delivery reduced from hours to minutes using MCP-based AI code synthesis
- **Reliability:** Zero SLA breaches across 2 years on high-volume production workloads

## Featured Impact 📈
- Designed reusable ETL frameworks that reduced onboarding time from days to hours
- Built AI-powered analysis modules reducing ad-hoc analyst load by ~3–4 hours/week per team
- Enabled ~40% faster audit preparation with real-time KPI visibility across global stakeholders
- Awards: **Continuous Effort Reliability (2024)** · **Integrity (2025)** · **Curious Scholar (2025)**

## Building 🔨
Things I ship and use myself.

| Project | What it is |
| --- | --- |
| [driftsnap](https://github.com/iam-kira/driftsnap) | Catches data-level drift in a table — row drops, null spikes, cardinality collapse, schema change. Your orchestrator says the task succeeded; driftsnap tells you the table came back 30% smaller. One query per snapshot, zero runtime dependencies, snapshots are plain JSON so they diff in git. Python + CLI, works over DuckDB / Iceberg / Postgres / Trino. |
| [telemetry-lakehouse](https://github.com/iam-kira/telemetry-lakehouse) | Cold-chain monitoring lakehouse built one layer at a time on a single laptop: MQTT → Kafka → Debezium CDC → Apache Iceberg → Dremio. Nine services, durable across daemon crashes, with the recovery playbooks written down. |
| [aura](https://github.com/iam-kira/what-did-i-do) | A programming language where `yeet` returns and `ghosted` is null. Lexer, parser and tree-walking interpreter in one Python file, zero dependencies. |

## Open Source 🌱
Upstream contributions to projects I use — found by running their test suites and
builds on Windows, rather than by browsing issue trackers.

**3 PRs merged · 4 more fixed upstream from my reports · 6 PRs in review · 5 issues open** — 18 projects.

### Fixed upstream
| Project | Contribution | Outcome |
| --- | --- | --- |
| [pipx](https://github.com/pypa/pipx) · 12.9k⭐ | [#2023](https://github.com/pypa/pipx/pull/2023) — test suite errored on Windows: a fixture symlinked `git` onto `PATH`, guarded only for `FileExistsError` | ✅ PR merged |
| [pylint](https://github.com/pylint-dev/pylint) · 5.7k⭐ | [#11360](https://github.com/pylint-dev/pylint/pull/11360) — functional test failed on any Windows checkout without symlink privilege | ✅ PR merged |
| [dspy](https://github.com/stanfordnlp/dspy) · 38.1k⭐ | [#10410](https://github.com/stanfordnlp/dspy/pull/10410) — alias-collision test failed when symlink creation is unavailable | ✅ PR merged |
| [gradio](https://github.com/gradio-app/gradio) · 43.5k⭐ | [#13801](https://github.com/gradio-app/gradio/issues/13801) — `gradio skills add` crashed on Windows with `WinError 1314` | ✅ Fixed in [#13803](https://github.com/gradio-app/gradio/pull/13803) |
| [black](https://github.com/psf/black) · 41.8k⭐ | [#5389](https://github.com/psf/black/issues/5389) — three symlink tests failed on Windows, a regression of #287 | ✅ Fixed in [#5390](https://github.com/psf/black/pull/5390) |
| [mlflow](https://github.com/mlflow/mlflow) · 28.0k⭐ | [#25641](https://github.com/mlflow/mlflow/issues/25641) — `mlflow-skinny` silently built an empty wheel on Windows checkouts | ✅ Fixed in [#25713](https://github.com/mlflow/mlflow/pull/25713) |
| [openai-agents-python](https://github.com/openai/openai-agents-python) · 29.5k⭐ | [#4852](https://github.com/openai/openai-agents-python/issues/4852) — 12 sandbox tests failed on Windows without symlink privilege | ◐ Test half fixed in [#4853](https://github.com/openai/openai-agents-python/pull/4853) |
### In review
| Project | Contribution | Outcome |
| --- | --- | --- |
| [transformers](https://github.com/huggingface/transformers) · 166.2k⭐ | [#48543](https://github.com/huggingface/transformers/pull/48543) — skip the symlinked hub-cache test when symlinks are unavailable | PR open |
| [langflow](https://github.com/langflow-ai/langflow) · 154.9k⭐ | [#15103](https://github.com/langflow-ai/langflow/pull/15103) — skip symlink path-containment tests on unprivileged Windows | PR open |
| [langchain](https://github.com/langchain-ai/langchain) · 146.6k⭐ | [#40405](https://github.com/langchain-ai/langchain/pull/40405) — skip prompt-loading symlink tests when symlinks are unavailable | PR open |
| [crewAI](https://github.com/crewAIInc/crewAI) · 58.7k⭐ | [#7432](https://github.com/crewAIInc/crewAI/pull/7432) — skip two path-containment security tests when symlinks are unavailable | PR open |
| [marimo](https://github.com/marimo-team/marimo) · 22.8k⭐ | [#10638](https://github.com/marimo-team/marimo/pull/10638) — configurable command-mode shortcut; an override bug made every hotkey undisableable | PR open |
| [datasets](https://github.com/huggingface/datasets) · 21.9k⭐ | [#8628](https://github.com/huggingface/datasets/pull/8628) — skip the tar-symlink extraction test when symlinks are unavailable | PR open |

### Reported
| Project | Contribution | Outcome |
| --- | --- | --- |
| [litellm](https://github.com/BerriAI/litellm) · 59.0k⭐ | [#40046](https://github.com/BerriAI/litellm/issues/40046) — five tests fail on Windows: symlinks, POSIX quoting, and a POSIX-only file mode | Issue open |
| [pytorch-lightning](https://github.com/Lightning-AI/pytorch-lightning) · 31.3k⭐ | [#21932](https://github.com/Lightning-AI/pytorch-lightning/issues/21932) — TensorBoard symlink test fails on Windows | Issue open |
| [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) · 24.3k⭐ | [#3408](https://github.com/modelcontextprotocol/python-sdk/issues/3408) — path-security test fails for unprivileged Windows contributors | Issue open |
| [adk-python](https://github.com/google/adk-python) · 21.5k⭐ | [#7029](https://github.com/google/adk-python/issues/7029) — new-file check misses added files on Windows under jj and hg | Issue open |
| [anthropic-sdk-python](https://github.com/anthropics/anthropic-sdk-python) · 3.9k⭐ | [#1915](https://github.com/anthropics/anthropic-sdk-python/issues/1915) — three symlink tests are missing the `needs_symlinks` marker | Issue open |

Three more were closed without merging, which is its own kind of signal: pylint
[#11381](https://github.com/pylint-dev/pylint/pull/11381) and
[#11382](https://github.com/pylint-dev/pylint/pull/11382) were real bugs that maintainers
had already fixed in parallel PRs, and I withdrew wandb
[#12726](https://github.com/wandb/wandb/issues/12726) myself after finding the file it
described had been deleted upstream — I had filed it against a stale checkout.

**Why these exist.** Several of these projects test Windows in CI, and the jobs are green.
GitHub runners can create symlinks; an ordinary Windows user cannot. Privilege-dependent
code passes CI and fails for every contributor on a normal machine — who usually assumes
their own setup is broken and never reports it.

## Hobbies 🎮
- Gaming
- Watching Anime
- Reading Manga
- Violinist
- Badminton (Neighbourhood professional 😄)

## Resume 📄
- Full profile: [RESUME.md](RESUME.md)

---

## Languages & Tools 👨‍💻
<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" width="52" alt="javascript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="40" width="52" alt="express" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" width="52" alt="react" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" width="52" alt="nodejs" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" width="52" alt="python" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" width="52" alt="java" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="40" width="52" alt="c" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" height="40" width="52" alt="flutter" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-original.svg" height="40" width="52" alt="dart" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" width="52" alt="html5" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" height="40" width="52" alt="sass" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" width="52" alt="css3" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" width="52" alt="mongodb" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" width="52" alt="mysql" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" height="40" width="52" alt="spring" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg" height="40" width="52" alt="kafka" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apacheairflow/apacheairflow-original.svg" height="40" width="52" alt="airflow" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/databricks/databricks-original.svg" height="40" width="52" alt="databricks" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" height="40" width="52" alt="aws" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" width="52" alt="docker" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" height="40" width="52" alt="kubernetes" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40" width="52" alt="linux" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" width="52" alt="git" />
</div>

## Tech Stack Badges 🛠
![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=violet)
![](https://img.shields.io/badge/Code-SQL-informational?style=flat&logo=postgresql&logoColor=white&color=violet)
![](https://img.shields.io/badge/Code-Scala-informational?style=flat&logo=scala&logoColor=white&color=violet)

![](https://img.shields.io/badge/ETL-Talend-informational?style=flat&logo=talend&logoColor=white&color=violet)
![](https://img.shields.io/badge/Orchestration-Airflow-informational?style=flat&logo=apacheairflow&logoColor=white&color=violet)
![](https://img.shields.io/badge/Streaming-Kafka-informational?style=flat&logo=apachekafka&logoColor=white&color=violet)
![](https://img.shields.io/badge/Streaming-Flink-informational?style=flat&logo=apacheflink&logoColor=white&color=violet)

![](https://img.shields.io/badge/Data-Databricks-informational?style=flat&logo=databricks&logoColor=white&color=violet)
![](https://img.shields.io/badge/Data-Apache%20Iceberg-informational?style=flat&logo=apacheiceberg&logoColor=white&color=violet)
![](https://img.shields.io/badge/Data-InfluxDB-informational?style=flat&logo=influxdb&logoColor=white&color=violet)
![](https://img.shields.io/badge/Data-Dremio-informational?style=flat&logo=dremio&logoColor=white&color=violet)
![](https://img.shields.io/badge/Cloud-AWS%20Glue-informational?style=flat&logo=amazonaws&logoColor=white&color=violet)

![](https://img.shields.io/badge/Observability-Grafana-informational?style=flat&logo=grafana&logoColor=white&color=violet)
![](https://img.shields.io/badge/Observability-Telegraf-informational?style=flat&logo=influxdb&logoColor=white&color=violet)

![](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=violet)
![](https://img.shields.io/badge/Tools-Kubernetes-informational?style=flat&logo=kubernetes&logoColor=white&color=violet)
![](https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=linux&logoColor=white&color=violet)
![](https://img.shields.io/badge/Cloud-AWS-informational?style=flat&logo=amazonaws&logoColor=white&color=violet)
![](https://img.shields.io/badge/Editor-VS_Code-informational?style=flat&logo=visual-studio-code&logoColor=white&color=violet)

---

## Contribution Graph 🐍
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iam-kira/iam-kira/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/iam-kira/iam-kira/output/github-snake.svg" />
    <img alt="snake eating my contribution graph" src="https://raw.githubusercontent.com/iam-kira/iam-kira/output/github-snake.svg" />
  </picture>
</div>

---

## Contact Me 📫
If you want to reach out for collaboration, doubts, or just to talk tech/anime/games — ping me 😃

<div align="left">
  <a href="https://discord.com/channels/@me" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="52" height="40" alt="discord" />
  </a>
  <a href="https://www.linkedin.com/in/vijay-biradar-1a2276164/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin" />
  </a>
  <a href="https://www.hackerrank.com/Itadori_Yuuji" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/hackerrank/default.svg" width="52" height="40" alt="hackerrank" />
  </a>
  <a href="https://twitter.com/Luoyfer" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/twitter/default.svg" width="52" height="40" alt="twitter" />
  </a>
  <a href="https://www.instagram.com/vijayybiradar/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/instagram/default.svg" width="52" height="40" alt="instagram" />
  </a>
  <a href="https://www.youtube.com/channel/UCiQjz_dDcweAaFMQxhGN6pA" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/youtube/default.svg" width="52" height="40" alt="youtube" />
  </a>
  <a href="mailto:vijaybiradar8273@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="52" height="40" alt="gmail" />
  </a>
</div>

<br/>
<div align="center">
  <img src="https://github.com/SP-XD/SP-XD/blob/main/images/dino_rounded.gif?raw=true" width="700" alt="dino"/>
</div>
<div align="center">
  <img src="https://profile-counter.glitch.me/iam/count.svg?" alt="profile counter"/>
</div>

---

_Last updated: September 2026_
