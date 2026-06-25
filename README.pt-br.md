# Roberto Lima

**Desenvolvedor de software — Python & Rust.** Construo software em produção e bibliotecas open-source, e ensino tecnologias modernas para a web.

<div align="center">

[![Website](https://img.shields.io/badge/Website-robertolima.vercel.app-FF6900?logo=vercel&logoColor=white)](https://robertolima.vercel.app/)
[![PyPI](https://img.shields.io/badge/PyPI-robertolima__dev-3775A9?logo=pypi&logoColor=white)](https://pypi.org/user/robertolima_dev/)
[![npm](https://img.shields.io/badge/npm-robertolima--dev-CB3837?logo=npm&logoColor=white)](https://www.npmjs.com/~robertolima-dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-roberto--lima-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/roberto-lima-01/)
[![Email](https://img.shields.io/badge/Email-contato-EA4335?logo=gmail&logoColor=white)](mailto:robertolima.izphera@gmail.com)
![Visualizações](https://komarev.com/ghpvc/?username=robertolima-dev&color=9747ff&label=Visualiza%C3%A7%C3%B5es)

</div>

### 👨‍💻 Sobre Mim

Desenvolvedor de software com **mais de 12 anos de experiência** em Python, Rust, JavaScript e TypeScript e seus principais frameworks — de APIs escaláveis e integrações com IA a web, mobile e bibliotecas open-source de alta performance. Prezo por código limpo e legível e por entregar coisas que as pessoas realmente usam.

`Rust` · `Python` · `TypeScript` · `Next.js` · `Django` · `FastAPI` · `AWS`

---

### 🏗️ Produtos que Construo

#### 🔐 [ImmutableLog](https://immutablelog.com/en/) — *Fundador*
Um **ledger criptográfico** privado e permissionado que transforma logs comuns de sistema em evidências invioláveis e verificáveis de forma independente. A **camada de evidência de auditoria** para times que precisam *provar* o que aconteceu — não apenas descrever.

- 📜 **Ledger append-only** — eventos não podem ser editados ou apagados depois de registrados
- 🔏 **Prova criptográfica** — hashing determinístico + verificação de inclusão em cada evento
- 🕵️ **Verificação independente** — terceiros podem validar os registros sem confiar no operador
- 🏢 **Privado por design** — os dados ficam no seu ambiente, sem blockchain pública
- ⚙️ **Feito em Rust** — consenso distribuído entre nós do cluster; API REST com SDKs para Node.js, Python, Go e Java
- 🎯 **Casos de uso** — governança de IA, SOC 2, ISO 27001, LGPD, detecção de ameaças internas e defesa jurídica

> *"Seus logs explicam o que aconteceu. O ImmutableLog prova."*

#### 🦀 [Memorust](https://memorust.vercel.app/en/) — *Criador*
Um **banco de dados chave-valor em memória escrito em Rust**, com fins educacionais — um clone do Redis construído do zero, com foco em código limpo e legível.

- 🔌 **Protocolo Redis (RESP)** — funciona com `redis-cli` e clientes Redis existentes, sem alterações
- 🗃️ **Comandos essenciais** — SET/GET, DEL, EXISTS, além de TTL & expiração (SETEX, EXPIRE, TTL) com limpeza em background
- 💾 **Persistência AOF** — escrita bufferizada, sync periódico e rewrite do AOF para manter o histórico compacto
- ⚡ **Rápido** — ~155k ops/seg básico, até 264k SET / 1.27M GET ops/seg com pipelining
- 🧱 **Stack enxuta** — Rust (edição 2024) + Tokio como única dependência, binário único, licença dupla MIT/Apache-2.0

> *"Simplicidade do Python. Performance do Rust."*

---

### 📦 Pacotes Open-Source

**23 pacotes** publicados no [PyPI](https://pypi.org/user/robertolima_dev/) e no [npm](https://www.npmjs.com/~robertolima-dev) — de cores em Rust de alta performance a utilitários do dia a dia. Contribuições, issues e sugestões são sempre bem-vindas!

#### 🦀 Powered by Rust · PyPI <sub>(PyO3 + maturin)</sub>

| Pacote | Descrição | Versão · Downloads |
|:--|:--|:--|
| **[rust-py-rate-limit](https://pypi.org/project/rust-py-rate-limit/)** | Rate limiting local rápido, com core em Rust | ![v](https://img.shields.io/pypi/v/rust-py-rate-limit?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/rust-py-rate-limit/month) |
| **[rust-py-cache](https://pypi.org/project/rust-py-cache/)** | Cache local ultrarrápido, com core em Rust | ![v](https://img.shields.io/pypi/v/rust-py-cache?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/rust-py-cache/month) |
| **[rust_py_scheduler](https://pypi.org/project/rust_py_scheduler/)** | Agendador de tarefas — jobs por intervalo & cron, retries | ![v](https://img.shields.io/pypi/v/rust_py_scheduler?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/rust_py_scheduler/month) |
| **[rust-py-monitor](https://pypi.org/project/rust-py-monitor/)** | Monitoramento de alta performance para Django & FastAPI | ![v](https://img.shields.io/pypi/v/rust-py-monitor?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/rust-py-monitor/month) |
| **[rust-py-audit](https://pypi.org/project/rust-py-audit/)** | Auditoria de eventos inviolável (hash chain), rápida | ![v](https://img.shields.io/pypi/v/rust-py-audit?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/rust-py-audit/month) |

#### 🦀 Powered by Rust · npm <sub>(napi-rs)</sub>

| Pacote | Descrição | Versão · Downloads |
|:--|:--|:--|
| **[rust-node-monitor](https://www.npmjs.com/package/rust-node-monitor)** | Monitoramento leve para Node.js, com core em Rust | ![v](https://img.shields.io/npm/v/rust-node-monitor?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/rust-node-monitor?style=flat-square) |
| **[rust-node-rate-limit](https://www.npmjs.com/package/rust-node-rate-limit)** | Rate limiting ultrarrápido para Node.js | ![v](https://img.shields.io/npm/v/rust-node-rate-limit?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/rust-node-rate-limit?style=flat-square) |
| **[rust-node-cache](https://www.npmjs.com/package/rust-node-cache)** | Cache em memória ultrarrápido para Node.js | ![v](https://img.shields.io/npm/v/rust-node-cache?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/rust-node-cache?style=flat-square) |

#### 🐍 Utilitários Python · PyPI

| Pacote | Descrição | Versão · Downloads |
|:--|:--|:--|
| **[smart-time-py](https://pypi.org/project/smart-time-py/)** | Manipulação avançada de data & hora | ![v](https://img.shields.io/pypi/v/smart-time-py?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/smart-time-py/month) |
| **[excel-toolkit-for-py](https://pypi.org/project/excel-toolkit-for-py/)** | Ler, manipular, validar e exportar arquivos Excel | ![v](https://img.shields.io/pypi/v/excel-toolkit-for-py?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/excel-toolkit-for-py/month) |
| **[text-cleaner-for-py](https://pypi.org/project/text-cleaner-for-py/)** | Limpeza e normalização de texto | ![v](https://img.shields.io/pypi/v/text-cleaner-for-py?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/text-cleaner-for-py/month) |
| **[SmartSecurityPy](https://pypi.org/project/SmartSecurityPy/)** | Hash de senha, criptografia e validação de JWT | ![v](https://img.shields.io/pypi/v/SmartSecurityPy?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/SmartSecurityPy/month) |
| **[SmartJsonPy](https://pypi.org/project/SmartJsonPy/)** | Validação, limpeza e conversão inteligente de JSON | ![v](https://img.shields.io/pypi/v/SmartJsonPy?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/SmartJsonPy/month) |
| **[SmartTestPy](https://pypi.org/project/SmartTestPy/)** | Framework de testes inteligente para Python | ![v](https://img.shields.io/pypi/v/SmartTestPy?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/SmartTestPy/month) |
| **[SmartLogs](https://pypi.org/project/SmartLogs/)** | Logger com cores, saída em arquivo e níveis | ![v](https://img.shields.io/pypi/v/SmartLogs?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/SmartLogs/month) |
| **[scrapy-html](https://pypi.org/project/scrapy-html/)** | Scraper de HTML retornando tags, classes e atributos | ![v](https://img.shields.io/pypi/v/scrapy-html?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/scrapy-html/month) |
| **[TaskFlowPy](https://pypi.org/project/TaskFlowPy/)** | Gerenciador de tarefas simples e eficiente | ![v](https://img.shields.io/pypi/v/TaskFlowPy?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/TaskFlowPy/month) |
| **[pdf-to-img-converter](https://pypi.org/project/pdf-to-img-converter/)** | Converte arquivos PDF em imagens | ![v](https://img.shields.io/pypi/v/pdf-to-img-converter?style=flat-square&color=3775A9) ![dl](https://static.pepy.tech/badge/pdf-to-img-converter/month) |

#### 🟨 Utilitários JavaScript / Node · npm

| Pacote | Descrição | Versão · Downloads |
|:--|:--|:--|
| **[cpf-cnpj-email-validator](https://www.npmjs.com/package/cpf-cnpj-email-validator)** | Validadores de CPF, CNPJ e e-mail | ![v](https://img.shields.io/npm/v/cpf-cnpj-email-validator?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/cpf-cnpj-email-validator?style=flat-square) |
| **[currency-br](https://www.npmjs.com/package/currency-br)** | Formatação e parsing de Real brasileiro (R$) | ![v](https://img.shields.io/npm/v/currency-br?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/currency-br?style=flat-square) |
| **[address-br](https://www.npmjs.com/package/address-br)** | Utilitários de endereços do Brasil | ![v](https://img.shields.io/npm/v/address-br?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/address-br?style=flat-square) |
| **[calc-array](https://www.npmjs.com/package/calc-array)** | Helpers para calcular valores em arrays | ![v](https://img.shields.io/npm/v/calc-array?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/calc-array?style=flat-square) |
| **[calc-simple-npm](https://www.npmjs.com/package/calc-simple-npm)** | Módulo de calculadora simples | ![v](https://img.shields.io/npm/v/calc-simple-npm?style=flat-square&color=CB3837) ![dl](https://img.shields.io/npm/dm/calc-simple-npm?style=flat-square) |

---

### 🚀 Projetos de Estudo

- 👉 [**Django usecases**](https://github.com/robertolima-dev/django-usecases) — projeto avançado de estudos em Django
- 👉 [**Rust usecases**](https://github.com/robertolima-dev/rust-usecases) — projeto avançado de estudos em Rust
- 👉 [**Rust blockchain**](https://github.com/robertolima-dev/rust_blockchain) — blockchain construída em Rust

---

### ⚡ Tecnologias & Ferramentas

**🐍 Python** — Django · Django REST Framework · Celery · FastAPI · PostgreSQL · Redis · Elasticsearch · Pytest · Poetry

**⚙️ JavaScript / TypeScript** — React · Next.js · Vue · Node.js · Express · NestJS · Adonis

**🦀 Rust** — Tokio · Actix Web · PyO3 · napi-rs · Cargo

**☁️ DevOps & IA** — Docker · Docker Compose · GitHub Actions · AWS (ECS, S3, SES, SQS) · OpenAI API · LangChain · n8n

---

### 📊 Estatísticas do GitHub

<div align="center">

![Estatísticas do GitHub de Roberto](https://github-readme-stats.vercel.app/api?username=robertolima-dev&show_icons=true&hide_border=true&theme=tokyonight)
![Linguagens mais usadas](https://github-readme-stats.vercel.app/api/top-langs/?username=robertolima-dev&layout=compact&hide_border=true&theme=tokyonight)

![Streak do GitHub](https://streak-stats.demolab.com/?user=robertolima-dev&hide_border=true&theme=tokyonight)

</div>

---

### 📫 Contato

- 🌐 [Website](https://robertolima.vercel.app/)
- 💼 [LinkedIn](https://www.linkedin.com/in/roberto-lima-01/)
- ✉️ [robertolima.izphera@gmail.com](mailto:robertolima.izphera@gmail.com)

---

## 📚 English
🇺🇸 [Click here for the English version](README.md)
