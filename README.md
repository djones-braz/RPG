# AI Lore & Character Sheet Studio

> Documentação técnica ilustrada e MVP funcional para geração de fichas de RPG e arte conceitual via Inteligência Artificial.

![Status](https://img.shields.io/badge/status-MVP%20Funcional-7c3aed)
![Curso](https://img.shields.io/badge/curso-IA%20Aplicada-0f172a)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-pronto-22c55e)

## Visão geral

O **AI Lore & Character Sheet Studio** é um projeto acadêmico desenvolvido no curso de **Inteligência Artificial Aplicada**, lecionado e orientado pelo **Professor Djones Braz de Araujo Costa**, na **Unidade da FAETEC-RJ de Cachoeiras de Macacu**.

A proposta do sistema é reduzir o atrito mecânico na criação de personagens de RPG, combinando geração de narrativa, ficha técnica estruturada, atributos balanceados, avatar conceitual e ferramentas de apoio para mesa de jogo.

## Equipe

**Desenvolvedores:**

- Ronald Salvaya
- Matheus Makoto
- Kauã Lau

**Orientação:** Professor Djones Braz de Araujo Costa  
**Natureza:** Documentação Técnica Ilustrada e MVP Funcional  
**Sistema-alvo:** Geração de Fichas de RPG & Arte Conceitual via IA  
**Data de emissão:** Junho de 2026

## Funcionalidades do MVP

- Geração de ficha de personagem com IA generativa.
- Criação de lore em Português do Brasil.
- Geração de avatar em estilos como Concept Art, Anime/Manga, Pixel Art e Realista.
- Controle reativo de HP, MP e XP.
- Modificação de atributos e cálculo de modificadores.
- Abas de Lore, Habilidades, Equipamentos e JSON bruto.
- Calculadora de dados compatível com fórmulas como `2d20 + 1d6 + FOR`.
- Exportação de ficha em PDF A4 via impressão do navegador.
- Armazenamento local de fichas e histórico.
- Opção para o usuário inserir sua própria chave da API Gemini.

## Estrutura do repositório

```text
ai-lore-character-sheet-studio/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── CHANGELOG.md
├── index.html
├── app/
│   └── index.html
├── data/
│   └── personagem-exemplo.json
├── prompts/
│   ├── prompt-sistema.md
│   └── schema-personagem.json
├── docs/
│   ├── index.html
│   ├── ARQUITETURA.md
│   ├── DOCUMENTACAO_TECNICA.md
│   ├── GITHUB_PAGES.md
│   ├── GUIA_USUARIO.md
│   ├── METODOLOGIA.md
│   ├── ROADMAP.md
│   ├── REFERENCIAS.md
│   ├── app/
│   │   └── index.html
│   └── assets/
│       ├── css/style.css
│       ├── js/site.js
│       ├── docs/AI_Lore_Character_Sheet_Documentacao_Tecnica.pdf
│       └── img/pdf-page-01.png ... pdf-page-07.png
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── bug_report.md
    │   └── feature_request.md
    └── pull_request_template.md
```

## Como executar localmente

Por ser uma aplicação estática, basta abrir o arquivo abaixo no navegador:

```text
app/index.html
```

Para testar como servidor local:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000/docs/
```

## Publicação no GitHub Pages

A forma recomendada para este repositório é publicar a pasta `docs/`.

1. Envie todos os arquivos para um repositório público no GitHub.
2. Acesse **Settings > Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch `main` e a pasta `/docs`.
5. Salve e aguarde a URL pública ser gerada.

Consulte o guia completo em [`docs/GITHUB_PAGES.md`](docs/GITHUB_PAGES.md).

## Como usar a aplicação

1. Acesse a página do projeto em GitHub Pages.
2. Clique em **Abrir MVP Funcional**.
3. Abra **Configurações**.
4. Insira sua chave gratuita do Google AI Studio.
5. Escreva uma descrição breve do personagem.
6. Escolha o estilo visual do avatar.
7. Clique em **Gerar Ficha & Avatar**.

## Licença

Este projeto está disponibilizado com licença MIT para fins educacionais, estudo, adaptação e colaboração comunitária. Ver [`LICENSE`](LICENSE).

## Créditos

Projeto desenvolvido por Ronald Salvaya, Matheus Makoto e Kauã Lau, sob orientação do Professor Djones Braz de Araujo Costa, no curso de Inteligência Artificial Aplicada da FAETEC-RJ - Unidade Cachoeiras de Macacu.
