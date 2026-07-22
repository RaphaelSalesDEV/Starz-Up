# 🎮 Starz Up — Online Gaming Tournament Platform

A full-featured web platform for organizing and managing competitive gaming tournaments. Built with vanilla JavaScript, CSS, and Firebase — no frameworks, no libraries.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-blue?style=flat-square)

---

## 📋 Overview

Starz Up is a competitive gaming tournament platform where players can register for championships, manage their virtual balance, interact with the community, and compete across multiple game titles. The platform includes real-time data sync via Firebase, role-based access control, and a full admin panel.

Developed as an Integrative Project for the Web Systems Development course at PUC Campinas, following Scrum methodology with 2-week sprints, requirement analysis, and multi-layer testing.

---

## ✨ Features

### User
- **Authentication** — Firebase Auth with signup, login, and session persistence
- **Tournament registration** — browse and join active tournaments
- **Virtual balance** — wallet system with balance validation on registration
- **Community page** — interact with other players
- **Interactive dashboard** — track stats, registrations, and tournament history

### Admin
- **Admin panel** — full CRUD for tournaments, users, and platform content
- **Permission control** — role-based access (user vs admin)
- **Tournament management** — create, edit, close, and manage championships

### Supported Games
| Game | Status |
|------|--------|
| CS2 | ✅ Available |
| VALORANT | ✅ Available |
| Rocket League | ✅ Available |
| Fortnite | ✅ Available |

---

## 🖼️ Screenshots

### Homepage
![Homepage](docs/screenshots/homepage.png)

### Community
![Community](docs/screenshots/community.png)

### Tournaments
![Tournaments](docs/screenshots/tournaments.png)

---

## 🔌 Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Backend** | Firebase (Auth, Realtime Database) |
| **Hosting** | Vercel |
| **Version Control** | Git + GitHub |
| **Methodology** | Scrum (2-week sprints) |

---

## 🚀 Getting Started

### Try it online

The project is deployed on Vercel:

🔗 **[starz-up.vercel.app](https://starz-up.vercel.app)**

> Create an account, explore the tournaments, and check the community page. Admin features require elevated permissions.

### Run locally

1. Clone the repository:
```bash
git clone https://github.com/RaphaelSalesDEV/Starz-Up.git
cd Starz-Up
```

2. Open `index.html` in any modern browser — no build step required.

3. Firebase credentials are managed via environment variables. Contact the maintainers for test credentials.

---

## 🏗️ Architecture
```
Starz-Up/
├── docs/                  # Documentation and assets
├── .gitignore             # OS, editor, and Firebase config exclusions
├── build-config.js        # Build and deploy configuration
├── vercel.json            # Vercel deployment settings
├── LICENSE                # MIT License
└── README.md              # You are here
```

### Firebase Integration
- **Authentication** — email/password signup and login with session persistence
- **Realtime Database** — live sync for tournament data, user balance, and community interactions
- **Security Rules** — role-based read/write permissions (user vs admin)
- **Environment Variables** — Firebase config protected via Vercel environment variables, never committed to the repo

---

## 📐 Methodology

This project was developed following **Scrum** as part of an Integrative Project at PUC Campinas:

| Practice | Description |
|----------|------------|
| **Sprints** | 2-week cycles with defined deliverables |
| **Role rotation** | Scrum Master and Product Owner roles rotated between team members |
| **Requirements** | Functional and non-functional requirements documented before implementation |
| **Testing** | Unit tests, exploratory tests, and system tests |
| **Documentation** | Technical documentation maintained throughout the project |

---

## 🗺️ Roadmap

| Phase | Description | Status |
|-------|-------------|--------|
| **1. Core Platform** | Auth, database, UI, tournaments, admin panel | ✅ Completed |
| **2. Testing** | Unit, exploratory, and system tests | ✅ Completed |
| **3. Deploy** | Vercel with environment variables | ✅ Completed |
| **4. Future Development** | Additional games, payment integration, mobile responsive | 🔄 Under evaluation |

> Future development depends on team decision. The project is fully functional as a completed semester deliverable.

---

## 👥 Contributors

| Contributor | Role |
|------------|------|
| **[Rafael Sanguini](https://github.com/rsanguini)** | Frontend development, UI/UX, authentication, dashboard, community page |
| **[Raphael Sales](https://github.com/RaphaelSalesDEV)** | Firebase integration, backend logic, admin panel, deployment |

---

## 👤 Author

**Rafael Sanguini Colagrossi** — Software Engineering Student

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rafaelsanguini)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rsanguini)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://rafaelsanguini.vercel.app)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rafaelcolagrossi@gmail.com)

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

⭐ If this project was helpful, leave a star — it means a lot!
