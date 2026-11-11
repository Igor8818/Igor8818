<div align="center">
  <img src="assets/banner.png" alt="Igor Sena Hagge — Software Engineer (Full-Stack, Mobile & AI)" width="100%" />
  <br/><br/>
  <p>
    <a href="#-sobre-mim"><b>Sobre mim</b></a> &nbsp;&bull;&nbsp;
    <a href="#-projetos-em-destaque"><b>Projetos em destaque</b></a> &nbsp;&bull;&nbsp;
    <a href="#-demonstrações-visuais"><b>Demonstrações</b></a> &nbsp;&bull;&nbsp;
    <a href="#-tecnologias"><b>Tecnologias</b></a> &nbsp;&bull;&nbsp;
    <a href="#-contato"><b>Contato</b></a>
  </p>
</div>

---

## 👋 Sobre mim

Olá! Sou desenvolvedor de software com experiência na construção de aplicações full-stack, back-end, front-end e mobile, além de soluções com inteligência artificial aplicada e visão computacional.

Desenvolvo sistemas que integram aplicações web, APIs REST, bancos de dados e dispositivos móveis, utilizando tecnologias como **Java**, **Spring Boot**, **Kotlin**, **React**, **React Native**, **TypeScript** e **Python**.

Tenho interesse em diferentes áreas da engenharia de software e busco oportunidades para contribuir com soluções reais, aprender continuamente e evoluir profissionalmente.

---

## 🚀 Projetos em destaque

### 1. Ecossistema de Pesquisa Agronômica — CEPEC / CEPLAC
> **Contexto Institucional:** Solução integrada (Mobile + API + Painel Web) desenvolvida como projeto de pesquisa aplicada e validação em campo para o **Centro de Pesquisas do Cacau (CEPEC/CEPLAC)**, voltada à fenotipagem digital em quadras experimentais sem sinal de internet.

| Projeto | Papel & Arquitetura | Stack Principal |
| :--- | :--- | :--- |
| **[🌱 CacauSync API](https://github.com/Igor8818/CacauSync)**<br/>*Full-Stack: Back-end & Painel Web* | API RESTful corporativa e SPA Web em React para planejamento de rotas (`.xlsx`/`.csv`), sincronização idempotente em lote (HTTP e ponte USB ADB em 1 clique), autenticação stateless JWT (RBAC) e conferência visual de fotos com caixas YOLO em HTML5 Canvas. Conta com **51 testes automatizados (JUnit 5, Mockito e AssertJ)**. | `Java 21` `Spring Boot 3.3` `React 18` `TypeScript` `Tailwind CSS` `PostgreSQL 16` `Flyway` `Docker` `JUnit 5` |
| **[📱 CacauApp](https://github.com/Igor8818/CacauApp)**<br/>*Mobile: Android Nativo & Edge AI* | Aplicativo Android *Offline-First* para contagem e classificação fitossanitária de frutos de cacau em campo usando **YOLOv8 (TensorFlow Lite)** no dispositivo, revisão interativa (*Human-in-the-Loop*), Modo Rota guiado por planilha, geolocalização GPS e exportação/sincronização em lote. | `Kotlin 2.0` `Jetpack Compose` `CameraX` `TensorFlow Lite` `YOLOv8` `Coroutines` `Material 3` `MVVM` |

### 2. Plataforma Full-Stack Autoral
> **Contexto:** Produto autoral completo (Mobile + API REST em nuvem) projetado para demonstrar arquitetura Full-Stack moderna, sincronização offline-first e integração determinística com IA.

| Projeto | Papel & Arquitetura | Stack Principal |
| :--- | :--- | :--- |
| **[🏋️ FocusLift](https://github.com/Igor8818/focuslift)**<br/>*Full-Stack Gym & AI Analytics* | Plataforma para rastreamento de treinos e sobrecarga progressiva. Une um app mobile **100% Offline-First (SQLite)** a uma **API REST em Java 21 & Spring Boot 3.4** com sincronização bidirecional via *tombstones*, autenticação JWT e *AI Coach* (**Gemini 2.5 Flash**) apoiado por motor matemático determinístico em Java (`ProgressionMathEngine`). | `Java 21` `Spring Boot 3.4` `PostgreSQL 16` `React Native` `Expo` `TypeScript` `SQLite` `Docker` `Gemini AI` |

### 3. Aplicações Web em Produção (Trabalhos para Clientes)
> **Contexto Comercial:** Projetos contratados e entregues em produção para profissionais liberais e consultórios.

* **[🩺 Claudia Fontes Enfermagem](https://github.com/Igor8818/Claudiaenfermagem)** — *Em produção ([claudiafontesenfermagem.vercel.app](https://claudiafontesenfermagem.vercel.app))*  
  Landing page institucional para consultório especializado, com player de vídeo interativo, design responsivo e deploy em Edge CDN. (`HTML5` • `Tailwind CSS` • `JavaScript ES6+` • `Vercel`)
* **[⚖️ Prof. Tales Almeida](https://github.com/Igor8818/tales)** — *Em produção ([proftalesalmeida.com](https://proftalesalmeida.com/))*  
  Website institucional e acervo acadêmico/jurídico desenvolvido sob encomenda com tema escuro e animações fluidas. (`HTML5` • `CSS3` • `JavaScript`)

---

## 📸 Demonstrações visuais

<div align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <b>🌱 CacauSync — Painel Web de Auditoria com IA</b><br/><br/>
        <a href="https://github.com/Igor8818/CacauSync">
          <img src="assets/cacausync_auditoria.png" width="460" alt="Painel Web de Auditoria Fitossanitária CacauSync" />
        </a>
        <br/>
        <sub>Conferência de fotos sequenciais com marcação de caixas delimitadoras YOLO em HTML5 Canvas, edição interativa de frutos e aprovação em 1 clique</sub>
      </td>
      <td align="center" width="50%">
        <b>📱 CacauApp — Visão Computacional On-Device & Campo</b><br/><br/>
        <a href="https://github.com/Igor8818/CacauApp">
          <img src="https://raw.githubusercontent.com/Igor8818/CacauApp/main/docs/assets/cacauapp_deteccao_perfeita.jpg" width="220" alt="Detecção YOLOv8 CacauApp" />
          <img src="https://raw.githubusercontent.com/Igor8818/CacauApp/main/docs/assets/cacauapp_coleta_campo.png" width="220" alt="Coleta em Campo CacauApp" />
        </a>
        <br/>
        <sub>Detecção de frutos on-device com YOLOv8/TFLite e Modo Rota guiado por planilha para operação 100% desconectada</sub>
      </td>
    </tr>
  </table>
</div>

---

## 🛠️ Tecnologias

| Área | Tecnologias & Ferramentas |
| :--- | :--- |
| **Back-end** | Java (21), Spring Boot 3, APIs RESTful, Spring Security (JWT), Spring Data JPA / Hibernate |
| **Front-end** | React, TypeScript, JavaScript (ES6+), Tailwind CSS, Vite, HTML5, CSS3 |
| **Mobile** | Kotlin, Jetpack Compose, React Native, Expo, Android SDK, CameraX |
| **IA Aplicada** | Python, YOLOv8, TensorFlow Lite (Edge AI On-Device), Google Gemini API |
| **Dados e DevOps** | PostgreSQL 16, SQLite, H2, Docker, Docker Compose, Flyway Migrations |
| **Testes & Qualidade** | JUnit 5, Mockito, AssertJ, GitHub Actions, Git |

---

## 📬 Contato

* **LinkedIn:** [linkedin.com/in/igorhagge](https://www.linkedin.com/in/igorhagge/)
* **E-mail:** [igor.senna2@hotmail.com](mailto:igor.senna2@hotmail.com)
* **GitHub:** [github.com/Igor8818](https://github.com/Igor8818)
