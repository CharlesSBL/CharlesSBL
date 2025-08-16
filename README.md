# 👋 Hi, I’m Karol!
### Software Architect & Full-Stack Developer
I’m a passionate software creator specializing in designing and building complex, efficient, and scalable systems. My work focuses on bridging high-level architectural vision with low-level implementation to deliver solutions that are not only technically elegant but also pragmatic and effective.
- 🔭 Currently exploring the performance frontiers in **Rust** and **GraalVM Native Image**.
- 🌱 Honing my skills in **declarative system management** using **NixOS**.
- 💬 Happy to discuss **software architecture, compiler theory, distributed systems, and AI modeling**.

---
## 🚀 About Me
As a developer, I navigate between different paradigms and ecosystems—from low-level system programming in **Rust** and **C**, to building robust enterprise applications in **Java (Spring Boot)**, to crafting dynamic interfaces in **TypeScript/React**.
I’m fascinated by performance optimization, automation, and creating reproducible development environments, reflected in my projects using **GraalVM**, **Docker**, and **NixOS**. I believe the best software emerges at the intersection of deep computer science fundamentals and a practical approach to solving real-world problems.

---
## 💻 Tech Stack
<table>
  <tr>
    <td valign="top" width="50%">
      <strong>Programming Languages</strong><br>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
      <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust">
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
      <img src="https://img.shields.io/badge/Nix-5277C3?style=for-the-badge&logo=nixos&logoColor=white" alt="Nix">
    </td>
    <td valign="top" width="50%">
      <strong>Backend & Databases</strong><br>
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot">
      <img src="https://img.shields.io/badge/Actix_Web-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Actix Web">
      <img src="https://img.shields.io/badge/REST_API-0277BD?style=for-the-badge&logo=api-platform&logoColor=white" alt="REST API">
      <img src="https://img.shields.io/badge/GraalVM-19B4DE?style=for-the-badge&logo=graalvm&logoColor=white" alt="GraalVM">
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <strong>Frontend</strong><br>
      <img src="https://img.shields.io/badge/-ReactJs-61DAFB?logo=react&logoColor=white&style=for-the-badge" alt="React">
      <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js">
      <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white" alt="Redux">
      <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
      <img src="https://img.shields.io/badge/HTML5_Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Canvas">
      <img src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="SCSS">
    </td>
    <td valign="top" width="50%">
      <strong>DevOps, Systems & Tools</strong><br>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
      <img src="https://img.shields.io/badge/NixOS-5277C3?style=for-the-badge&logo=nixos&logoColor=white" alt="NixOS">
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
      <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white" alt="Maven">
      <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">
      <img src="https://img.shields.io/badge/Shell_Scripting-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Shell Scripting">
    </td>
  </tr>
</table>

---
## 📂 My Projects
Below is a detailed overview of my most important work. Projects are grouped thematically to showcase the breadth of my skills.

### I. System Architecture & Conceptual Projects
*In this section, I present deep technical explorations that go beyond standard implementation. These are case studies and architectural specifications demonstrating the ability to design complex systems from scratch.*

<details>
<summary><strong>Project Nexus: Specification for a Unified Programming Language</strong></summary>
> **Project Goal:** Design and specify a new programming language (`.nx`) and its ecosystem. The aim is to create a successor that synthesizes the performance of C, the productivity of Python, and the asynchronicity of JavaScript into a single coherent paradigm.
>
> **Key Architectural Concepts:**
> - **Unified Intermediate Representation (UIR):** The core system—a common intermediate representation into which code from various languages is compiled, enabling unprecedented optimizations.
> - **Library Ingestor (`nexlink`):** A tool for transpiling existing libraries (C, Python, JS) into the native `.nexlib` format, eliminating the need for FFI (Foreign Function Interface).
> - **Polyglot Optimizer:** An advanced optimizer capable of cross-language transformations, such as inlining a Python function directly into a Nexus loop.
> - **Dual Memory Model:** Default safe memory management (ARC + GC) with the ability to switch to a `perf {}` block with manual allocation and borrow-checking inspired by Rust.
>
> **Project Value:** Demonstrates deep understanding of **compiler theory, language design, operating systems, and complex software architecture**.
</details>

<details>
<summary><strong>Project Phoenix: Hybrid Desktop Application Architecture</strong></summary>
> **Project Goal:** Design a hybrid desktop application architecture that combines **instant startup and low memory usage** (characteristic of native apps) with **the speed and flexibility of web UI development**.
>
> **Key Architectural Concepts:**
> - **Native Backend (AOT Compilation):** Backend in **Spring Boot** compiled to a native binary using **GraalVM Native Image**, ensuring startup in a fraction of a second.
> - **Java Frontend:** User interface written in Java, then compiled to high-performance JavaScript/WebAssembly using tools like `J2CL`.
> - **Desktop Shell:** Minimalist **JavaFX** application with a `WebView` component that renders the web frontend, running on a standard JVM.
> - **Strict API Contract:** Shared Maven module with DTOs, ensuring type safety and serving as a formal contract between client and server.
>
> **Project Value:** Shows the ability to design **complex, multi-module systems**, knowledge of advanced compilation techniques, and making informed architectural trade-offs.
</details>

<details>
<summary><strong>Architectural Case Studies (Startups as Technical Ideas)</strong></summary>
> These projects are technical analyses of business problems, presented as ready-made architectural concepts for hypothetical startups.
>
> 1. **Intellexa - Market Intelligence from AI Conversations:**
>    - **Problem:** Companies have millions of AI chatbot logs ("dark data") that are an untapped resource.
>    - **Technical Solution:** Three-tier SaaS platform (B2B). **Tier 1 (Ignite):** Analytical dashboard with PII anonymization and topic clustering. **Tier 2 (Accelerate):** Adds API for insights and benchmarking. **Tier 3 (Apex):** Introduces Fine-Tuning as a Service (FaaS) and dedicated data strategist support. Architecture based on microservices, stream processing, and NLP models.
>
> 2. **Integrit Labs - Integration as a Service:**
>    - **Problem:** Engineers waste valuable time integrating and maintaining external SDKs (Stripe, Twilio, Scandit), instead of focusing on product development.
>    - **Technical Solution:** Integration services company evolving into a platform. **Phase 1:** Expert services (fixed-price). **Phase 2:** Premium WordPress plugin (`Integrit Connect`). **Phase 3:** Creation of `Integrit API`—a unified "API to API" that becomes the main SaaS product.
>
> 3. **LearnSphere Academy - EdTech Platform:**
>    - **Problem:** Need for a professional, engaging educational platform.
>    - **Technical Solution:** Landing page design and initial system architecture. Frontend in **Next.js** (for SEO and performance), backend as a **Headless CMS** (e.g., Strapi) for content management (courses, tutors) and API for handling registrations and consultations. Future integration with **SphereLabs AI**—a custom LLM module for personalized learning.
>
> **Project Value:** Demonstrates the ability to **translate business needs into concrete technical solutions** and think about scalability and monetization.
</details>

### II. Full-Stack & Web Applications
<details>
<summary><strong>Self-Hosted AI Chat (Rust & React)</strong></summary>
> **Description:** Fully functional, locally hosted AI chat application. Backend written in **Rust (Actix Web)** uses the `llama-cpp-2` library for inference on LLM models (GGUF format) without external APIs. Frontend built in **React** and **TypeScript** provides a modern, responsive interface.
>
> **Key Features:**
> - No dependency on external APIs—100% privacy.
> - Conversation context management.
> - High performance thanks to native backend.
>
> **Technologies:** `Rust`, `Actix Web`, `llama.cpp`, `React`, `TypeScript`, `Vite`.
</details>

<details>
<summary><strong>Pizza Store - E-commerce Application (SPA)</strong></summary>
> **Description:** Modern Single-Page Application (SPA) simulating a pizza store. Implemented dynamic product search and filtering (`lodash.debounce`), advanced sorting, cart management, and **PayPal** payment integration.
>
> **Key Features:**
> - State management with **Redux Toolkit**.
> - State synchronization with URL and `localStorage`.
> - Loading optimization via Code Splitting (`React.lazy`).
>
> **Technologies:** `React`, `TypeScript`, `Redux Toolkit`, `SCSS`, `PayPal API`.
</details>

<details>
<summary><strong>Data Dashboard - Data Visualization Platform</strong></summary>
> **Description:** Full-stack application for collecting, processing, and visualizing personal data from various sources. Backend in **Python** periodically fetches and aggregates data. Frontend in **Next.js** delivers interactive charts and filters for data exploration.
>
> **Key Features:**
> - Automated backend tasks.
> - Server-side rendering (SSR) for high performance.
>
> **Technologies:** `Python`, `Next.js`, `React`, `Data Visualization`.
</details>

### III. Systems, Tools & DevOps
<details>
<summary><strong>Nixrach: Declarative NixOS System Configuration</strong></summary>
> **Description:** Comprehensive, fully reproducible **NixOS** system configuration using **Flakes** and **Home-Manager**. Manages the entire development environment—from kernel to window manager (**Hyprland**), applications, aliases, and scripts.
>
> **Key Features:**
> - "Infrastructure as Code" applied to the workstation.
> - Modular structure for different hosts (desktop, laptop).
> - Full automation and reproducibility.
>
> **Technologies:** `Nix`, `NixOS`, `Flakes`, `Home-Manager`, `Hyprland`, `Waybar`.
</details>

<details>
<summary><strong>envdev: Developer Environment Manager</strong></summary>
> **Description:** Native CLI tool (Java + GraalVM) orchestrating a containerized development environment based on **RHEL**. Automatically manages configuration and lifecycle of containers (developer tools + web-based VS Code), providing isolated and reproducible work environments.
>
> **Key Features:**
> - Instant startup thanks to native compilation.
> - Dual-container architecture (tools + IDE).
> - Full automation via `docker-compose`.
>
> **Technologies:** `Java`, `GraalVM Native Image`, `Docker`, `Docker Compose`, `Picocli`.
</details>

### IV. Simulations & Artificial Intelligence
<details>
<summary><strong>2D Real-Time Battle Simulator</strong></summary>
> **Description:** Interactive 2D battle simulator with autonomous AI units that independently seek enemies, engage in combat, and react to battlefield conditions. The project uses object-oriented architecture and **HTML5 Canvas API** for real-time rendering.
>
> **Key Features:**
> - Intelligent agent behavior (targeting, pursuit).
> - Combat system based on HP and armor.
> - Dynamic UI with real-time updates.
>
> **Technologies:** `TypeScript`, `HTML5 Canvas API`, `Object-Oriented Programming`.
</details>

<details>
<summary><strong>Mind-Simulator: Competitive Learning System</strong></summary>
> **Description:** **Java/Spring Boot** application simulating an environment where simple, "generic" learning cells compete for data processing. Cells that successfully process data strengthen and develop specializations, demonstrating emergence and system self-organization.
>
> **Key Features:**
> - Competition for resources (data) and specialization.
> - Evolutionary cycle (metabolism, death, birth).
> - Agent-based architecture.
>
> **Technologies:** `Java`, `Spring Boot`, `Agent-Based Modeling`.
</details>

### V. Libraries & Smaller Projects
- **Collection of 15 Pure JavaScript Projects:** Small applications demonstrating in-depth knowledge of fundamental JavaScript mechanisms, DOM manipulation, and event handling without frameworks.
- **Telegram Bot in Java:** Simple Telegram bot written in Java using the Spring framework, demonstrating integration with external APIs.
- **Rust CLI Utility Suite:** Collection of command-line tools in Rust, including programs for secure file copying and CSV processing.
- **StructUI:** Lightweight, class-based UI library written in TypeScript and run with `bun.js`.

---
I’m always open to new challenges and interesting projects. If my work interests you, feel free to reach out!
