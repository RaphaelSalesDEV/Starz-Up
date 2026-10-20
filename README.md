# 🎮 Starz Up — Plataforma de Torneios Online de Jogos

Uma plataforma web completa para organizar e gerenciar torneios competitivos de jogos. Desenvolvida com JavaScript puro, CSS e Firebase — sem frameworks ou bibliotecas externas.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Licença](https://img.shields.io/badge/Licen%C3%A7a-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-blue?style=flat-square)

---

## 📋 Visão geral

O **Starz Up** é uma plataforma de torneios competitivos de jogos na qual os jogadores podem se inscrever em campeonatos, gerenciar seu saldo virtual, interagir com a comunidade e competir em diferentes títulos.

A plataforma conta com sincronização de dados em tempo real por meio do Firebase, controle de acesso baseado em funções e um painel administrativo completo.

O projeto foi desenvolvido como um Projeto Integrador da disciplina de Desenvolvimento de Sistemas Web da PUC Campinas, seguindo a metodologia Scrum, com sprints de duas semanas, análise de requisitos e testes em múltiplas camadas.

---

## ✨ Funcionalidades

### 👤 Usuário

- **Autenticação** — Firebase Authentication com cadastro, login e persistência de sessão.
- **Inscrição em torneios** — visualização e participação em torneios ativos.
- **Saldo virtual** — sistema de carteira com validação de saldo durante as inscrições.
- **Página da comunidade** — interação entre os jogadores da plataforma.
- **Painel interativo** — acompanhamento de estatísticas, inscrições e histórico de torneios.

### 🛡️ Administrador

- **Painel administrativo** — operações CRUD completas para torneios, usuários e conteúdos da plataforma.
- **Controle de permissões** — acesso baseado em funções, diferenciando usuários comuns e administradores.
- **Gerenciamento de torneios** — criação, edição, encerramento e administração de campeonatos.

### 🎮 Jogos disponíveis

| Jogo | Status |
|---|---|
| Counter-Strike 2 (CS2) | ✅ Disponível |
| VALORANT | ✅ Disponível |
| Rocket League | ✅ Disponível |
| Fortnite | ✅ Disponível |

---

## 🖼️ Capturas de tela

### Página inicial

![Página inicial](docs/screenshots/homepage.png)

### Comunidade

![Página da comunidade](docs/screenshots/community.png)

### Torneios

![Página de torneios](docs/screenshots/tournaments.png)

---

## 🔌 Tecnologias utilizadas

| Camada | Tecnologia |
|---|---|
| **Frontend** | HTML5, CSS3 e JavaScript puro |
| **Backend e serviços** | Firebase Authentication e Realtime Database |
| **Hospedagem** | Vercel |
| **Controle de versão** | Git e GitHub |
| **Metodologia de desenvolvimento** | Scrum, com sprints de duas semanas |

---

## 🚀 Como executar o projeto

### Experimente online

O projeto está hospedado na Vercel:

🔗 **[Acessar o Starz Up](https://starz-up.vercel.app)**

> Crie uma conta, explore os torneios e acesse a página da comunidade. As funcionalidades administrativas exigem permissões elevadas.

### Execute localmente

**1. Clone o repositório:**

```bash
git clone https://github.com/RaphaelSalesDEV/Starz-Up.git
cd Starz-Up
```

**2. Abra o arquivo `index.html` em qualquer navegador moderno.**

Não é necessário executar um processo de build para abrir a interface.

**3. Configure as credenciais do Firebase.**

As credenciais do Firebase são gerenciadas por variáveis de ambiente. Entre em contato com os responsáveis pelo projeto para obter credenciais de teste.

---

## 🏗️ Arquitetura do projeto

```text
Starz-Up/
├── docs/                  # Documentação e recursos visuais
├── .gitignore             # Exclusões de arquivos do sistema, editor e Firebase
├── build-config.js        # Configuração de build e implantação
├── vercel.json            # Configurações de implantação na Vercel
├── LICENSE                # Licença MIT
└── README.md              # Documentação principal do projeto
```

### Integração com Firebase

- **Autenticação** — cadastro e login com e-mail e senha, incluindo persistência de sessão.
- **Realtime Database** — sincronização de dados de torneios, saldo dos usuários e interações da comunidade em tempo real.
- **Regras de segurança** — permissões de leitura e escrita baseadas em funções, diferenciando usuários comuns e administradores.
- **Variáveis de ambiente** — configuração do Firebase protegida por variáveis de ambiente na Vercel, sem ser incluída diretamente no repositório.

---

## 📐 Metodologia de desenvolvimento

O projeto foi desenvolvido seguindo a metodologia **Scrum**, como parte de um Projeto Integrador da PUC Campinas.

| Prática | Descrição |
|---|---|
| **Sprints** | Ciclos de duas semanas com entregas definidas. |
| **Rotação de funções** | As funções de Scrum Master e Product Owner foram alternadas entre os integrantes da equipe. |
| **Requisitos** | Requisitos funcionais e não funcionais documentados antes da implementação. |
| **Testes** | Testes unitários, exploratórios e de sistema. |
| **Documentação** | Documentação técnica mantida durante todo o desenvolvimento. |

---

## 🗺️ Roadmap

| Etapa | Descrição | Status |
|---|---|---|
| **1. Plataforma principal** | Autenticação, banco de dados, interface, torneios e painel administrativo. | ✅ Concluída |
| **2. Testes** | Testes unitários, exploratórios e de sistema. | ✅ Concluída |
| **3. Implantação** | Hospedagem na Vercel com variáveis de ambiente. | ✅ Concluída |
| **4. Desenvolvimento futuro** | Novos jogos, integração de pagamentos e melhorias na responsividade mobile. | 🔄 Em avaliação |

> O desenvolvimento futuro depende de decisões da equipe. O projeto está funcional e foi concluído como entrega de um projeto acadêmico semestral.

---

## 👥 Colaboradores

| Colaborador | Responsabilidades |
|---|---|
| **[Rafael Sanguini](https://github.com/rsanguini)** | Desenvolvimento frontend, UI/UX, autenticação, painel interativo e página da comunidade. |
| **[Raphael Sales](https://github.com/RaphaelSalesDEV)** | Integração com Firebase, lógica de backend, painel administrativo e implantação. |

---


## 📄 Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter mais informações.

---

⭐ Se este projeto foi interessante para você, considere deixar uma estrela no repositório!
