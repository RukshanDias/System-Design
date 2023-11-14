# System Design

### Content

1. [What is Software Architect](https://github.com/RukshanDias/System-Design/tree/WorkingBranch#whats-software-architect)
2. The Architectural mindset
3. The Architecture process
4. Working with System Requirements
5. Types of Applications
6. Selecting Tech-Stacks
7. Components Architecture
8. Design Patterns
9. System Architecture
10. Other Considerations

---

## What's Software Architect

### 3 main types of architectures

-   Infrastructure Architect
    -   Designs the infrastructure of system (all non-software elements).
    -   This includes Servers, VMs, Networks, Storage, etc:
    -   He should be familiar with system requirements.
-   Software Architect
    -   Also called as Solution, System architect.
    -   Responsible for the architecture of the software.
-   Enterprise Architect
    -   These people works with the top management.
    -   No development-oriented tasks.

### Responsibility of architect

-   "Developer knows what CAN be done - architect knows what SHOULD be done"
-   Baseline Requirements: **Fast, Secure, Reliable, Easy to maintain**

### Organizational Chart of an architect

-   ![Architect organization chart](imgs/architect%20organisation%20chart.png)
-   Career Paths:
    -   Dev -> Architect : common in small companies, >3 years of experience
    -   Dev -> Team Lead -> Jr.Architect / Proj.Manager : Common path
    -   Dev -> Team Lead -> Proj.Manager -> Sr.Architect : Can become an enterprise architect

---

## The Architectural mindset
- Areas to focus on :
    - Weakness
    - Strengths
    - Competition
    - Growth Strategy
    - Understanding the true north

---

## The Architecture process
### Steps:
![architectural process setps](imgs/architectural%20process.png)

1. Understand system requirements
    - 'What the system should Do'
    - Defined by system analyst
2. Understand non-functional requirements
    - Technical & service level attributes.
    - eg: Loads, volumes, performance
    - Much more important than regular reqirements.
    - Should be discussed with clients & system analyst.
3. Map components
    - Represent tasks of the system.
    - A simple idea on how the system should work.
    - 2 Goals:
        - Understand system functionality.
        - Communicate your understanding to the client.
4. Select Tech-stack
    - For Backend, FrontEnd and DataStore
    - Have to consider lot of factors when selecting.
5. Design architecture
    - Qualities of a well designed system:
        - loose coupling
        - Stateless
        - Scaling
        - Caching & more..
6. Write architecture document
    - Describes the full process of the system.
    - Must be relevent for all participent.

---

