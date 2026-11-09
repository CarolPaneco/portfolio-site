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

### 10. Ordem Certa — Gestão de Ordens de Serviço & Equipes
- **Stack:** React 19, TanStack Router, Supabase, Google Maps API, Recharts, Tailwind CSS v4, Zod, Radix UI.
- **Recursos:** Gestão completa de ordens de serviço (OS) com georreferenciamento de clientes no mapa, controle de insumos e estoque de materiais, relatórios analíticos de produtividade e formulários reativos tipados fim a fim.
- **Repositório:** [CarolPaneco/Ordem-Certa](https://github.com/CarolPaneco/Ordem-Certa)

### 11. ReMarTur Viagens — Portal de Resorts & Experiências
- **Stack:** React 19, TanStack Router, Framer Motion, Tailwind CSS v4, Vite.
- **Recursos:** Vitrine digital para grandes resorts termais (Olímpia, Barretos, Caldas Novas), filtros dinâmicos por capacidade (até 7 pessoas) e comodidades, animações fluidas de scroll com Framer Motion e cotador interativo que gera leads formatados no WhatsApp.
- **Repositório:** [CarolPaneco/remartur-v3](https://github.com/CarolPaneco/remartur-v3)

### 12. Studio Clara Romano — Nail Design & Agendamento Digital
- **Stack:** React 19, TanStack Start (SSR), Nitro, TanStack Query, Vitest, Motion, Sharp, Tailwind CSS v4.
- **Recursos:** Plataforma com Server-Side Rendering ultrarrápido, gaveta lateral interativa estilo sacola de procedimentos para escolha múltipla de serviços, cálculo em tempo real de valores/tempo e agendamento via WhatsApp.
- **Site:** [studioclararomano.com](https://studioclararomano.com/) • **Repositório:** [CarolPaneco/cr](https://github.com/CarolPaneco/cr)

### 13. Forneria Canto D' Itália — Tradição & Gastronomia Artesanal
- **Stack:** HTML5 Semântico, Tailwind CSS Customizado, Cormorant Garamond, Glassmorphism, CSS Animations.
- **Recursos:** Experiência imersiva para forneria artesanal em Olímpia/SP, exibição de pizzas de longa fermentação, carta de vinhos (adega), tour fotográfico pelo salão rústico e integração com delivery oficial e localização.
- **Repositório:** [CarolPaneco/cantoditalia](https://github.com/CarolPaneco/cantoditalia)

### 14. Hayané Beauty Studio — Estética Facial & Canvas 2D
- **Stack:** JavaScript ES6+, HTML5 Canvas 2D, Física de Partículas, 3D Parallax, Tailwind CSS, Lucide.
- **Recursos:** Web app com engine em Canvas 2D renderizando poeira dourada que reage ao mouse com física e gravidade, parallax 3D interativo por coordenadas do cursor, carrinho reativo de procedimentos com cálculo de orçamento e agendamento direto.
- **Repositório:** [CarolPaneco/lash](https://github.com/CarolPaneco/lash)

### 15. NFCeDesktop — Emissão Fiscal Desktop em .NET 8 WPF
- **Stack:** C# 12, .NET 8 Windows, WPF, XAML, QuestPDF, QRCoder, Padrão SEFAZ, MVVM.
- **Recursos:** Aplicação desktop corporativa para emissão, validação e impressão de Notas Fiscais de Consumidor Eletrônicas (NFC-e), geração vetorial de DANFE em PDF com QuestPDF e renderização de QR Code fiscal regulatório.
- **Repositório:** [CarolPaneco/NFCeDesktop](https://github.com/CarolPaneco/NFCeDesktop)

### 16. Automação SimpleFarm — RPA Agrícola em Nuvem
- **Stack:** Python 3, Playwright Headless, Multithreading (25 threads), Pool de Proxies, Single Sign-On Microsoft, GitHub Actions.
- **Recursos:** Robô de RPA em nuvem para extração diária do relatório agronômico R10 (Analítico do Talhão) no sistema SimpleFarm/GAtec da Tereos. Bypass de bloqueios geográficos via proxies rotativos, autenticação SSO e envio automatizado de planilhas por e-mail (SMTP).
- **Repositório:** [CarolPaneco/automacao-simplefarm](https://github.com/CarolPaneco/automacao-simplefarm)

---

## 💳 Cardápio de Serviços & Investimento

Soluções digitais completas com modelo transparente de implantação e manutenção contínua:

| Solução | Implantação (Taxa Única) | Manutenção Mensal | O Que Inclui |
| :--- | :--- | :--- | :--- |
| **Landing Page** | **R$ 200,00** | **R$ 50,00 / mês** | Design responsivo exclusivo, WhatsApp, formulário, SEO inicial, custos de nuvem e suporte 24h com pequenos ajustes. |
| **E-commerce + Gestão Total** | **R$ 1.000,00** | **R$ 500,00 / mês** | Loja virtual completa, carrinho, checkout, Painel Administrativo de Gestão (ERP), estoque, fluxo de caixa e suporte 24h. |
| **CRM Multi-Módulos** | **R$ 600,00** | **R$ 300,00 / mês** | Gestão de clientes, funil/pipeline (Kanban), ordens de serviço, relatórios analíticos de produtividade e suporte 24h. |

> **Diferenciais Inclusos:**
> - 🎁 **Protótipo Inicial 100% Gratuito:** O cliente aprova a interface e o fluxo antes de pagar o valor de implantação.
> - ☁️ **Custos de Servidor Cobertos:** A mensalidade cobre hospedagem, banco de dados e estabilidade contínua.
> - 🕒 **Atendimento & Suporte 24h:** Canal direto para dúvidas, assistência e orientações técnicas.
> - 🛠️ **Pequenas Alterações Sem Custo Extra:** Ajustes de dados, fotos, banners, produtos e textos inclusos na mensalidade.

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
