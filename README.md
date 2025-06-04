# 🌐 Plataforma de Comunicação e Capacitação Docente

Este projeto é um ambiente digital moderno desenvolvido para **fortalecer a comunicação interna** e **promover a capacitação de professores** em todo o Brasil. O sistema foi desenhado para escalar, atender diferentes tipos de usuários (aluno, professor, admin, visitante) e manter uma base sólida e segura, do backend ao frontend.

---

## 🛠️ Tecnologias Utilizadas

### Backend
- **[NestJS](https://nestjs.com/)** — Estrutura modular, robusta e escalável para Node.js
- **[TypeORM](https://typeorm.io/)** — ORM para manipulação de dados com suporte a queries customizadas
- **[PostgreSQL](https://www.postgresql.org/)** — Banco de dados relacional confiável e poderoso
- **Autenticação com Sessions e Cookies** — Protegido por AuthGuards e gerenciamento de `roles`
- **Swagger** — Documentação automática das rotas
- **Jest** — Testes automatizados de serviços e controladores
- **Docker** — Conteinerização do backend para facilitar o deploy e padronizar ambientes
- **Deploy:**  
  - Inicialmente no **Render**  
  - Migração para VPS com **EasyPanel** para gerenciamento e deploy manual

### Frontend
- **[React.js](https://react.dev/)** + **[Vite](https://vitejs.dev/)** — Para construção rápida e responsiva da interface
- **[Tailwind CSS](https://tailwindcss.com/)** + **[Radix UI](https://www.radix-ui.com/)** — Design moderno e acessível
- **[React Query](https://tanstack.com/query/latest)** — Otimização de cache e gerenciamento de requisições
- **Context API** — Para controle de autenticação e estado global
- Estrutura componetizada e legível — facilitando manutenção, reuso e testes

---

## 📊 Funcionalidades Principais

- Cadastro e login com múltiplos níveis de acesso (admin, professor, aluno, visitante)
- Área exclusiva para professores, com acesso a conteúdos e ferramentas internas
- Sistema de dashboard com métricas e filtros avançados (queries otimizadas com SQL puro via TypeORM)
- Gerenciamento de usuários e permissões
- Sistema responsivo, funcional em desktop e dispositivos móveis
- Painel de administração completo
- Documentação automatizada via Swagger

---

## 🧠 Aprendizados e Desafios

> Este foi um projeto que tive o prazer de construir de ponta a ponta — do backend ao frontend e até o deploy.  
Passei por diversos desafios técnicos, como:
- Otimização de performance com uso de **queries personalizadas SQL** no TypeORM
- Autenticação segura com cookies/sessions sem expor tokens
- Configuração de ambientes Docker e migração para VPS
- Implementação de sistema de **roles** e proteção de rotas via **AuthGuard**
- Criação de interfaces modernas e acessíveis com componentes reutilizáveis

Cada erro foi uma oportunidade de aprendizado, e hoje me sinto muito mais preparado para lidar com aplicações reais e escaláveis.

---

## 📷 Galeria de Imagens e Diagramas

> ⚠️ Imagens do sistema, fluxogramas de arquitetura e exemplos de queries utilizadas serão adicionados abaixo (adicione seus prints aqui):

- ✅ Interfaces principais do sistema (login, dashboard, painel do professor)
- ✅ Diagrama ER do banco (gerado a partir das entidades TypeORM)
- ✅ Diagrama de arquitetura (API, banco, frontend, cloud)
- ✅ Exemplos de queries SQL otimizadas utilizadas em relatórios

---

## 🤝 Contato
📧 gabriel23teotonio@gmail.com
🔗 [linkedin.com/in/gabriel-teotonio](https://linkedin.com/in/gabriel-teotonio)  
