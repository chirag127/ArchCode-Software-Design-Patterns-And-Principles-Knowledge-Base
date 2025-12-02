# ArchCode: Software Design & Architectural Knowledge Base

<p align="center">
  <a href="https://github.com/chirag127/ArchCode-Software-Design-Patterns-And-Principles-Knowledge-Base/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/chirag127/ArchCode-Software-Design-Patterns-And-Principles-Knowledge-Base/ci.yml?branch=main&label=Markdown%20Lint&style=flat-square" alt="Markdown Lint"></a>
  <a href="https://github.com/chirag127/ArchCode-Software-Design-Patterns-And-Principles-Knowledge-Base/blob/main/LICENSE"><img src="https://img.shields.io/github/license/chirag127/ArchCode-Software-Design-Patterns-And-Principles-Knowledge-Base?style=flat-square&color=blueviolet" alt="License"></a>
  <a href="#"><img src="https://img.shields.io/badge/Tech-Markdown-blue.svg?style=flat-square" alt="Tech Stack"></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-Maintained-green.svg?style=flat-square" alt="Status"></a>
  <a href="https://github.com/chirag127/ArchCode-Software-Design-Patterns-And-Principles-Knowledge-Base/stargazers"><img src="https://img.shields.io/github/stars/chirag127/ArchCode-Software-Design-Patterns-And-Principles-Knowledge-Base?style=flat-square&color=gold" alt="GitHub Stars"></a>
</p>

<p align="center">
  <em>A definitive, developer-centric knowledge base for mastering essential software design patterns and architectural principles. This repository provides a structured, comprehensive reference to elevate code quality, ensure maintainability, and accelerate learning for developers at all levels.</em>
</p>

<p align="center">
  <a href="https://github.com/chirag127/ArchCode-Software-Design-Patterns-And-Principles-Knowledge-Base/stargazers"><strong>Star ⭐ this Repo</strong></a> to support its development and help others discover it!
</p>

---

## Table of Contents

- [Architectural Vision](#architectural-vision)
- [Core Principles](#core-principles)
- [Design Patterns (Gang of Four)](#design-patterns-gang-of-four)
- [How to Contribute](#how-to-contribute)
- [AI Agent Directives](#-ai-agent-directives)
- [License](#license)

## Architectural Vision

This repository is organized as a hierarchical knowledge base, designed for clarity and progressive learning. The structure separates high-level principles from concrete pattern implementations, allowing for both quick reference and deep study.

text
.
├── PRINCIPLES/
│   ├── SOLID/
│   │   ├── 01-Single-Responsibility.md
│   │   ├── 02-Open-Closed.md
│   │   ├── 03-Liskov-Substitution.md
│   │   ├── 04-Interface-Segregation.md
│   │   └── 05-Dependency-Inversion.md
│   ├── DRY.md
│   ├── KISS.md
│   └── YAGNI.md
│
├── PATTERNS/
│   ├── 01-CREATIONAL/
│   │   ├── Abstract-Factory.md
│   │   ├── Builder.md
│   │   ├── Factory-Method.md
│   │   ├── Prototype.md
│   │   └── Singleton.md
│   ├── 02-STRUCTURAL/
│   │   ├── Adapter.md
│   │   ├── Bridge.md
│   │   ├── Composite.md
│   │   ├── Decorator.md
│   │   ├── Facade.md
│   │   ├── Flyweight.md
│   │   └── Proxy.md
│   └── 03-BEHAVIORAL/
│       ├── Chain-of-Responsibility.md
│       ├── Command.md
│       ├── Interpreter.md
│       ├── Iterator.md
│       ├── Mediator.md
│       ├── Memento.md
│       ├── Observer.md
│       ├── State.md
│       ├── Strategy.md
│       ├── Template-Method.md
│       └── Visitor.md
│
├── .github/
├── LICENSE
└── README.md


## Core Principles

Foundational guidelines that inform high-quality software architecture.

- **SOLID**: A mnemonic acronym for five design principles intended to make software designs more understandable, flexible, and maintainable.
- **DRY (Don't Repeat Yourself)**: A principle of software development aimed at reducing repetition of software patterns, replacing it with abstractions or using data normalization to avoid redundancy.
- **KISS (Keep It Simple, Stupid)**: A design principle that states that most systems work best if they are kept simple rather than made complicated; therefore, simplicity should be a key goal in design, and unnecessary complexity should be avoided.
- **YAGNI (You Ain't Gonna Need It)**: The principle that functionality should not be added until deemed necessary.

## Design Patterns (Gang of Four)

Categorized solutions to commonly occurring problems within a given context in software design.

- **Creational Patterns**: Provide object creation mechanisms that increase flexibility and reuse of existing code.
- **Structural Patterns**: Explain how to assemble objects and classes into larger structures, while keeping these structures flexible and efficient.
- **Behavioral Patterns**: Concerned with algorithms and the assignment of responsibilities between objects.

## How to Contribute

Contributions are welcome! This knowledge base thrives on community collaboration. To contribute, please follow these steps:

1.  **Fork the Repository**: Create your own copy of the project.
2.  **Create a New Branch**: `git checkout -b feature/add-new-pattern`
3.  **Make Your Changes**: Add or improve content. Ensure your writing is clear, concise, and follows the existing format.
4.  **Lint Your Files**: Run `npx markdownlint .` to check for formatting errors.
5.  **Commit Your Changes**: `git commit -m 'feat: Add explanation for Strategy Pattern'`
6.  **Push to Your Branch**: `git push origin feature/add-new-pattern`
7.  **Open a Pull Request**: Submit your changes for review.

## 🤖 AI Agent Directives

<details>
<summary><strong>SYSTEM: APEX TECHNICAL AUTHORITY (DECEMBER 2025 EDITION)</strong></summary>

### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards.
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed documentation updates and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

### 2. CONTEXT-AWARE APEX STACKS (LATE 2025 STANDARDS)
This repository, `ArchCode-Software-Design-Patterns-And-Principles-Knowledge-Base`, is a technical knowledge base. Your primary function is to maintain its integrity, clarity, and structure.

*   **PRIMARY SCENARIO: KNOWLEDGE MANAGEMENT & TECHNICAL DOCUMENTATION**
    *   **Stack:** This project is built entirely with **Markdown**. Content quality is enforced by **markdownlint** for consistency and **Prettier** for formatting. Your goal is to produce exceptionally clear and well-structured technical documentation.
    *   **Architecture:** The repository follows a strict **Information Architecture** based on a hierarchical, topic-based structure. Content is categorized into `PRINCIPLES` and `PATTERNS` to facilitate discoverability and logical grouping. You must preserve this structure.
    *   **Writing Style:** All content must be authoritative, concise, and technically precise. Use code examples (in a language like Python, TypeScript, or Java) only where they directly clarify a concept. All new entries must follow the established formatting of existing documents.

*   **VERIFICATION & LINTING COMMANDS**
    *   To ensure content quality before any commit, you must execute these commands:
    *   `npx markdownlint . --fix` - To check and fix all markdown files for style and syntax violations.
    *   `npx prettier --write .` - To enforce a consistent code and text format across the project.

</details>

---

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://github.com/chirag127/ArchCode-Software-Design-Patterns-And-Principles-Knowledge-Base/blob/main/LICENSE).
