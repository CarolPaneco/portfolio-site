# Portfolio Website — Caroline Paneco

<div align="center">

![Badge Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-success?style=for-the-badge)
![Badge Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Badge HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Badge JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Website de portfólio pessoal e profissional com estética dark neon/cyberpunk, responsivo e moderno.**

[Sobre Mim](#-sobre-o-projeto) • [Estrutura](#-estrutura-de-arquivos) • [Projetos](#-projetos-em-destaque) • [Como Executar](#-como-executar-localmente) • [Contato](#-contato)

</div>

---

## 🚀 Sobre o Projeto

Este repositório contém o código-fonte do portfólio pessoal de **Caroline Paneco**, Desenvolvedora de Software brasileira com formação em Análise e Desenvolvimento de Sistemas (UNIP) e graduanda em Desenvolvimento de Software Multiplataforma (FATEC Olímpia).

O site foi concebido com uma arquitetura visual moderna inspirada em interfaces técnicas de alta performance, utilizando paleta dark, efeitos de *glassmorphism*, tipografia fluida (*Space Grotesk* e *Manrope*) e componentes em estilo Bento Grid.

---

## 📂 Estrutura de Arquivos

```bash
portfolio-site/
├── index.html              # Página principal (Sobre Mim, Tech Stack Bento Grid, Formação, Bio)
├── .gitignore              # Arquivos e pastas ignorados pelo Git
├── README.md               # Documentação completa do repositório
├── pages/
│   ├── projects.html       # Vitrine de projetos com mídias e links técnicos
│   ├── skills.html         # Detalhamento de habilidades e competências técnicas
│   ├── hobbies.html        # Interesses criativos e lado pessoal (Xadrez, Idiomas, etc.)
│   ├── contact.html        # Formulário de contato funcional (Formspree) e redes
│   └── assets/
│       ├── img/
│       │   └── eu.jpeg     # Foto de perfil profissional
│       └── pdf/
│           └── resume.pdf  # Currículo para download
├── img/                    # Screenshots e imagens dos projetos
│   ├── inicial.png         # Screenshot: Tela inicial (Paula Presentes)
│   ├── detalhe.png         # Screenshot: Detalhes do produto
│   └── image.png           # Screenshot: Painel administrativo
├── docs/
│   └── documentacao_tecnica_paulapresentes.pdf  # Documentação técnica completa
└── videos/
    └── video.mp4           # Demonstração em vídeo do e-commerce Paula Presentes
```

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico**: Estruturação acessível e otimizada para SEO.
- **Tailwind CSS (CDN)**: Estilização utilitária com sistema customizado de tokens e tema dark.
- **JavaScript (Vanilla)**: Interatividade para menu mobile responsivo e navegação fluida.
- **Google Fonts**: Famílias tipográficas *Space Grotesk* e *Manrope*.
- **Google Material Symbols**: Ícones modernos e estilizados.
- **Formspree**: Integração direta para envio e recebimento de mensagens do formulário de contato.

---

## 💻 Projetos em Destaque

1. **Paula Presentes (E-commerce)**
   - Plataforma completa de vendas online com catálogo dinâmico, carrinho funcional, painel administrativo e autenticação.
   - *Tech Stack:* ASP.NET Core MVC, PostgreSQL, Tailwind CSS.
   - Inclui vídeo demonstrativo e documentação técnica em PDF.

2. **CRUD API**
   - Sistema full-stack de gerenciamento de produtos com API RESTful e interface reativa.
   - *Tech Stack:* ASP.NET Core, React, SQL Server.
   - Repositório: [SistemaWeb](https://github.com/CarolPaneco/SistemaWeb)

3. **Kanban App**
   - Aplicativo de fluxo e gestão de tarefas com experiência Drag & Drop.
   - *Tech Stack:* Flutter, Dart.
   - Repositório: [KANBAN](https://github.com/CarolPaneco/KANBAN)

---

## 🖥️ Como Executar Localmente

Como o projeto é construído em HTML, CSS e JavaScript puros (sem necessidade de compilação ou bundler complexo), você pode executá-lo diretamente no seu navegador:

1. Clone o repositório:
   ```bash
   git clone https://github.com/CarolPaneco/portfolio-site.git
   cd portfolio-site
   ```

2. Abra o arquivo `index.html` em qualquer navegador:
   - No Windows (PowerShell):
     ```powershell
     Start-Process index.html
     ```
   - Ou utilizando a extensão **Live Server** do VS Code:
     Clique com o botão direito no `index.html` e selecione *Open with Live Server*.

---

## 🌐 Publicação (GitHub Pages)

Para publicar gratuitamente este portfólio no GitHub Pages:
1. Vá até as configurações do repositório no GitHub (**Settings** > **Pages**).
2. Na seção **Branch**, selecione `main` (ou `master`) e a pasta `/ (root)`.
3. Clique em **Save**.
4. O site estará disponível em `https://carolpaneco.github.io/portfolio-site/`.

---

## 📬 Contato

- **LinkedIn:** [Caroline Paneco](https://www.linkedin.com/in/caroline-paneco-6942641b5/)
- **GitHub:** [@CarolPaneco](https://github.com/CarolPaneco)
- **E-mail:** [cpaneco@gmail.com](mailto:cpaneco@gmail.com)

---

<div align="center">
  <sub>Desenvolvido por Caroline Paneco • 2026</sub>
</div>
