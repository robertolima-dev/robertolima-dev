# Roberto Lima
Desenvolvedor backend com foco em Python e Rust. Contribuo ativamente com projetos open-source e ensino tecnologias modernas para a web.

### 👨‍💻 Sobre Mim
Desenvolvedor de software com mais de 10 anos de experiência em Python, Rust, JavaScript e TypeScript, além de seus principais frameworks.

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

---

### 🚀 Projeto em Destaque
Confira meu projeto principal de estudos avançados em Django:  
👉 [Django usecases](https://github.com/robertolima-dev/django-usecases)

### 📦 Meus pacotes open-source no PyPI

Contribuo ativamente com a comunidade Python através de pacotes no [PyPI](https://pypi.org/user/robertolima_dev/). Alguns deles:

- **[SmartJsonPy](https://pypi.org/project/SmartJsonPy/)**  
  Pacote para validações, limpeza e manipulação avançada de JSON.  
  ![PyPI - Version](https://img.shields.io/pypi/v/SmartJsonPy) ![PyPI - Downloads](https://img.shields.io/pypi/dm/SmartJsonPy)

- **[excel_toolkit_for_py](https://pypi.org/project/excel_toolkit_for_py/)**  
  Ferramenta poderosa para conversões, manipulações e validações de arquivos Excel.  
  ![PyPI - Version](https://img.shields.io/pypi/v/excel_toolkit_for_py) ![PyPI - Downloads](https://img.shields.io/pypi/dm/excel_toolkit_for_py)

- **[text_cleaner_for_py](https://pypi.org/project/text_cleaner_for_py/)**  
  Pacote prático para limpeza avançada e normalização de textos.  
  ![PyPI - Version](https://img.shields.io/pypi/v/text_cleaner_for_py) ![PyPI - Downloads](https://img.shields.io/pypi/dm/text_cleaner_for_py)

- **[scrapy_html](https://pypi.org/project/scrapy_html/)**  
  Simplifica scraping HTML, permitindo buscas rápidas por tags e classes.  
  ![PyPI - Version](https://img.shields.io/pypi/v/scrapy_html) ![PyPI - Downloads](https://img.shields.io/pypi/dm/scrapy_html)

- **[SmartTestPy](https://pypi.org/project/SmartTestPy/)**  
  Biblioteca de testes inteligentes para Django, facilitando testes automatizados.  
  ![PyPI - Version](https://img.shields.io/pypi/v/SmartTestPy) ![PyPI - Downloads](https://img.shields.io/pypi/dm/SmartTestPy)

- **[SmartSecurityPy](https://pypi.org/project/SmartSecurityPy/)**  
  Biblioteca de segurança: hash de senha, criptografia e validação de JWT.  
  ![PyPI - Version](https://img.shields.io/pypi/v/SmartSecurityPy) ![PyPI - Downloads](https://img.shields.io/pypi/dm/SmartSecurityPy)

Sinta-se à vontade para contribuir ou sugerir melhorias!

### 📫 Contato
- [LinkedIn](https://www.linkedin.com/in/roberto-lima-01/)
- [E-mail](mailto:robertolima.izphera@gmail.com)
- [Website](https://robertolima.vercel.app/)

---

### ⚡ Tecnologias

#### 🐍 **Python**

* Django | Django REST Framework | Celery | FastAPI
* PostgreSQL | Redis | Elasticsearch
* Pytest | Poetry

#### ⚙️ **JavaScript / TypeScript**

* React | Next.js | Vue
* Node.js | Express | Adonis | Nest

#### 🦀 **Rust**

* Actix Web | Cargo | Tokio *(estudo em andamento)*

#### ☁️ **DevOps & Outros**

* Docker | Docker Compose | GitHub Actions
* AWS ECS | S3 | SES | SQS
* OpenAI API | LangChain | n8n
