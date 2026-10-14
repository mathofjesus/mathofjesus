# Matheus Costa de Jesus

**Estudante de Ciência da Computação** | **Operador de Máquinas (8 anos)** | **Foco: Cibersegurança & Forward Deployed Engineering**

---

## 🎯 Perfil Profissional

Estudante de Ciência da Computação (6º semestre, EAD) com **8 anos de experiência operacional** em ambiente industrial (M. Dias Branco). Atualmente cursando **CS50x (Harvard)** e construindo portfólio com foco em:

- **Cibersegurança** — análise de vulnerabilidades, hardening, segurança de memória, programação segura
- **Forward Deployed Engineering** — integração de sistemas, troubleshooting em produção, automação, observabilidade
- **Engenharia de Sistemas** — C/C++, Linux, redes, programação de baixo nível, arquitetura de software

**Localização:** Lauro de Freitas, BA, Brasil  
**Contato:** matheuscojesus@gmail.com | +55 71 99608-0859  
**Links:** [GitHub](https://github.com/mathofjesus) • [LinkedIn](https://linkedin.com/in/matheus-costa-de-jesus) • [X/Twitter](https://x.com/mathofjesus)

---

## 🛠️ Stack Tecnológica

### Linguagens Principais
| Linguagem | Uso Principal |
|-----------|---------------|
| **C** | Sistemas, memória, redes, Linux/POSIX, segurança, engenharia reversa |
| **C++** | Estruturas de dados, STL, concorrência, sistemas de maior escala, ML do zero |
| **Python** | Automação, scripting, análise, IA/ML, ferramentas de segurança |
| **Java** | Backend enterprise, Spring Boot, sistemas financeiros (formação/legado) |
| **SQL** | Persistência relacional, otimização, integração |

### Ecossistema de Desenvolvimento
- **Build/Compilação:** GCC, Clang, CMake, Make, Maven
- **Debug/Análise:** GDB, Valgrind, AddressSanitizer, UBSan, ThreadSanitizer, perf
- **Versionamento:** Git, GitHub, GitHub Actions (CI/CD)
- **Containerização:** Docker, Docker Compose
- **Bancos:** PostgreSQL, Redis, libpq
- **Redes/Protocolos:** TCP/IP, HTTP, TLS, sockets, epoll
- **Testes:** Criterion, JUnit 5, Mockito, TestContainers, Playwright

### Áreas de Foco Atual
- Segurança de memória (buffer overflow, use-after-free, integer overflow)
- Programação de sistemas Linux (syscalls, file descriptors, IPC, signals)
- Criptografia aplicada, TLS, parsing seguro
- Fuzzing, análise estática/dinâmica, sanitizers
- Arquitetura de sistemas distribuídos, mensageria, cloud

---

## 🚀 Projetos em Destaque

### [SecureLens](https://github.com/mathofjesus/SecureLens) ⭐ **Projeto Principal de Portfólio**
**C/C++ • Cybersecurity • Machine Learning • Docker • CI/CD**

Plataforma que combina **análise de vulnerabilidades em dependências** (via API OSV) com **classificação de sentimentos** implementada do zero em C++ (TF-IDF + Logistic Regression).

**Destaques técnicos:**
- Parser de dependências: `requirements.txt`, `package.json`, `pom.xml`
- Cliente HTTP assíncrono com `libcurl` para API OSV
- ML from scratch: tokenizer, TF-IDF, logistic regression, serialização de modelo
- API REST + CLI unificadas
- Hardening: validação de paths, limites de arquivo, timeouts, sem execução de código alheio
- Testes com Criterion, sanitizers (ASan/UBSan/TSan), CI no GitHub Actions

**Stack:** C++17, C11, CMake, libcurl, nlohmann/json, tinyxml2, Docker

---

### [Gestor de Finanças Pessoais](https://github.com/mathofjesus/gestor-de-financas-pessoais) ⭐ **Produção**
**Java 21 • Spring Boot 3.5 • PostgreSQL • JWT • Docker • TestContainers**

Plataforma financeira full-stack com **rigor empresarial**: precisão monetária (BigDecimal), autenticação JWT com rotação de tokens (versioning), proteção CSRF double-submit, optimistic locking (`@Version`), validação de segredos no startup, bloqueio por força bruta, SSR com Thymeleaf, PWA offline.

**Arquitetura:** Maven multi-module (`financeapp-core` + `financeapp-api`)  
**Testes:** 80%+ cobertura, TestContainers (PostgreSQL real), MockMvc  
**CI/CD:** GitHub Actions, Docker Compose, Flyway migrations

---

### [Encurtador de URLs](https://github.com/mathofjesus/Encurtador) 🧪 **Systems Programming**
**C • epoll • Redis • PostgreSQL • Docker Sandbox**

URL shortener construído para **praticar programação de sistemas** e **medir gaps de capacidade** entre requisitos e hardware restrito (1 vCPU, 4 GB RAM, 50 GB NVMe).

**Implementação própria:**
- HTTP server assíncrono com reactor `epoll` + connection buffering
- Parser HTTP/1.1, rate limiting token-bucket, cache Redis (`hiredis`)
- Connection pool PostgreSQL (`libpq`), métricas Prometheus, JSON logging
- Sandbox Docker que **impõe** os limites de hardware (CFS quota, cgroups)

**Análise de capacidade documentada:** requisitos de 100M URLs/dia e retenção 10 anos **não cabem** no hardware — o projeto expõe a aritmética e os limites reais (throughput, disco, HA).

---

### [Dashboard](https://github.com/mathofjesus/Dashboard) 📊 **C Systems**
**C • Make • Binário nativo ~107KB**

Dashboard de métricas/sistema em C puro. Build com `Makefile`, foco em desempenho e footprint mínimo.

---

### [CS50x](https://github.com/mathofjesus/CS50x) 🎓 **Formação**
**C • Harvard CS50x**

Exercícios e problem sets do curso CS50x (Harvard) — fundamentos de C, algoritmos, memória, estruturas de dados, web, SQL, Python.

---

### [docker-sandbox](https://github.com/mathofjesus/docker-sandbox) 🧰 **Tooling / Agent Skill**
**TypeScript/Node • Docker • Apache-2.0**

Skill para agentes de IA (Claude Code, Cursor, Codex, Hermes) executarem testes e protótipos em **containers descartáveis** — host limpo, isolamento total. Suporta: TypeScript (React/Vue/Preact + Vitest/Jest), Playwright E2E, Java 21 + Spring Boot (Maven/Gradle), PostgreSQL 15.

---

## 📦 Outros Projetos no GitHub

| Repositório | Linguagem | Descrição |
|-------------|-----------|-----------|
| [Portfolio](https://github.com/mathofjesus/Portfolio) | TypeScript | Portfolio web completo |
| [notificador-de-precos](https://github.com/mathofjesus/notificador-de-precos) | Java | Monitoramento de preços |
| [memory-game](https://github.com/mathofjesus/memory-game) | TypeScript | React Native + Expo + Jest |
| [visual-query-builder](https://github.com/mathofjesus/visual-query-builder) | TypeScript | Construtor visual de queries |
| [ComparadorDeInvestimentosRendaFixa](https://github.com/mathofjesus/ComparadorDeInvestimentosRendaFixa) | Java | LCA/LCI vs Tesouro Direto |
| [Sistema_de_Bibliotecas](https://github.com/mathofjesus/Sistema_de_Bibliotecas) | Java | Sistema acadêmico |
| [Zoo](https://github.com/mathofjesus/Zoo) | Java | Controle de zoológico |
| [Agenda-de-Contatos](https://github.com/mathofjesus/Agenda-de-Contatos) | HTML | Projeto concluído |
| [EstruturasDeControle](https://github.com/mathofjesus/EstruturasDeControle) | — | Exercícios de faculdade |

> **Total:** 25 repositórios públicos • 30 stars • Foco crescente em C/C++ e sistemas

---

## 🎓 Formação & Certificações

- **Ciência da Computação** — 6º semestre (EAD) — *em andamento*
- **CS50x** — Harvard (Introduction to Computer Science) — *em andamento*
- **Voxy Proficiency Certificate** — Inglês (B1 Intermediário)
- **Experiência profissional:** 9 anos como Operador de Máquinas (M. Dias Branco) — automação industrial, KPIs, documentação técnica, conformidade de segurança, equipes multidisciplinares

---

## 🎯 Objetivos de Carreira (Próximos 12–24 meses)

1. **Cibersegurança** — Security Engineer, AppSec, SecOps, Threat Research
2. **Forward Deployed Engineer** — Integração cliente-produção, troubleshooting, automação, arquitetura
3. **Engenharia de Sistemas/Backend** — Rust/Go/C++ em sistemas distribuídos, infraestrutura, performance

**Empresas de interesse:** ANPD, Google, IBM, Nubank, Banco do Brasil, Santander, startups de segurança/infra

---

## 📚 Princípios de Desenvolvimento

- **Fundamentos primeiro:** C/C++ para entender o que linguagens de alto nível abstraem
- **Segurança por design:** validação de entrada, ownership explícito, sanitizers sempre
- **Observabilidade nativa:** logs estruturados, métricas, tracing desde o início
- **Projetos como sistemas reais:** não apenas exercícios — arquitetura, testes, CI, deploy, documentação
- **Aprendizado progressivo:** conceito → código mínimo → compilação → execução → debug → análise → sistema maior

---

## 🤝 Como Me Encontrar

- **Email:** matheuscojesus@gmail.com
- **LinkedIn:** [linkedin.com/in/matheus-costa-de-jesus](https://linkedin.com/in/matheus-costa-de-jesus)
- **GitHub:** [github.com/mathofjesus](https://github.com/mathofjesus)
- **X/Twitter:** [x.com/mathofjesus](https://x.com/mathofjesus)

---

> *"A programação é a ferramenta; o entendimento de sistemas, redes, memória e segurança é o diferencial."*  
> — Construindo base sólida em C/C++ para atuar em segurança e engenharia de sistemas reais.