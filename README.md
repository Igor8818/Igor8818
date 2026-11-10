# Igor Hagge

Engenheiro de Software com atuação ponta a ponta em **Engenharia Mobile (Android Nativo com Kotlin & Jetpack Compose / React Native)**, **Back-end Corporativo (Java 21 & Spring Boot 3)** e **Engenharia de Inteligência Artificial (Edge AI & Deterministic LLM Workflows)**.

Construo sistemas resilientes do mundo real — desde aplicações *Offline-First* com inferência de Visão Computacional (YOLOv8 via TensorFlow Lite) operando 100% desconectadas em campo, até APIs corporativas com persistência relacional, segurança stateless, testes automatizados e orquestração multi-agente guiada por especificações formais (SDD).

---

### 💼 Ecossistema em Destaque: CEPEC / CEPLAC

Solução integrada ponta a ponta desenvolvida para pesquisa agronômica e fenotipagem digital de cacaueiros:

- **[📱 CacauApp — Visão Computacional Offline-First & Auditoria](https://github.com/Igor8818/CacauApp)**  
  Aplicativo Android nativo para o **Centro de Pesquisas do Cacau (CEPEC/CEPLAC)** para automação de contagem biométrica e diagnóstico fitossanitário em campo:
  - Detecção fitossanitária *on-device* via modelos **YOLOv8 (TensorFlow Lite Float32)** com pré-processamento geométrico (*Letterboxing isomórfico*) e aceleração por CPU multithread e GPU Delegate;
  - Tela de revisão interativa (*Human-in-the-Loop*) para classificação individual de frutos (*Sadio*, *Vassoura de Bruxa*, *Podridão Parda*) e ajuste dinâmico de caixas delimitadoras;
  - Operação 100% offline com **Modo Rota guiada por planilhas (*FieldBook*)**, georreferenciamento GPS e exportação CSV padronizada (RFC 4180);
  - Sincronização assíncrona HTTP/OkHttp com envio em lote de leituras e fotos com correção de orientação EXIF e controle anti-OOM;
  - Concorrência blindada com snapshots atômicos no disparo da câmera contra *race conditions*.  
  `Kotlin 2.0` &bull; `Jetpack Compose` &bull; `CameraX` &bull; `TensorFlow Lite` &bull; `YOLOv8` &bull; `Coroutines` &bull; `Material 3` &bull; `MVVM`

- **[🌱 CacauSync API — Back-end Corporativo & Auditoria Científica](https://github.com/Igor8818/CacauSync)**  
  API RESTful e painel web para centralização, validação e auditoria fitossanitária de ensaios genéticos (ex: ensaio competitivo TC-1801):
  - Ingestão em lote via JSON (com coordenadas YOLO normalizadas) e multipart CSV + Fotos com **chaves de idempotência estrita** contra duplicidades em conexões instáveis;
  - Autenticação *stateless* com **Spring Security 6 e JWT Bearer** (RBAC: Coordenador de Genética e Pesquisador de Campo);
  - Banco relacional **PostgreSQL 16** com migrações versionadas via **Flyway**, validação de contratos com **Jakarta Bean Validation** e armazenamento seguro de fotos em disco;
  - Revisão visual humana com sobreposição de caixas YOLO em HTML5 Canvas e cálculo automatizado de taxas de infecção e produtividade por clone;
  - Suíte de **39 testes automatizados com JUnit 5, Mockito e AssertJ** com 100% de aprovação e containerização completa com **Docker & Docker Compose**.  
  `Java 21` &bull; `Spring Boot 3.3` &bull; `PostgreSQL 16` &bull; `Flyway` &bull; `Spring Security (JWT)` &bull; `Docker` &bull; `JUnit 5` &bull; `Mockito` &bull; `OpenAPI / Swagger`

---

### 🏋️ Engenharia Full-Stack & Inteligência Artificial

- **[🏋️ FocusLift — Full-Stack Gym Progression & AI Analytics Platform](https://github.com/Igor8818/focuslift)**  
  Plataforma Full-Stack para musculação de alta performance e sobrecarga progressiva, unindo cliente mobile *Offline-First* a uma API corporativa em nuvem:
  - **Back-end Corporativo em Java 21 & Spring Boot 3.4:** API RESTful stateless protegida por **Spring Security 6 e tokens JWT**, banco relacional **PostgreSQL 16**, migrações versionadas com **Flyway**, documentação OpenAPI/Swagger e containerização completa com **Docker & Docker Compose**;
  - **Motor Determinístico & AI Coach (Anti-Alucinação):** Integração com **Google Gemini 2.5 Flash** blindada por motor em Java (`ProgressionMathEngine`), calculando 1RM (fórmula de Brzycki), delta de volume semanal (*tonnage*) e detecção de platôs de carga antes da injeção de contexto no LLM;
  - **Sincronização Idempotente com Tombstones:** Protocolo bidirecional que reconcilia alterações offline do SQLite com a nuvem, com resolução de conflitos por timestamp e tratamento seguro de exclusões lógicas (*tombstones*);
  - **Mobile Client Offline-First:** Interface fluida em **React Native (Expo SDK 57)** operando 100% offline via **SQLite local** (queries parametrizadas contra SQL Injection), comparador de séries em tempo real, calculadora visual de anilhas por algoritmo guloso e i18n nativo para 5 idiomas.  
  `Java 21` &bull; `Spring Boot 3.4` &bull; `PostgreSQL 16` &bull; `Docker` &bull; `Spring Security (JWT)` &bull; `React Native` &bull; `Expo SDK 57` &bull; `TypeScript` &bull; `SQLite` &bull; `Gemini AI`

---

### 🧠 AI Engineering & Spec-Driven Development (SDD 2.0)

Aplicação prática de metodologias modernas de **Engenharia de Software Assistida por IA**:
- **Arquitetura Multi-Agente & Auditoria Cega (Zero-Context Dual-Agent Review):** Desenvolvimento orientado a contratos de arquitetura congelados (`docs/specs/SPEC-XXX.md`), coordenado por agentes de execução e auditado de forma independente por subagentes de contexto zero para eliminação de viés de confirmação e blindagem contra *race conditions*;
- **Edge AI & Otimização On-Device:** Conversão de modelos neurais para TFLite com quantização, NMS customizado e reuso de buffers nativos de memória.

---

### 🚀 Outros Projetos

- **[Claudia Fontes Enfermagem](https://github.com/Igor8818/Claudiaenfermagem)** — Landing page profissional para consultório médico especializado com player de vídeo interativo e entrega via Edge CDN. (`Tailwind CSS`, `JavaScript ES6+`, `Vercel`).
- **[Tales Almeida](https://github.com/Igor8818/tales)** — Website institucional e acervo científico para jurista em Dark Theme com animações de rolagem. (`HTML5`, `CSS3`, `JavaScript`).

---

### 🛠️ Tecnologias & Habilidades

* **Linguagens:** Kotlin, Java (21), TypeScript, JavaScript (ES6+), SQL, Python
* **Mobile:** Android SDK, Jetpack Compose, CameraX, React Native, Expo, Coroutines, StateFlow, Room / SQLite, MVVM
* **Back-end & DevOps:** Spring Boot 3, Spring Data JPA, Spring Security (JWT), APIs RESTful, PostgreSQL, Flyway, Docker, Docker Compose, Swagger/OpenAPI
* **Inteligência Artificial:** TensorFlow Lite, YOLOv8, Edge AI on-device, Google Gemini API (Anti-Hallucination Prompting), Spec-Driven Development (SDD), Orquestração de Agentes / LLMs
* **Qualidade de Software:** JUnit 5, Mockito, AssertJ, Vitest, Git, GitHub Actions, Gradle, Maven, Android Studio

---

### 📬 Contato

* **LinkedIn:** [linkedin.com/in/igorhagge](https://www.linkedin.com/in/igorhagge/)
* **E-mail:** [igor.senna2@hotmail.com](mailto:igor.senna2@hotmail.com)
* **GitHub:** [@Igor8818](https://github.com/Igor8818)
