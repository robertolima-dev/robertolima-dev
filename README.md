# Roberto Lima

**Software developer — Python & Rust.** I build production software and open-source libraries, and teach modern web technologies.

<div align="center">

[![Website](https://img.shields.io/badge/Website-robertolima.vercel.app-FF6900?logo=vercel&logoColor=white)](https://robertolima.vercel.app/)
[![PyPI](https://img.shields.io/badge/PyPI-robertolima__dev-3775A9?logo=pypi&logoColor=white)](https://pypi.org/user/robertolima_dev/)
[![npm](https://img.shields.io/badge/npm-robertolima--dev-CB3837?logo=npm&logoColor=white)](https://www.npmjs.com/~robertolima-dev)
[![crates.io](https://img.shields.io/badge/crates.io-robertolima--dev-E6B14C?logo=rust&logoColor=white)](https://crates.io/users/robertolima-dev)
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
A **security, audit and event observability platform** built on a private, permissioned **cryptographic ledger** — a SIEM whose events are tamper-evident and independently verifiable. *Observe · Detect · Audit · Prove*: the same event flows through observability, detection, audit and cryptographic proof, in a single pipeline.

- 👁️ **Observability** — logs & events, errors, services, environments, endpoints, timeline, search & filters
- 🚨 **Detection** — brute force, suspicious IPs, new country, unusual admin/root activity, 401/403 and error spikes, threat intelligence
- 📋 **Audit trail** — actor, action, resource, timestamp, source IP, service, request ID, timeline and CSV export
- 🔏 **Cryptographic proof** — SHA-256 hash chain, Merkle proof of inclusion and integrity verification on every event
- 🏢 **Private by design** — permissioned ledger with multi-node Proof of Authority consensus, in your environment, no public blockchain
- ⚙️ **Built in Rust** — ECS normalization, host agent (zero code) and SDKs for Node.js, Python, Go and Java
- 🎯 **Compliance** — SOC 2, ISO 27001, LGPD, PCI DSS 10.5, NIST 800-53 AU-9, EU AI Act, ISO 42001

> *"Know what happened. Detect what matters. Prove what happened."*

#### 🏛️ [Gizé](https://gize-rust-framework.vercel.app/en) — *Creator*
A **productivity-focused backend framework for Rust** that removes the "day-one tax" of standing up a real-world backend — scaffolding, conventions and code generation so you ship REST APIs in minutes, not days.

- 🏗️ **Project scaffolding** — production-ready structure with routing, database pooling and error handling out of the box
- ⚙️ **CRUD generation** — models, migrations, repositories, services, DTOs, handlers, routes and tests from a single command
- 🗄️ **Multi-database** — works with PostgreSQL, SQLite and MySQL
- 🔍 **Transparent codegen** — all generated code is readable, idiomatic Rust that you fully own and can edit
- 🔋 **Optional batteries** — admin interface, authentication, WebSockets and OpenAPI docs as opt-in modules
- 🦀 **Built in Rust** — Axum + SQLx + Tokio, a 10-crate modular workspace (2024 edition)

> *"Batteries-included velocity, the Rust way."*

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

**32 packages** published on [crates.io](https://crates.io/users/robertolima-dev), [PyPI](https://pypi.org/user/robertolima_dev/) and [npm](https://www.npmjs.com/~robertolima-dev) — from a full Rust backend framework and performance-critical Rust cores to everyday utilities. Contributions, issues and suggestions are always welcome!

#### 🦀 Native Rust · crates.io <sub>(the Gizé backend framework)</sub>

| Crate | Description | Version · Downloads |
|:--|:--|:--|
| **[gize](https://crates.io/crates/gize)** | Gizé CLI — productivity-first backend framework for Rust | ![v](https://img.shields.io/crates/v/gize?style=flat-square&color=E6B14C) ![dl](https://img.shields.io/crates/d/gize?style=flat-square) |
| **[gize-core](https://crates.io/crates/gize-core)** | Core domain model, conventions and manifest | ![v](https://img.shields.io/crates/v/gize-core?style=flat-square&color=E6B14C) ![dl](https://img.shields.io/crates/d/gize-core?style=flat-square) |
| **[gize-generator](https://crates.io/crates/gize-generator)** | Code generation engine — safe file writing & templating | ![v](https://img.shields.io/crates/v/gize-generator?style=flat-square&color=E6B14C) ![dl](https://img.shields.io/crates/d/gize-generator?style=flat-square) |
| **[gize-db](https://crates.io/crates/gize-db)** | Data-layer conventions and SQLx migrations | ![v](https://img.shields.io/crates/v/gize-db?style=flat-square&color=E6B14C) ![dl](https://img.shields.io/crates/d/gize-db?style=flat-square) |
| **[gize-macros](https://crates.io/crates/gize-macros)** | Procedural macros, kept intentionally small | ![v](https://img.shields.io/crates/v/gize-macros?style=flat-square&color=E6B14C) ![dl](https://img.shields.io/crates/d/gize-macros?style=flat-square) |
| **[gize-openapi](https://crates.io/crates/gize-openapi)** | OpenAPI spec generation | ![v](https://img.shields.io/crates/v/gize-openapi?style=flat-square&color=E6B14C) ![dl](https://img.shields.io/crates/d/gize-openapi?style=flat-square) |
| **[gize-admin](https://crates.io/crates/gize-admin)** | Admin UI generator — a React SPA from the manifest | ![v](https://img.shields.io/crates/v/gize-admin?style=flat-square&color=E6B14C) ![dl](https://img.shields.io/crates/d/gize-admin?style=flat-square) |
| **[gize-templates](https://crates.io/crates/gize-templates)** | Templates for code generated by Gizé | ![v](https://img.shields.io/crates/v/gize-templates?style=flat-square&color=E6B14C) ![dl](https://img.shields.io/crates/d/gize-templates?style=flat-square) |
| **[gize-testing](https://crates.io/crates/gize-testing)** | Test utilities for Gizé-generated apps | ![v](https://img.shields.io/crates/v/gize-testing?style=flat-square&color=E6B14C) ![dl](https://img.shields.io/crates/d/gize-testing?style=flat-square) |

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
