# Portfolio Website — Caroline Vitória Paneco

<div align="center">

![Badge Status](https://img.shields.io/badge/Status-Ativo-success?style=for-the-badge)
![Badge Role](https://img.shields.io/badge/Role-Multiplatform_.NET_Developer-blue?style=for-the-badge)
![Badge Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Badge i18n](https://img.shields.io/badge/i18n-PT--BR_%7C_EN-ff3b7a?style=for-the-badge)
![Badge Theme](https://img.shields.io/badge/Theme-Dark_%26_Light-00d4ec?style=for-the-badge)

**Plataforma de portfólio profissional de engenharia de software com design de alta fidelidade, suporte bilíngue nativo (PT/EN), alternador de tema Claro/Escuro e vitrine técnica completa.**

[Sobre](#-sobre-o-projeto) • [Projetos](#-projetos-em-destaque) • [Stack Tecnológica](#-arsenal-tecnológico) • [Experiência](#-experiência-profissional) • [Como Executar](#-como-executar-localmente) • [Contato](#-contato)

</div>

---

## 🚀 Sobre o Projeto

Este repositório contém o código-fonte do portfólio de engenharia de **Caroline Vitória Paneco**, Desenvolvedora de Software Multiplataforma com foco em arquitetura .NET e soluções de engenharia corporativas. 

O site foi completamente reprojetado para transmitir uma estética moderna, técnica e de alto padrão (inspirada em empresas como Linear, Vercel e Apple Developer), incluindo:
- **Suporte Bilíngue Nativo (PT/EN):** Tradução instantânea de toda a interface sem recarregar a página, com persistência no `localStorage`.
- **Alternador de Tema (Dark / Light):** Paleta adaptativa com modo escuro em alta saturação neon e modo claro limpo e contrastante.
- **Estrutura Unificada:** Navegação fluida com âncoras diretas para Projetos, Habilidades, Experiência e Contato.
- **Espaço para Mídia em Todos os Projetos:** Slots configurados para vídeos demonstrativos, galerias de capturas de tela e links diretos para repositórios e sites de clientes.

---

## 📂 Estrutura de Arquivos

```bash
portfolio-site/
├── index.html              # Aplicação principal (Hero, Vitrine de Projetos, Skills, Experiência, Contato)
├── .gitignore              # Regras de exclusão do Git
├── README.md               # Documentação técnica completa
├── pages/                  # Rotas de redirecionamento legado para compatibilidade de URLs
│   ├── projects.html
│   ├── skills.html
│   ├── contact.html
│   └── assets/
│       ├── img/
│       │   └── eu.jpeg     # Foto de perfil profissional
│       └── pdf/
│           └── resume.pdf  # Currículo para download
├── img/                    # Imagens e capturas de tela dos projetos
│   ├── inicial.png         # Screenshot: Paula Presentes - Home
│   ├── detalhe.png         # Screenshot: Paula Presentes - Detalhe do Produto
│   └── image.png           # Screenshot: Paula Presentes - Painel Administrativo
├── docs/
│   └── documentacao_tecnica_paulapresentes.pdf  # Documentação técnica completa
└── videos/
    └── video.mp4           # Demonstração em vídeo do e-commerce Paula Presentes
```

---

## 💻 Projetos em Destaque

### 1. Paula Presentes — E-commerce & Painel Administrativo
- **Stack:** ASP.NET Core MVC, PostgreSQL, Tailwind CSS.
- **Recursos:** Catálogo dinâmico, fluxo de carrinho, autenticação de usuários, galeria de imagens e painel administrativo completo de controle de produtos, estoque, vendas e fluxo de caixa.
- **Mídia:** Vídeo integrado na aplicação, documentação técnica em PDF e galeria de screenshots.

### 2. Débora Doces — E-commerce & Gestão Administrativa
- **Stack:** Web, JavaScript, Painel Administrativo.
- **Recursos:** E-commerce para confeitaria artesanal com cardápio dinâmico, tela interativa para personalização de encomendas (escolha de massas, recheios, coberturas e agendamento de data de entrega) e painel administrativo com controle em tempo real de pedidos, status de produção, ficha de clientes e gestão de estoque.

### 3. ALEVS — Streetwear Autoral E-commerce
- **Stack:** TanStack Start, React 19, Tailwind CSS v4, Supabase, Drizzle ORM, Radix UI, Vite 8, Vitest.
- **Recursos:** Storefront contínua, busca e filtros instantâneos, modal de visualização rápida com seletor de medidas, carrinho persistente com `localStorage`, cupons de desconto dinâmicos e fluxo de checkout simulado em 3 etapas (Pix, Cartão, Boleto).
- **Repositório:** [CarolPaneco/alevs](https://github.com/CarolPaneco/alevs)

### 4. Portal de IA (IA Nossa) — API Corporativa Gemini & OpenAI
- **Stack:** Node.js, Express, Google Gemini API oficial (`generateContent`), OpenAI API spec, SSE Streaming.
- **Recursos:** Portal corporativo seguro para chat com múltiplos modelos de IA com chave restrita ao backend (zero vazamento de chaves no cliente), streaming de respostas em tempo real e deploy estruturado no Render.
- **Repositório:** [CarolPaneco/ia_nossa](https://github.com/CarolPaneco/ia_nossa)

### 5. IdeaFlow (Spark Mindful Flow) — Gestão de Ideias com IA & Recharts
- **Stack:** TanStack Start, React 19, Recharts, Radix UI, Vaul drawers, Vite 8.
- **Recursos:** Captura inteligente de ideias com decomposição assistida por IA, geração de planos de ação imediata em 15 minutos, histórico de motivos de mudança de rota (pivôs), dashboards visuais com Recharts e exportação direta para Google Calendar e arquivo `.ics`.
- **Repositório:** [CarolPaneco/spark-mindful-flow](https://github.com/CarolPaneco/spark-mindful-flow)

### 6. Telemetria Agrícola — Arquitetura Modular & IndexedDB
- **Stack:** JavaScript Moderno, IndexedDB, CSS3.
- **Recursos:** Sistema de controle e análise de telemetria de frotas agrícolas (Colhedora, Tratos Culturais e Plantadora). Armazenamento incremental offline no IndexedDB do navegador sem sobrescrever histórico e cruzamento com produtividade de cana e registros de chuva.
- **Repositório:** [CarolPaneco/projeto-telemetria](https://github.com/CarolPaneco/projeto-telemetria)

### 7. Robô Leitor — OCR & Processamento de Documentos em Python
- **Stack:** Python, Flask, Tesseract OCR.
- **Recursos:** Ingestão e extração automatizada de texto em PDFs e formatos de imagem (PNG, JPG, TIFF) com suporte ao português, preparação de dados em lote para planilhas CSV/Excel e suporte a pipelines de LLM.
- **Repositório:** [CarolPaneco/leitor-documentos](https://github.com/CarolPaneco/leitor-documentos)

### 8. CRUD API (SistemaWeb)
- **Stack:** ASP.NET Core, React, SQL Server.
- **Recursos:** API RESTful com arquitetura em camadas, autenticação e sincronização de dados em tempo real com frontend React.
- **Repositório:** [CarolPaneco/SistemaWeb](https://github.com/CarolPaneco/SistemaWeb)

### 9. Kanban App
- **Stack:** Flutter, Dart.
- **Recursos:** Aplicativo de gestão ágil com movimentação de cards Drag & Drop fluida, arquitetura adaptativa para Web e Mobile.
- **Repositório:** [CarolPaneco/KANBAN](https://github.com/CarolPaneco/KANBAN)

---

## 🛠️ Arsenal Tecnológico

- **Desenvolvimento .NET & Backend:** C#, ASP.NET Core MVC, Entity Framework Core, Arquitetura .NET, Python, C++, REST APIs, POO.
- **Web & Multiplataforma:** React 19, Flutter, Tailwind CSS v4, TanStack Start/Router, HTML5/CSS3, JavaScript (ES6+), Android Studio.
- **Dados, IA & Telemetria:** Power BI, Redes Neurais, Soluções assistidas por IA, Telemetria Agrícola, Tesseract OCR, Análise de Dados.
- **Bancos de Dados:** PostgreSQL, SQLite, SQL Server, IndexedDB.
- **DevOps, Ferramentas & Práticas:** Docker, Azure DevOps, Git & GitHub, Power Automate, Arduino, Testes Unitários & de Carga, Scrum.

---

## 💼 Experiência Profissional

- **Tereos:** Estagiária de Controle Agrícola — Análise de Dados & Melhoria Contínua *(Ago 2026 – Presente)*
- **AGTech:** Desenvolvedora Júnior *(Fev 2025 – Mar 2026)*

---

## 🎓 Formação Acadêmica

- **FATEC de Olímpia:** Tecnólogo em Desenvolvimento de Software Multiplataforma *(2026 – Previsão 2028)*
- **Universidade Paulista (UNIP):** Tecnólogo em Análise e Desenvolvimento de Sistemas *(2023 – 2024 | Concluído)*

---

## 🖥️ Como Executar Localmente

Como o projeto é construído em HTML semântico com Tailwind CSS e JavaScript moderno, você pode executá-lo diretamente:

1. Clone o repositório:
   ```bash
   git clone https://github.com/CarolPaneco/portfolio-site.git
   cd portfolio-site
   ```

2. Inicie o servidor local:
   ```bash
   npx serve
   ```
   Acesse no navegador: `http://localhost:3000`

---

## 🌐 Publicação no GitHub Pages

O site está configurado para publicação imediata no GitHub Pages:
1. No repositório, acesse **Settings > Pages**.
2. Selecione a branch `main` e a pasta `/ (root)`.
3. Salve as alterações.
4. O portfólio estará online em: **`https://carolpaneco.github.io/portfolio-site/`**

---

## 📬 Contato

- **LinkedIn:** [Caroline Paneco](https://www.linkedin.com/in/caroline-paneco-6942641b5/)
- **GitHub:** [@CarolPaneco](https://github.com/CarolPaneco)
- **E-mail:** [cpaneco@gmail.com](mailto:cpaneco@gmail.com)

---

<div align="center">
  <sub>Desenvolvido por Caroline Vitória Paneco • 2026</sub>
</div>
