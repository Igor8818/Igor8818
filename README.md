<div align="center">
  <img src="assets/banner_v4.jpg" alt="Igor Sena Hagge — Software Engineer (Full-Stack, Mobile & AI)" width="100%" />
  <br/><br/>
  <p>
    <a href="#-sobre-mim"><b>Sobre mim</b></a> &nbsp;&bull;&nbsp;
    <a href="#-projetos-em-destaque"><b>Projetos em destaque</b></a> &nbsp;&bull;&nbsp;
    <a href="#-demonstrações-visuais"><b>Demonstrações</b></a> &nbsp;&bull;&nbsp;
    <a href="#-engenharia--qualidade"><b>Engenharia & Qualidade</b></a> &nbsp;&bull;&nbsp;
    <a href="#-tecnologias"><b>Tecnologias</b></a> &nbsp;&bull;&nbsp;
    <a href="#-contato"><b>Contato</b></a>
  </p>
  <p>
    <a href="https://www.linkedin.com/in/igorhagge/">
      <img src="https://img.shields.io/badge/LinkedIn-Igor_Hagge-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:igor.senna2@hotmail.com">
      <img src="https://img.shields.io/badge/Email-igor.senna2%40hotmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <img src="https://img.shields.io/badge/Qualidade_%26_CI-254%2B_Testes_Automatizados-1B5E20?style=flat-square&logo=githubactions&logoColor=white" alt="254+ Testes Automatizados" />
  </p>
</div>

<details>
  <summary>🇺🇸 <b>Read in English — Quick Summary for Recruiters &amp; Engineering Teams</b></summary>
  <br/>
  <p>
    <b>Software Engineer</b> delivering end-to-end systems across <b>Enterprise Back-end (Java 21, Spring Boot 3, PostgreSQL, SQL Server)</b>, <b>Native &amp; Cross-Platform Mobile (Kotlin / Jetpack Compose &amp; React Native / Expo)</b>, <b>Modern Web (React 18, TypeScript, Tailwind CSS)</b>, and <b>Applied AI (On-Device Edge AI with YOLO / TensorFlow Lite &amp; Guardrailed LLMs)</b>.
  </p>
  <ul>
    <li><b>AgTech &amp; Edge AI Ecosystem (115 Automated Tests + CI):</b> Built <a href="https://github.com/Igor8818/CacauApp">CacauApp</a> + <a href="https://github.com/Igor8818/CacauSync">CacauSync API</a> for cacao genetic research at <b>CEPEC / CEPLAC</b> (940 trees, 104 clones, stateless JWT RBAC, idempotent HTTP/USB ADB sync, HTML5 Canvas YOLO auditing), and generalized the engine into <a href="https://github.com/Igor8818/BreedAI">BreedAI</a>, a standalone open-source multi-crop field phenotyping app inspired by Field Book.</li>
    <li><b>Full-Stack Product &amp; Database Security (139 Automated Tests + CI):</b> Created <a href="https://github.com/Igor8818/focuslift">FocusLift</a> (Java 21 + Spring Boot 3.4 + PostgreSQL 16 + React Native Offline-First + Gemini 2.5 Flash guarded by a deterministic Java math engine) and <a href="https://github.com/Igor8818/cacauapp2">CacauApp2</a> (Android Edge AI paired with <b>SQL Server 2025 RBAC, Row-Level Security, Dynamic Data Masking, SHA-256, and Covering Indexes</b> validated across 100,000 rows).</li>
    <li><b>Production Web Deliveries:</b> Shipped custom institutional web applications for real clients on Vercel &amp; Netlify (<a href="https://claudiafontesenfermagem.vercel.app">Claudia Fontes Clinic</a>, <a href="https://proftalesalmeida.com">Prof. Tales Almeida</a>, and <a href="https://github.com/Igor8818/BeatrizTeixeira">Beatriz Figueiredo Law</a>).</li>
  </ul>
</details>

---

## 👋 Sobre mim

**Engenheiro de Software** com entrega ponta a ponta em **Mobile Nativo & Multiplataforma (Kotlin / Jetpack Compose & React Native)**, **Back-end Corporativo (Java 21 / Spring Boot 3)**, **Front-end Web (React / TypeScript)**, **Engenharia de Dados Segura (PostgreSQL & SQL Server)** e **IA Aplicada (Edge AI com YOLO / TensorFlow Lite & LLMs)**.

Projeto e construo sistemas voltados a cenários reais exigentes — de aplicativos Android **100% Offline-First** com inferência de Visão Computacional embarcada em áreas rurais sem internet, a APIs REST corporativas com segurança *stateless* JWT, bancos relacionais com RBAC/RLS/migrações versionadas, auditoria visual em HTML5 Canvas e pipelines automatizados em **GitHub Actions CI**.

---

## 🚀 Projetos em destaque

### 1. Plataforma Open-Source & Ecossistema de Edge AI (**115 Testes Automatizados**)
> **Do Campo Institucional (CEPEC / CEPLAC) ao Produto Multi-Cultura:** O motor de Visão Computacional e Auditoria validado em pesquisa agronômica oficial (`CacauApp` + `CacauSync`) foi generalizado no **BreedAI**, um aplicativo standalone multi-culturas pronto para publicação na **Google Play**.

| Projeto | Arquitetura & Impacto Técnico | Stack & Qualidade |
| :--- | :--- | :--- |
| **[🧬 BreedAI](https://github.com/Igor8818/BreedAI)**<br/>*App Android Multi-Culturas (Open-Source • Play-Ready)* | Fenotipagem em campo inspirada no **Field Book** (`BreedAITheme` + `ModalNavigationDrawer` + 4 abas), **100% standalone e offline**. Possui motor **Universal YOLO/SSD** (`[1,C,N]`, `End2End NMS [1,N,6]`, `INT8`/`UINT8`/`FLOAT32`, leitura de metadados Ultralytics), parser nativo offline de **`.xlsx` (ZIP+SAX XML)**, *Traits* dinâmicos, importação/exportação de modelos em **`.zip`** e regras ProGuard/R8 para release. | `Kotlin 2.0` `Jetpack Compose` `CameraX` `TFLite` `YOLO Universal` `Excel .xlsx` **`31 Testes`** `CI` |
| **[🌱 CacauSync API](https://github.com/Igor8818/CacauSync)**<br/>*Back-end Corporativo & Painel Web React* | API RESTful corporativa em **Java 21 + Spring Boot 3.3** (integrada a SPA Web em **React 18 + TypeScript**) para planejamento de rotas (`.xlsx`/`.csv`), sincronização idempotente em lote (HTTP e ponte automática **USB ADB** em 1 clique), segurança *stateless* **JWT (RBAC)**, **PostgreSQL 16 + Flyway** e auditoria visual com caixas YOLO em **HTML5 Canvas + zoom**. | `Java 21` `Spring Boot 3.3` `React 18` `TypeScript` `PostgreSQL 16` `Flyway` `Docker` **`51 Testes JUnit 5`** `CI` |
| **[📱 CacauApp](https://github.com/Igor8818/CacauApp)**<br/>*Mobile Edge AI Fitossanitário (CEPEC / CEPLAC)* | App Android dedicado ao ensaio clonal `TC-1801` (104 clones, 940 plantas). Suporta **Pipeline Duplo simultâneo** (Contagem + Diagnóstico de *Sadio*, *Vassoura de Bruxa*, *Podridão Parda* e *Monilíase*) com **Letterbox isomórfico**, *snap* geométrico pós-captura, auditoria *Human-in-the-Loop* e sincronização em 1 clique com o laboratório. | `Kotlin 2.0` `Jetpack Compose` `CameraX` `TFLite` `YOLOv8` `OkHttp` **`33 Testes`** `CI` |

---

### 2. Produto Full-Stack Autoral & Engenharia de Banco de Dados (**139 Testes Automatizados**)

| Projeto | Arquitetura & Impacto Técnico | Stack & Qualidade |
| :--- | :--- | :--- |
| **[🏋️ FocusLift](https://github.com/Igor8818/focuslift)**<br/>*Full-Stack Mobile Offline-First & AI Coach* | Plataforma para progressão de cargas em treinos de força. Conecta cliente mobile **100% Offline-First (SQLite parametrizado)** a API REST em **Java 21 + Spring Boot 3.4** com sincronização bidirecional por *tombstones*, JWT, cálculo de 1RM e **AI Coach (Gemini 2.5 Flash)** blindado por motor determinístico em Java (`ProgressionMathEngine`) contra alucinações numéricas. | `Java 21` `Spring Boot 3.4` `PostgreSQL 16` `React Native` `Expo` `TypeScript` `SQLite` `Docker` `Gemini AI` **`81 Testes`** `CI` |
| **[🍫 CacauApp2](https://github.com/Igor8818/cacauapp2)**<br/>*Edge AI Offline & SQL Server 2025 Security/Tuning* | Arquitetura integrando aplicativo Android nativo (Letterbox + Gamma LUT para cabruca sombreada + WBF/IoS NMS) a um banco **SQL Server 2025** com **RBAC em 4 papéis (`GRANT`/`DENY`)**, **Row-Level Security (`RLS`)**, **Dynamic Data Masking (`DDM`) + `SHA-256`**, trilha de auditoria imutável, **Covering Indexes** validados com planos de execução sobre **100.000 registros** e ponte CLI Python anti-SQLi. | `SQL Server 2025` `T-SQL` `Kotlin` `CameraX` `Python` `RBAC / RLS / DDM` **`58 Testes`** |

---

### 3. Aplicações Web em Produção (Clientes)

* **[🩺 Claudia Fontes Enfermagem](https://github.com/Igor8818/Claudiaenfermagem)** — *Em produção ([claudiafontesenfermagem.vercel.app](https://claudiafontesenfermagem.vercel.app))*  
  Landing page institucional para consultório especializado com player de vídeo interativo, design responsivo e entrega via Edge CDN. (`HTML5` &bull; `Tailwind CSS` &bull; `JavaScript ES6+` &bull; `Vercel`)
* **[⚖️ Prof. Tales Almeida](https://github.com/Igor8818/tales)** — *Em produção ([proftalesalmeida.com](https://proftalesalmeida.com/))*  
  Website institucional e acervo acadêmico/jurídico desenvolvido sob encomenda em tema escuro com animações fluidas e pipeline de deploy contínuo. (`React` &bull; `Vite` &bull; `JavaScript` &bull; `CSS3` &bull; `GitHub Actions` &bull; `Netlify`)
* **[🏛️ Dra. Beatriz Figueiredo — Advocacia](https://github.com/Igor8818/BeatrizTeixeira)** — *Publicado ([igor8818.github.io/BeatrizTeixeira](https://igor8818.github.io/BeatrizTeixeira/))*  
  Website institucional modular desenvolvido para escritório jurídico com identidade visual de autoridade e layout responsivo. (`React` &bull; `Vite` &bull; `Tailwind CSS` &bull; `JavaScript`)

---

## 📸 Demonstrações visuais

<div align="center">
  <table>
    <tr>
      <td align="center" width="50%" colspan="2">
        <b>🧬 BreedAI — Plataforma Multi-Culturas &amp; Edge AI</b><br/><br/>
        <a href="https://github.com/Igor8818/BreedAI">
          <img src="assets/feature_breedai.jpg" width="680" alt="BreedAI — Multi-Crop Field Phenotyping &amp; Edge AI" />
        </a>
        <br/><br/>
        <img src="assets/screen_coleta_livre.png" width="195" alt="Tela Coleta Livre BreedAI" />
        &nbsp;&nbsp;
        <img src="assets/screen_menu_lateral.png" width="195" alt="Menu Lateral Field Book BreedAI" />
        &nbsp;&nbsp;
        <img src="assets/cacausync_auditoria.png" width="380" alt="Painel Web CacauSync" />
        <br/>
        <sub>UX agronômica inspirada no Field Book (esquerda/centro) e painel web de auditoria científica CacauSync (direita)</sub>
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <b>📱 CacauApp — Detecção YOLOv8 &amp; Auditoria Fitossanitária em Campo</b><br/><br/>
        <a href="https://github.com/Igor8818/CacauApp">
          <img src="https://raw.githubusercontent.com/Igor8818/CacauApp/main/docs/assets/cacauapp_deteccao_perfeita.jpg" width="230" alt="Detecção YOLOv8 CacauApp" />
          &nbsp;&nbsp;
          <img src="https://raw.githubusercontent.com/Igor8818/CacauApp/main/docs/assets/cacauapp_coleta_campo.png" width="230" alt="Coleta em Campo CacauApp" />
        </a>
        <br/>
        <sub>Inferência YOLOv8/TFLite on-device com snap geométrico pós-foto e classificação humana assistida 100% offline</sub>
      </td>
    </tr>
  </table>
</div>

---

## 🧠 Engenharia & Qualidade

* **Spec-Driven Development (SDD) & Contratos Cross-Stack:** Especificações formais (`docs/specs/SPEC-000` a `SPEC-003` + `REGRAS_DE_NEGOCIO.md`) assegurando concordância estrita entre payloads Android, CSV RFC 4180 e back-end Spring Boot.
* **Offline-First & Resiliência de Dados:** Persistência local com `AtomicFile` e SQLite parametrizado, chaves de idempotência contra quedas de rede e reconciliação bidirecional segura por *tombstones*.
* **Segurança & Otimização Relacional:** Controle de acesso baseado em papéis (`RBAC` via JWT e banco), `Row-Level Security (RLS)`, mascaramento dinâmico (`DDM`), migrações versionadas com **Flyway** e tuning com **Covering Indexes** medido em `STATISTICS IO/TIME` sobre **100.000+ linhas**.
* **Engine Edge AI On-Device & Guardrails de LLM:** Suporte unificado a modelos YOLO `FLOAT32`/`UINT8`/`INT8` e `End2End NMS [1,N,6]`, *Letterbox* isomórfico, reuso de buffers nativos e motores determinísticos em Java blindando respostas de IA generativa.
* **Testes & Integração Contínua:** **254+ testes automatizados** (`51` CacauSync + `33` CacauApp + `31` BreedAI + `81` FocusLift + `58` CacauApp2) e pipelines ativos em **GitHub Actions CI**.

---

## 🛠️ Tecnologias

| Área | Tecnologias & Ferramentas |
| :--- | :--- |
| **Back-end** | Java (21), Spring Boot 3, APIs RESTful, Spring Security (JWT), Spring Data JPA / Hibernate, Apache POI |
| **Front-end** | React 18, TypeScript, JavaScript (ES6+), Tailwind CSS, Vite, HTML5, CSS3 |
| **Mobile** | Kotlin 2.0, Jetpack Compose (Material 3), CameraX, React Native, Expo, Android SDK, Coroutines |
| **IA Aplicada** | Python, YOLOv8 / Universal YOLO, TensorFlow Lite (Edge AI On-Device), Google Gemini API, Spec-Driven Development |
| **Dados e DevOps** | PostgreSQL 16, SQL Server 2025 (RBAC, RLS, DDM), SQLite, H2, Docker, Docker Compose, Flyway Migrations |
| **Testes & CI** | JUnit 4/5, Mockito, AssertJ, Vitest, GitHub Actions CI, ProGuard/R8, Gradle, Maven, Git |

---

## 📬 Contato

* **LinkedIn:** [linkedin.com/in/igorhagge](https://www.linkedin.com/in/igorhagge/)
* **E-mail:** [igor.senna2@hotmail.com](mailto:igor.senna2@hotmail.com)
* **GitHub:** [github.com/Igor8818](https://github.com/Igor8818)
