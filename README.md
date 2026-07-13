<div align="center">

# Paulo Henrique — Portfólio de Desenvolvimento

Portfólio profissional de um estudante de Ciência da Computação e desenvolvedor full stack em formação, com projetos em desenvolvimento web, automação, APIs, Java e persistência de dados.

[![Portfólio](https://img.shields.io/badge/Portfólio-Acessar-59a8ff?style=for-the-badge&logo=google-chrome&logoColor=white)](https://phmbezerra.github.io/portfolioHUB/)
[![GitHub](https://img.shields.io/badge/GitHub-phmbezerra-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/phmbezerra)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Paulo%20Henrique-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paulo-henrique-melo-bezerra-8b1b28372/)

</div>

---

## Sobre o projeto

Este repositório reúne minha apresentação profissional, projetos, competências, certificado, currículo e formas de contato em uma única página responsiva.

O portfólio foi construído para demonstrar não apenas conhecimento técnico, mas também organização, documentação, preocupação com experiência do usuário e capacidade de transformar requisitos em entregas funcionais.

## Perfil profissional

Sou estudante do **2º semestre de Ciência da Computação no CEUB**, em Brasília/DF, com foco em:

- desenvolvimento full stack;
- automação de rotinas com Python;
- interfaces responsivas com HTML, CSS, JavaScript e React;
- APIs, autenticação e ferramentas internas;
- Java, SQLite e sistemas orientados a eventos;
- PHP e PostgreSQL em aprendizado contínuo.

Busco minha primeira oportunidade de estágio em desenvolvimento, preferencialmente no período da manhã e em modelo híbrido em Brasília/DF.

## Projetos em destaque

### AccessVault

Plataforma de gestão de acessos com autenticação, níveis de permissão, solicitações, aprovação, geração de acessos e trilha de auditoria.

**Tecnologias e conceitos:** React, FastAPI, JWT, SQLite, controle de acesso, auditoria e dashboard administrativo.

### EchoCraft

Plugin em Java para Minecraft que registra blocos destruídos, persiste o estado em SQLite e reconstrói estruturas com efeitos visuais.

**Tecnologias e conceitos:** Java, SQLite, eventos, persistência, depuração e tratamento de blocos especiais.

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
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-121013?style=flat-square&logo=github&logoColor=white)

</div>

## Principais recursos

- layout responsivo para computador, tablet e celular;
- menu móvel acessível;
- SEO básico, Open Graph e dados estruturados;
- apresentação objetiva de projetos e competências;
- currículo para download;
- recomendações públicas integradas ao Supabase;
- tratamento de falha no carregamento das imagens;
- suporte a preferência de movimento reduzido;
- links diretos para GitHub, LinkedIn e email.

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

Clone o repositório:

```bash
git clone https://github.com/phmbezerra/portfolioHUB.git
cd portfolioHUB
```

Abra o arquivo `index.html` no navegador ou execute um servidor local:

```bash
python -m http.server 8000
```

Depois, acesse `http://localhost:8000`.

## Recomendações com Supabase

A seção de recomendações utiliza a tabela `recommendations` e espera os seguintes campos:

```text
id
name
avatar_url
message
approved
created_at
```

Novas recomendações são cadastradas com `approved = false` e só aparecem no portfólio após aprovação.

> A chave pública do Supabase pode existir no front-end, mas a segurança depende de políticas de **Row Level Security (RLS)** configuradas corretamente. O navegador deve conseguir inserir recomendações pendentes e consultar somente registros aprovados.

## Publicação

O projeto pode ser publicado gratuitamente com GitHub Pages:

1. abra **Settings** no repositório;
2. acesse **Pages**;
3. selecione a branch principal e a pasta raiz;
4. salve e aguarde a publicação.

## Contato

- **Email:** paulohenriquemelobezerra1@gmail.com
- **GitHub:** [github.com/phmbezerra](https://github.com/phmbezerra)
- **LinkedIn:** [Paulo Henrique de Melo Bezerra](https://www.linkedin.com/in/paulo-henrique-melo-bezerra-8b1b28372/)
- **Portfólio:** [phmbezerra.github.io/portfolioHUB](https://phmbezerra.github.io/portfolioHUB/)

---

<div align="center">

Desenvolvido e mantido por **Paulo Henrique de Melo Bezerra**.

</div>
