# Paulo Henrique — Portfolio HUB v3

Portfólio pessoal de **Paulo Henrique de Melo Bezerra**, estudante de Ciência da Computação no CEUB e desenvolvedor de software em formação.

A versão 3 reorganiza o site em torno de **projetos selecionados e evidências técnicas**, reduzindo repetições e dando mais espaço aos trabalhos que melhor representam o nível atual de desenvolvimento.

## Projetos em destaque

### 1. EchoCraft + EchoPanel
Ecossistema de memória temporal para servidores Minecraft, integrando um plugin Paper em Java a um painel Laravel/Livewire por REST API autenticada.

- EchoCraft: https://github.com/phmbezerra/EchoCraft
- EchoPanel: https://github.com/phmbezerra/EchoPanel

### 2. AccessVault
Sistema full stack de gestão de usuários, sistemas e acessos.

**Stack:** React, Vite, FastAPI, SQLAlchemy e SQLite.

- Repositório: https://github.com/phmbezerra/AccessVault

### 3. ECHO//SYSTEM
Jogo narrativo em React apresentado como um sistema operacional corrompido, com múltiplas rotas/finais, persistência local e áudio procedural via Web Audio API.

- Repositório: https://github.com/phmbezerra/echo-system

### 4. LMWI-Scheduler
Case de pesquisa computacional sobre **Locational Marginal Water Impact (LMWI)** aplicado a decisões de scheduling.

O código permanece privado. O portfólio apresenta somente uma visão de alto nível do problema e da metodologia experimental.

## Laboratório

### ECHOBRIDGE
Protótipo em desenvolvimento para ampliar a compatibilidade visual de itens Java modded em clientes Bedrock usando Fabric, Geyser e resource packs.

## Estrutura

```text
portfolioHUB/
├── index.html
├── README.md
├── .gitignore
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── main.js
    ├── docs/
    │   └── Paulo_Henrique_Curriculo_Profissional.pdf
    └── img/
        ├── foto-perfil.jpg
        └── certificado-python.jpg
```

## Decisões da v3

- projetos principais reduzidos a uma curadoria de quatro cases;
- EchoCraft + EchoPanel tratados como um único ecossistema;
- AccessVault descrito apenas com funcionalidades comprovadas no repositório atual;
- LMWI-Scheduler apresentado como case privado, sem link para código;
- ECHOBRIDGE identificado explicitamente como projeto em desenvolvimento;
- projetos introdutórios movidos para uma área de evolução;
- CSS e JavaScript extraídos do `index.html` para melhorar manutenção;
- remoção da seção pública de recomendações da página principal;
- link do currículo corrigido para o arquivo existente no repositório;
- layout responsivo, navegação acessível e suporte a `prefers-reduced-motion`.

## Executar localmente

```bash
python -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Publicação

O site é compatível com GitHub Pages e pode ser publicado diretamente a partir da raiz do repositório.
