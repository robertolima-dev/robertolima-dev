# Roberto Lima

**Software developer — Python & Rust.** I build production software and open-source libraries, and teach modern web technologies.

<div align="center">

[![Website](https://img.shields.io/badge/Website-robertolima.vercel.app-FF6900?logo=vercel&logoColor=white)](https://robertolima.vercel.app/)
[![PyPI](https://img.shields.io/badge/PyPI-robertolima__dev-3775A9?logo=pypi&logoColor=white)](https://pypi.org/user/robertolima_dev/)
[![npm](https://img.shields.io/badge/npm-robertolima--dev-CB3837?logo=npm&logoColor=white)](https://www.npmjs.com/~robertolima-dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-roberto--lima-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/roberto-lima-01/)
[![Email](https://img.shields.io/badge/Email-contact-EA4335?logo=gmail&logoColor=white)](mailto:robertolima.izphera@gmail.com)
![Profile views](https://komarev.com/ghpvc/?username=robertolima-dev&color=9747ff&label=Profile+views)

</div>

### 👨‍💻 About Me

Software developer with **12+ years of experience** across Python, Rust, JavaScript and TypeScript and their main frameworks — from scalable APIs and AI integrations to web, mobile and high-performance open-source libraries. I care about clean, readable code and shipping things people actually use.

`Rust` · `Python` · `TypeScript` · `Next.js` · `Django` · `FastAPI` · `AWS`

---

### 🏗️ Products I Build

#### 🔐 [ImmutableLog](https://immutablelog.com/en/) — *Founder*
A private, permissioned **cryptographic ledger** that turns ordinary system logs into tamper-evident, independently verifiable evidence. The **Audit Evidence Layer** for teams that need to *prove* what happened — not just describe it.

- 📜 **Append-only ledger** — events can't be edited or deleted once recorded
- 🔏 **Cryptographic proof** — deterministic hashing + inclusion verification on every event
- 🕵️ **Independent verification** — third parties can verify records without trusting the operator
- 🏢 **Private by design** — data stays in your environment, no public blockchain
- ⚙️ **Built in Rust** — distributed consensus across cluster nodes; REST API with SDKs for Node.js, Python, Go and Java
- 🎯 **Use cases** — AI governance, SOC 2, ISO 27001, LGPD, insider-threat detection and legal defensibility

> *"Your logs explain what happened. ImmutableLog proves it."*

#### 🦀 [Memorust](https://memorust.vercel.app/en/) — *Creator*
An educational, in-memory **key-value database written in Rust** — a Redis clone built from scratch with a focus on clean, readable code.

- 🔌 **Redis protocol (RESP)** — works with `redis-cli` and existing Redis clients, no changes needed
- 🗃️ **Core commands** — SET/GET, DEL, EXISTS, plus TTL & expiration (SETEX, EXPIRE, TTL) with background cleanup
- 💾 **AOF persistence** — buffered writes, periodic sync and AOF rewrite to keep history compact
- ⚡ **Fast** — ~155k ops/sec basic, up to 264k SET / 1.27M GET ops/sec with pipelining
- 🧱 **Minimal stack** — Rust (2024 edition) + Tokio as the only dependency, single binary, dual MIT/Apache-2.0

> *"Python simplicity. Rust performance."*

---

### 📦 Open-Source Packages

**23 packages** published on [PyPI](https://pypi.org/user/robertolima_dev/) and [npm](https://www.npmjs.com/~robertolima-dev) — from performance-critical Rust cores to everyday utilities. Contributions, issues and suggestions are always welcome!

#### 🦀 Powered by Rust · PyPI <sub>(PyO3 + maturin)</sub>

| Package | Description | Version · Downloads |
|:--|:--|:--|
| **[rust-py-rate-limit](https://pypi.org/project/rust-py-rate-limit/)** | Fast local rate limiting, powered by Rust | ![v](https://img.shields.io/pypi/v/rust-py-rate-limit?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/rust-py-rate-limit/month) |
| **[rust-py-cache](https://pypi.org/project/rust-py-cache/)** | Ultra-fast local cache, powered by Rust | ![v](https://img.shields.io/pypi/v/rust-py-cache?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/rust-py-cache/month) |
| **[rust_py_scheduler](https://pypi.org/project/rust_py_scheduler/)** | Performant task scheduler — interval & cron jobs, retries | ![v](https://img.shields.io/pypi/v/rust_py_scheduler?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/rust_py_scheduler/month) |
| **[rust-py-monitor](https://pypi.org/project/rust-py-monitor/)** | High-performance monitoring for Django & FastAPI | ![v](https://img.shields.io/pypi/v/rust-py-monitor?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/rust-py-monitor/month) |
| **[rust-py-audit](https://pypi.org/project/rust-py-audit/)** | Fast, tamper-evident event auditing (hash chain) | ![v](https://img.shields.io/pypi/v/rust-py-audit?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/rust-py-audit/month) |

#### 🦀 Powered by Rust · npm <sub>(napi-rs)</sub>

| Package | Description | Version · Downloads |
|:--|:--|:--|
| **[rust-node-monitor](https://www.npmjs.com/package/rust-node-monitor)** | Lightweight Node.js monitoring, powered by Rust | ![v](https://img.shields.io/npm/v/rust-node-monitor?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/rust-node-monitor?style=flat-square) |
| **[rust-node-rate-limit](https://www.npmjs.com/package/rust-node-rate-limit)** | Ultra-fast rate limiting for Node.js | ![v](https://img.shields.io/npm/v/rust-node-rate-limit?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/rust-node-rate-limit?style=flat-square) |
| **[rust-node-cache](https://www.npmjs.com/package/rust-node-cache)** | Ultra-fast in-memory cache for Node.js | ![v](https://img.shields.io/npm/v/rust-node-cache?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/rust-node-cache?style=flat-square) |

#### 🐍 Python utilities · PyPI

| Package | Description | Version · Downloads |
|:--|:--|:--|
| **[smart-time-py](https://pypi.org/project/smart-time-py/)** | Advanced date & time manipulation | ![v](https://img.shields.io/pypi/v/smart-time-py?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/smart-time-py/month) |
| **[excel-toolkit-for-py](https://pypi.org/project/excel-toolkit-for-py/)** | Read, manipulate, validate and export Excel files | ![v](https://img.shields.io/pypi/v/excel-toolkit-for-py?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/excel-toolkit-for-py/month) |
| **[text-cleaner-for-py](https://pypi.org/project/text-cleaner-for-py/)** | Text cleaning and normalization utilities | ![v](https://img.shields.io/pypi/v/text-cleaner-for-py?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/text-cleaner-for-py/month) |
| **[SmartSecurityPy](https://pypi.org/project/SmartSecurityPy/)** | Password hashing, encryption and JWT utilities | ![v](https://img.shields.io/pypi/v/SmartSecurityPy?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/SmartSecurityPy/month) |
| **[SmartJsonPy](https://pypi.org/project/SmartJsonPy/)** | Smart JSON validation, cleaning and conversion | ![v](https://img.shields.io/pypi/v/SmartJsonPy?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/SmartJsonPy/month) |
| **[SmartTestPy](https://pypi.org/project/SmartTestPy/)** | An intelligent testing framework for Python | ![v](https://img.shields.io/pypi/v/SmartTestPy?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/SmartTestPy/month) |
| **[SmartLogs](https://pypi.org/project/SmartLogs/)** | Smart logger with colors, file output and levels | ![v](https://img.shields.io/pypi/v/SmartLogs?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/SmartLogs/month) |
| **[scrapy-html](https://pypi.org/project/scrapy-html/)** | HTML scraper returning tags, classes and attributes | ![v](https://img.shields.io/pypi/v/scrapy-html?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/scrapy-html/month) |
| **[TaskFlowPy](https://pypi.org/project/TaskFlowPy/)** | A simple, efficient task manager for Python | ![v](https://img.shields.io/pypi/v/TaskFlowPy?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/TaskFlowPy/month) |
| **[pdf-to-img-converter](https://pypi.org/project/pdf-to-img-converter/)** | Convert PDF files into images | ![v](https://img.shields.io/pypi/v/pdf-to-img-converter?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/pdf-to-img-converter/month) |

#### 🟨 JavaScript / Node utilities · npm

| Package | Description | Version · Downloads |
|:--|:--|:--|
| **[cpf-cnpj-email-validator](https://www.npmjs.com/package/cpf-cnpj-email-validator)** | Validators for Brazilian CPF, CNPJ and email | ![v](https://img.shields.io/npm/v/cpf-cnpj-email-validator?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/cpf-cnpj-email-validator?style=flat-square) |
| **[currency-br](https://www.npmjs.com/package/currency-br)** | Brazilian Real (R$) currency formatting and parsing | ![v](https://img.shields.io/npm/v/currency-br?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/currency-br?style=flat-square) |
| **[address-br](https://www.npmjs.com/package/address-br)** | Brazilian address utilities — lookup and formatting | ![v](https://img.shields.io/npm/v/address-br?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/address-br?style=flat-square) |
| **[calc-array](https://www.npmjs.com/package/calc-array)** | Helpers to compute values over arrays | ![v](https://img.shields.io/npm/v/calc-array?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/calc-array?style=flat-square) |
| **[calc-simple-npm](https://www.npmjs.com/package/calc-simple-npm)** | A simple calculator module for everyday arithmetic | ![v](https://img.shields.io/npm/v/calc-simple-npm?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/calc-simple-npm?style=flat-square) |

---

### 🚀 Study Projects

- 👉 [**Django usecases**](https://github.com/robertolima-dev/django-usecases) — advanced Django study project
- 👉 [**Rust usecases**](https://github.com/robertolima-dev/rust-usecases) — advanced Rust study project
- 👉 [**Rust blockchain**](https://github.com/robertolima-dev/rust_blockchain) — blockchain built in Rust

---

### ⚡ Technologies & Tools

**🐍 Python** — Django · Django REST Framework · Celery · FastAPI · PostgreSQL · Redis · Elasticsearch · Pytest · Poetry

**⚙️ JavaScript / TypeScript** — React · Next.js · Vue · Node.js · Express · NestJS · Adonis

**🦀 Rust** — Tokio · Actix Web · PyO3 · napi-rs · Cargo

**☁️ DevOps & AI** — Docker · Docker Compose · GitHub Actions · AWS (ECS, S3, SES, SQS) · OpenAI API · LangChain · n8n

---

### 📊 GitHub Stats

<div align="center">

![Roberto's GitHub stats](https://github-readme-stats.vercel.app/api?username=robertolima-dev&show_icons=true&hide_border=true&theme=tokyonight)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=robertolima-dev&layout=compact&hide_border=true&theme=tokyonight)

![GitHub streak](https://streak-stats.demolab.com/?user=robertolima-dev&hide_border=true&theme=tokyonight)

</div>

---

### 📫 Contact

- 🌐 [Website](https://robertolima.vercel.app/)
- 💼 [LinkedIn](https://www.linkedin.com/in/roberto-lima-01/)
- ✉️ [robertolima.izphera@gmail.com](mailto:robertolima.izphera@gmail.com)

---

## 📚 Português
🇧🇷 [Clique aqui para a versão em português](README.pt-br.md)
