# EduConnect Sierra Leone

> A Digital Public Good platform connecting students, graduates, mentors, employers, and scholarship providers across Sierra Leone.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status: In Development](https://img.shields.io/badge/Status-In%20Development-blue.svg)]()
[![SDLC: Waterfall](https://img.shields.io/badge/SDLC-Waterfall-orange.svg)]()

---

## Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [System Architecture](#system-architecture)
- [System Design Artifacts](#system-design-artifacts)
- [Prototype Screens](#prototype-screens)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Stakeholders](#stakeholders)
- [Development Methodology](#development-methodology)
- [Contributing](#contributing)
- [Team](#team)
- [License](#license)

---

## Overview

**EduConnect Sierra Leone** is a centralized digital ecosystem designed to bridge the gap between opportunity and access for students and graduates in Sierra Leone. The platform aggregates scholarships, internships, jobs, mentorship programs, and learning resources in one place — removing the friction of searching across scattered websites, institutions, and social media channels.

This project was developed as part of the **Principles of Software Engineering (PROG102)** course at **Limkokwing University of Creative Technology, Sierra Leone**, with an emphasis on real-world software engineering practices: system analysis, UML modeling, database design, architecture planning, and UI prototyping.

---

## Problem Statement

Students and graduates in Sierra Leone face significant barriers when trying to access educational and career development opportunities. Information is fragmented across multiple platforms, institutions, and informal networks — meaning many qualified individuals miss scholarships, internships, and jobs simply because they had no reliable way to find them.

EduConnect Sierra Leone addresses this by providing a single, accessible platform that connects all relevant stakeholders in one digital space.

---

## Objectives

- Provide a **centralized hub** for educational and career opportunities
- Enable easy **discovery of scholarships and internships**
- Connect users with **experienced mentors** in their field
- Improve access to **curated learning resources**
- Facilitate **direct communication** between students, employers, and providers
- Enhance **youth employability** through technology
- Support **sustainable development** goals within Sierra Leone

---

## Key Features

### For Students & Graduates

| Feature | Description |
|---|---|
| Registration & Login | Secure account creation and authentication |
| Scholarship Search | Browse and filter scholarship opportunities |
| Internship Search | Discover internship postings from verified employers |
| Job Search | Find full-time and part-time employment listings |
| Mentor Directory | Browse mentors by industry, expertise, and availability |
| Mentorship Requests | Send and manage mentorship connection requests |
| Learning Resources | Access curated educational content and materials |
| Notifications | Receive timely alerts on new opportunities |
| Profile Management | Manage personal details, skills, and applications |

### For Administrators

| Feature | Description |
|---|---|
| User Management | Oversee accounts across all user types |
| Opportunity Management | Add, edit, and remove listings |
| Resource Management | Curate and maintain the learning resource library |
| Platform Monitoring | Track usage, activity, and system health |

---

## Technology Stack

| Layer | Technologies |
|---|---|
| **Frontend** | Flutter, React |
| **Backend** | Node.js, PHP |
| **Database** | MySQL |
| **Design** | Figma, Draw.io |
| **Version Control** | Git, GitHub |

---

## System Architecture

The platform follows a **three-layer architecture**:

```
┌─────────────────────────────────────────┐
│           Presentation Layer            │
│      Web Interface · Mobile App         │
├─────────────────────────────────────────┤
│           Application Layer             │
│  Auth · Scholarships · Jobs ·           │
│  Mentorship · Notifications             │
├─────────────────────────────────────────┤
│              Data Layer                 │
│  Users · Scholarships · Job Listings ·  │
│  Mentorship Requests · Resources        │
└─────────────────────────────────────────┘
```

---

## System Design Artifacts

The project includes a comprehensive set of design artifacts:

### UML Diagrams
- Use Case Diagram
- Activity Diagram
- Sequence Diagram
- Class Diagram
- State Diagram

### Database Design
- Entity Relationship Diagram (ERD)

### Data Flow Modeling
- DFD Level 0 — Context Diagram
- DFD Level 1

### Architecture
- System Architecture Diagram
- Network Diagram

### Project Planning
- Gantt Chart

All diagrams and documentation are located in the [`Documentation/`](Documentation/) directory.

---

## Prototype Screens

A high-fidelity Figma prototype covers the full user journey across 15 screens:

1. Splash Screen
2. Welcome Screen
3. Login Screen
4. Registration Screen
5. Dashboard Screen
6. Scholarships Screen
7. Jobs Screen
8. Internships Screen
9. Learning Resources Screen
10. Mentor Directory Screen
11. Mentor Profile Screen
12. My Applications Screen
13. Notifications Screen
14. Profile Settings Screen
15. Admin Dashboard Screen

> Prototype files are available in [`Prototype/Figma_Designs/`](Prototype/Figma_Designs/).

---

## Getting Started

> **Note:** The platform is currently in the design and prototyping phase. Full development setup instructions will be added as the project progresses.

### Prerequisites

- Node.js v18+
- PHP 8+
- MySQL 8+
- Flutter SDK
- Git

### Clone the Repository

```bash
git clone https://github.com/your-org/EduConnect-Sierra-Leone.git
cd EduConnect-Sierra-Leone
```

### Backend Setup

```bash
cd Backend
npm install        # for Node.js services
# or
composer install   # for PHP services
```

### Frontend Setup

```bash
cd Frontend
flutter pub get    # for mobile
npm install        # for web (React)
```

### Database Setup

```bash
cd Database
mysql -u root -p < schema.sql
```

---

## Repository Structure

```
EduConnect-Sierra-Leone/
│
├── Documentation/
│   ├── Final_Report.docx
│   ├── UML_Diagrams/
│   ├── DFDs/
│   ├── ERD/
│   └── Architecture/
│
├── Prototype/
│   ├── Figma_Designs/
│   └── Screenshots/
│
├── Frontend/
├── Backend/
├── Database/
├── Assets/
└── README.md
```

---

## Stakeholders

The platform is designed to serve six key groups:

- **Students** — access opportunities and resources
- **Graduates** — find employment, mentorship, and further education
- **Mentors** — share expertise and guide the next generation
- **Employers** — post internships and job opportunities
- **Scholarship Providers** — list and manage scholarship offerings
- **Administrators** — manage the platform and its content

---

## Development Methodology

This project follows the **Waterfall SDLC** model, progressing through clearly defined phases:

1. **Planning** — Define scope, goals, and feasibility
2. **Requirements Analysis** — Gather and document stakeholder needs
3. **System Design** — Create architecture, UML, ERD, and UI prototypes
4. **Development** — Build frontend, backend, and database components
5. **Testing** — Validate functionality, usability, and performance
6. **Deployment** — Launch the platform for public access
7. **Maintenance** — Monitor, update, and improve over time

---

## Contributing

Contributions are welcome. To get started:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "Add: your feature description"`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a Pull Request for review

Please ensure your code follows the project's existing conventions and that any new features are documented.

---

## Team

Developed by students of the **Principles of Software Engineering (PROG102)** course at **Limkokwing University of Creative Technology, Sierra Leone**.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

*EduConnect Sierra Leone — Learn • Connect • Grow*
