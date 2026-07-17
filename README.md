<div align="center">

# Paulo Henrique — Portfólio de Desenvolvimento de Software

Portfólio pessoal e profissional com projetos de desenvolvimento full stack, integração entre sistemas, automação, banco de dados e interfaces responsivas.

[![Portfólio](https://img.shields.io/badge/Portfólio-Acessar-59a8ff?style=for-the-badge&logo=google-chrome&logoColor=white)](https://phmbezerra.github.io/portfolioHUB/)
[![GitHub](https://img.shields.io/badge/GitHub-phmbezerra-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/phmbezerra)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Paulo%20Henrique-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paulo-henrique-melo-bezerra-8b1b28372/)

</div>

---

## Sobre o projeto

Este repositório apresenta minha trajetória em desenvolvimento de software e reúne os trabalhos que melhor representam minha evolução técnica.

O portfólio destaca projetos que conectam interface, back-end, APIs, persistência, automação e documentação. O principal caso apresentado atualmente é o ecossistema **EchoCraft + EchoPanel**, formado por duas aplicações independentes que se comunicam por uma API autenticada.

## Sobre mim

Sou estudante de **Ciência da Computação no CEUB**, em Brasília/DF, e desenvolvedor de software em formação.

Tenho interesse em desenvolvimento full stack, integrações entre sistemas, automação, APIs e banco de dados. Aprendo principalmente por meio da prática: construo protótipos, testo soluções, investigo falhas, registro decisões e aprimoro os projetos conforme encontro novos desafios.

## Projetos em destaque

### EchoCraft + EchoPanel

Ecossistema de memória temporal para servidores Minecraft.

O **EchoCraft** é um plugin Paper em Java que registra versões de estruturas, rastros e ações de jogadores, persiste os dados em SQLite e restaura memórias temporais.

O **EchoPanel** é um painel Laravel com Livewire que monitora servidores, exibe atividades e linhas do tempo visuais e envia comandos remotos de restauração ao plugin.

**Tecnologias e conceitos:** Java, Paper API, Laravel, Livewire, PHP, REST API, SQLite, Gradle, autenticação por token, heartbeat e fila de comandos.

- [Repositório do EchoCraft](https://github.com/phmbezerra/EchoCraft)
- [Repositório do EchoPanel](https://github.com/phmbezerra/EchoPanel)

### AccessVault

Plataforma de gestão de acessos com autenticação, níveis de permissão, solicitações, aprovação, geração de acessos e trilha de auditoria.

**Tecnologias e conceitos:** React, FastAPI, JWT, SQLite, controle de acesso, auditoria e dashboard administrativo.

### Organizador de Arquivos

Automação em Python para classificar arquivos por extensão, criar diretórios e gerar um resumo da execução.

**Tecnologias e conceitos:** Python, manipulação de arquivos e automação de tarefas repetitivas.

### Sistema de Estoque

Aplicação em Python com operações de cadastro, consulta, atualização e remoção de produtos.

**Tecnologias e conceitos:** Python, SQLite, CRUD e persistência de dados.

## Tecnologias do portfólio

<div align="left">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-121013?style=flat-square&logo=github&logoColor=white)

</div>

## Principais recursos

- layout responsivo para computador, tablet e celular;
- navegação móvel acessível;
- SEO básico, Open Graph e dados estruturados;
- apresentação organizada de projetos e competências;
- destaque para integração entre Java e Laravel;
- currículo atualizado para download;
- recomendações públicas integradas ao Supabase;
- fallback para falhas de imagens e serviços externos;
- suporte à preferência de movimento reduzido;
- links diretos para projetos, GitHub, LinkedIn e email.

## Estrutura esperada

```text
portfolioHUB/
├── index.html
├── README.md
├── .gitignore
└── assets/
    ├── docs/
    │   └── curriculo-paulo-henrique.pdf
    └── img/
        ├── foto-perfil.jpg
        └── certificado-python.jpg
```

## Executando localmente

```bash
git clone https://github.com/phmbezerra/portfolioHUB.git
cd portfolioHUB
python -m http.server 8000
```

Depois, acesse `http://localhost:8000`.

## Recomendações com Supabase

A seção de recomendações utiliza a tabela `recommendations` com os campos:

```text
id
name
avatar_url
message
approved
created_at
```

Novas recomendações são registradas com `approved = false` e aparecem no site somente após aprovação.

> A chave pública do Supabase pode ser utilizada no front-end, mas a proteção dos dados depende de políticas de **Row Level Security (RLS)** configuradas corretamente.

## Publicação

O projeto está preparado para publicação pelo GitHub Pages a partir da branch principal e da pasta raiz do repositório.

## Contato

- **Email:** paulohenriquemelobezerra1@gmail.com
- **GitHub:** [github.com/phmbezerra](https://github.com/phmbezerra)
- **LinkedIn:** [Paulo Henrique de Melo Bezerra](https://www.linkedin.com/in/paulo-henrique-melo-bezerra-8b1b28372/)
- **Portfólio:** [phmbezerra.github.io/portfolioHUB](https://phmbezerra.github.io/portfolioHUB/)

---

<div align="center">

Desenvolvido e mantido por **Paulo Henrique de Melo Bezerra**.

</div>
