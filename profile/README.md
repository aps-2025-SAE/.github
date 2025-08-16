# 📅 Sistema de Agendamento de Eventos (SAE)

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)  
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)  
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)  
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white)  
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?logo=tailwind-css&logoColor=white)  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)  
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)  

> Plataforma integrada para **gestão completa de eventos**, unindo administração, secretariado e experiência do cliente final.

---

## 🌟 Contexto e Motivação
O **SAE** nasceu da necessidade de modernizar e centralizar o processo de agendamento de eventos, que muitas vezes é fragmentado, burocrático e suscetível a falhas de comunicação.  
A ideia é oferecer uma solução **única, intuitiva e eficiente**, capaz de atender desde pequenas instituições até organizações maiores, garantindo **agilidade no atendimento**, **organização interna** e **experiência fluida para o cliente**.

---

## 🎯 Objetivo
O **SAE** oferece um ecossistema de aplicações que facilita:
- O **agendamento e gerenciamento de eventos**.
- A comunicação entre clientes, administradores e secretários.
- Uma **experiência intuitiva** com interfaces modernas e responsivas.

---

## 🔑 Principais Funcionalidades

### Para Clientes
- Consulta de eventos disponíveis.  
- Solicitação de agendamentos online.  
- Visualização do status e detalhes do evento.  

### Para Administradores
- Criação, edição e exclusão de eventos.  
- Acompanhamento de métricas e relatórios.  

### Para Secretários
- Aprovação ou rejeição de solicitações.  
- Gestão de agenda e calendário.  
- Comunicação direta com clientes via plataforma.  

---

## 🏗 Arquitetura Geral
A solução segue uma **arquitetura multicamadas**:
- **Apresentação** → Frontends modernos (React e Next.js)  
- **Aplicação** → Lógica e orquestração das funcionalidades  
- **Domínio** → Regras de negócio centrais  
- **Persistência** → Banco MySQL + ORM Eloquent  

---

## 🛠 Tecnologias Utilizadas
| Camada | Tecnologias |
|--------|-------------|
| **Backend** | [Laravel](https://laravel.com/) · API REST · JWT · MySQL · ORM Eloquent |
| **Frontend Admin** | [React](https://react.dev/) · TypeScript · [Shadcn](https://ui.shadcn.com/docs/installation) · [TailwindCSS](https://tailwindcss.com/) |
| **Frontend Cliente** | [Next.js](https://nextjs.org/) · TypeScript · [Shadcn](https://ui.shadcn.com/docs/installation) · [TailwindCSS](https://tailwindcss.com/) |
| **Infraestrutura** | VPS · [Docker](https://www.docker.com/) (Backend) · [Vercel](https://vercel.com/) (Frontends) |

---

## 📂 Estrutura dos Repositórios
- **[`SAE_back`](https://github.com/aps-2025-SAE/SAE_back)** → API REST em Laravel  
- **[`SAE_front`](https://github.com/aps-2025-SAE/SAE_front)** → Painel administrativo e secretariado (React)  
- **[`SAE_front_client`](https://github.com/aps-2025-SAE/SAE_front_client)** → Portal do cliente (Next.js)  

---

## 🔄 Fluxo Resumido
1. **Clientes** → Visualizam e agendam eventos pelo portal.  
2. **API Backend** → Processa requisições, autentica usuários e mantém os dados.  
3. **Admin/Secretário** → Gerenciam eventos e usuários pelo painel administrativo.  

---

## 🚀 Guia de Execução

### 🔹 Backend (Laravel)
```bash
git clone https://github.com/aps-2025-SAE/SAE_back
cd SAE_back
composer install
cp .env.example .env
php artisan migrate
php artisan serve
```

### 🔹 Frontends (React / Next.js)
```bash
git clone https://github.com/aps-2025-SAE/SAE_front
cd SAE_front # ou SAE_front_client
npm install
npm run dev
```

---

## 👨‍💻 Equipe de Desenvolvimento
| Nome | GitHub |
|------|--------|
| Ana Luiza | [@AnaLuizanc](https://github.com/AnaLuizanc) |
| Anne Karoline | [@annekarolinneds](https://github.com/annekarolinneds) |
| Ênio Filipe | [@eniofilipe22](https://github.com/eniofilipe22) |
| João Vitor Medina | [@MedinaJv](https://github.com/MedinaJv) |

---

## 📜 Licença
Este projeto está sob a licença [MIT](./LICENSE).
