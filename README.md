# Igor Hagge

Desenvolvedor de Software focado em **Engenharia Mobile (Android Nativo Kotlin & React Native)**, **Back-end Corporativo (Java 21 / Spring Boot 3)** e **Visão Computacional Embarcada (Edge AI)**.

Trabalho na concepção e entrega de sistemas de alto desempenho do mundo real — desde aplicações operando 100% offline com inferência de inteligência artificial em campo, até APIs resilientes com arquiteturas limpas, testes automatizados e integração em nuvem.

---

### 💼 Ecossistema em Destaque: CEPEC / CEPLAC

Solução integrada de ponta a ponta desenvolvida para pesquisa agronômica e melhoramento genético de cacaueiros:

- **[📱 CacauApp (Mobile + Edge AI)](https://github.com/Igor8818/CacauApp)**  
  Aplicativo Android nativo desenvolvido para o **Centro de Pesquisas do Cacau (CEPEC/CEPLAC)** para auditoria e contagem biométrica em campo:
  - Detecção fitossanitária on-device a 30+ FPS via modelos **YOLOv8 (TensorFlow Lite)** com aceleração por CPU multithread e GPU Delegate;
  - Tela de revisão interativa (*Human-in-the-Loop*) permitindo classificação individual de frutos (*Sadio*, *Vassoura de Bruxa*, *Podridão Parda*) e marcações manuais;
  - Operação 100% offline com Modo Rota guiada por planilhas (*FieldBook*), georreferenciamento GPS e exportação CSV (RFC 4180);
  - Sincronização direta com a API central via HTTP/OkHttp com correção de orientação EXIF e controle anti-OOM.  
  `Kotlin 2.0` &bull; `Jetpack Compose` &bull; `CameraX` &bull; `TensorFlow Lite` &bull; `YOLOv8` &bull; `Material 3` &bull; `MVVM`

- **[🌱 CacauSync API (Back-end Corporativo)](https://github.com/Igor8818/CacauSync)**  
  API REST central para ingestão de coletas de campo, upload de fotos e consolidação estatística de ensaios agronômicos:
  - Arquitetura limpa em camadas, imutabilidade com `Java Records` e tratamento de erros padronizado (**RFC 7807**);
  - Ingestão em lote via JSON (com caixas delimitadoras) e CSV, garantindo **idempotência estrita** contra duplicidades;
  - Banco relacional PostgreSQL 16 com migrações versionadas via **Flyway** e testes unitários/integração com **JUnit 5 + Mockito** (35 testes aprovados);
  - Segurança *stateless* com Bearer Token JWT e containerização completa com **Docker & Docker Compose**.  
  `Java 21` &bull; `Spring Boot 3.3` &bull; `PostgreSQL 16` &bull; `Flyway` &bull; `Spring Security (JWT)` &bull; `Docker` &bull; `JUnit 5`

---

### 🚀 Outros Projetos Relevantes

- **[FocusLift](https://github.com/Igor8818/focuslift)** — App mobile *Offline-First* para progressão de cargas na musculação com sincronização incremental `SQLite ↔ Cloud Firestore`, detecção de PRs, 5 idiomas e monetização In-App via RevenueCat. (`React Native`, `Expo`, `TypeScript`, `SQLite`, `Vitest`).
- **[Claudia Fontes Enfermagem](https://github.com/Igor8818/Claudiaenfermagem)** — Landing page profissional médica com player de vídeos interativo e entrega via Edge CDN. (`Tailwind CSS`, `JavaScript ES6+`, `Vercel`).
- **[Tales Almeida](https://github.com/Igor8818/tales)** — Website institucional e acervo científico para jurista em Dark Theme com animações de rolagem. (`HTML5`, `CSS3`, `JavaScript`).

---

### 🛠️ Tecnologias & Domínios

* **Linguagens:** Kotlin, Java (21), TypeScript, JavaScript (ES6+), SQL
* **Mobile:** Android SDK, Jetpack Compose, CameraX, React Native, Expo, MVVM, Coroutines, StateFlow, Room / SQLite
* **Back-end & Cloud:** Spring Boot 3, Spring Data JPA, Spring Security (JWT), RESTful APIs, PostgreSQL, Flyway, Docker, Docker Compose, Firebase
* **IA & Visão Computacional:** TensorFlow Lite, YOLOv8, Edge AI on-device, processamento de imagem com ExifInterface e matrizes de rotação
* **Qualidade & Ferramentas:** JUnit 5, Mockito, AssertJ, Git, GitHub Actions, Gradle, Maven, Android Studio, VS Code

---

### 📬 Contato

* **LinkedIn:** [linkedin.com/in/igorhagge](https://www.linkedin.com/in/igorhagge/)
* **E-mail:** [igor.senna2@hotmail.com](mailto:igor.senna2@hotmail.com)
* **GitHub:** [@Igor8818](https://github.com/Igor8818)
