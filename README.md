# 🏛️ Object-Oriented Programming (OOPs) Repository

<p align="center">
  <img src="https://img.shields.io/badge/Paradigm-OOP-blue?style=for-the-badge&logo=architecture" alt="OOP Paradigm"/>
  <img src="https://img.shields.io/badge/Maintained-Yes-success?style=for-the-badge" alt="Maintained"/>
  <img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge" alt="Contributions Welcome"/>
</p>

---

## 🗺️ Core Architecture & Roadmap

```mermaid
graph TD
    OOP[Object-Oriented Programming] --> Pillars[4 Core Pillars]
    OOP --> Principles[SOLID Principles]
    OOP --> Design[Design Patterns]

    Pillars --> Encapsulation[Encapsulation]
    Pillars --> Inheritance[Inheritance]
    Pillars --> Polymorphism[Polymorphism]
    Pillars --> Abstraction[Abstraction]

    Principles --> S[Single Responsibility]
    Principles --> O[Open/Closed]
    Principles --> L[Liskov Substitution]
    Principles --> I[Interface Segregation]
    Principles --> D[Dependency Inversion]

    style OOP fill:#2c3e50,stroke:#34495e,stroke-width:2px,color:#fff
    style Pillars fill:#2980b9,stroke:#3498db,stroke-width:2px,color:#fff
    style Principles fill:#27ae60,stroke:#2ecc71,stroke-width:2px,color:#fff
    style Design fill:#8e44ad,stroke:#9b59b6,stroke-width:2px,color:#fff
```
---

| Pillar | Concept Visualization | Visual Code Blueprint |
| :--- | :--- | :--- |
| **Encapsulation** | 🔒 Data Hiding & Bundling | `[ Data + Methods ] ➔ 💊 Capsule (Class)` |
| **Inheritance** | 🌿 Parent-Child Hierarchy | `Base Class ➔ ⏬ Extended ➔ Derived Class` |
| **Polymorphism** | 🎭 One Interface, Many Forms | `Execute() ➔ ⚡ Method Overriding / Overloading` |
| **Abstraction** | 🔍 Hiding Details, Showing Essentials | `User Interface ➔ 🛠️ [ Hidden Implementation ]` |

---

### 📐 SOLID Principles Implementation Status
- [ ] S - Single Responsibility Principle [ 🟩 Done ]

- [ ] O - Open/Closed Principle [ 🟩 Done ]

- [ ] L - Liskov Substitution Principle [ 🟨 In Progress ]

- [ ] I - Interface Segregation Principle [ 🟥 Planned ]

- [ ] D - Dependency Inversion Principle [ 🟥 Planned ]

---
### 🤝 Contribution Workflow
```shell
gitGraph
    commit id: "Initial Commit"
    branch feature-oop
    checkout feature-oop
    commit id: "Add OOP Concept"
    commit id: "Fix Structural Code"
    checkout main
    merge feature-oop
    commit id: "Release v1.0"
```
