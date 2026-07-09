# Documentação Técnica - AI Lore & Character Sheet Studio

## Identificação do projeto

**Nome:** AI Lore & Character Sheet Studio  
**Desenvolvedores:** Ronald Salvaya, Matheus Makoto e Kauã Lau  
**Orientador:** Professor Djones Braz de Araujo Costa  
**Curso:** Inteligência Artificial Aplicada  
**Instituição:** FAETEC-RJ - Unidade Cachoeiras de Macacu  
**Natureza:** Documentação Técnica Ilustrada e MVP Funcional  
**Sistema-alvo:** Geração de Fichas de RPG & Arte Conceitual via IA  
**Data de emissão:** Junho de 2026

## 1. Resumo executivo

O **AI Lore & Character Sheet Studio** é um sistema web voltado à criação de fichas de personagens de RPG com apoio de Inteligência Artificial Generativa. O projeto busca reduzir a complexidade inicial enfrentada por jogadores e mestres ao criar personagens, automatizando partes mecânicas da ficha e ampliando a experiência criativa por meio de narrativas e avatares personalizados.

O sistema une três frentes principais:

1. geração textual de lore e dados técnicos;
2. cálculo e organização de atributos mecânicos;
3. geração de avatar conceitual alinhado ao personagem.

## 2. Problema identificado

A criação tradicional de fichas de RPG pode exigir leitura de manuais extensos, conhecimento prévio de regras e tempo de preparação. Além disso, a obtenção de ilustrações personalizadas costuma depender de comissões artísticas pagas ou imagens genéricas que nem sempre representam o conceito imaginado pelo jogador.

## 3. Proposta de valor

A proposta de valor do MVP é oferecer uma ferramenta acessível, visual e interativa para criar personagens de RPG com rapidez, mantendo a criatividade humana como elemento central. O usuário descreve o personagem em linguagem natural e recebe uma ficha estruturada, com atributos, lore, habilidades, equipamentos, status e imagem conceitual.

## 4. Módulos do sistema

### 4.1 Painel de entrada e parametrização

O painel de entrada permite inserir palavras-chave ou uma descrição curta do personagem. A interface também disponibiliza estilos visuais para geração do avatar, como:

- Concept Art;
- Anime/Manga;
- Pixel Art;
- Realista;
- Cyberpunk Neon;
- Pintura a Óleo.

O sistema também possui inspirações rápidas para reduzir bloqueio criativo e facilitar o teste do MVP.

### 4.2 Painel de ficha inteligente

Após a geração, a ficha apresenta:

- nome do personagem;
- título honorífico;
- classe;
- nível;
- atributos;
- modificadores;
- HP, MP e XP;
- lore;
- habilidades;
- equipamentos;
- JSON bruto.

A ficha também permite editar dados, alterar atributos, modificar status e exportar a folha em PDF A4.

### 4.3 Abas de conteúdo

A interface organiza o conteúdo em abas para reduzir a sobrecarga visual:

- **Lore:** história e origem do personagem.
- **Habilidades:** poderes, custos e efeitos.
- **Equipamentos:** armas, poções, utilidades e fórmulas.
- **JSON Bruto:** representação estruturada da ficha.

### 4.4 Calculadora de dados

A calculadora aceita expressões com dados e modificadores, como:

```text
2d20 + 1d6 + FOR
```

Ela interpreta dados clássicos de RPG, como `d4`, `d6`, `d8`, `d10`, `d12`, `d20` e `d100`, além de modificadores vinculados aos atributos da ficha.

## 5. Arquitetura técnica

O MVP foi implementado como aplicação estática em:

- HTML5;
- CSS com Tailwind via CDN;
- JavaScript Vanilla;
- Google Gemini API para geração textual estruturada;
- Pollinations AI para geração de imagem;
- Firebase opcional para sincronização futura;
- localStorage para persistência local.

## 6. Inteligência Artificial no projeto

Foram utilizadas ferramentas de IA para pesquisa, prototipação, apoio à documentação, geração e refinamento de código, validação conceitual e produção de materiais de divulgação.

Ferramentas citadas na documentação original:

- Gemini;
- ChatGPT;
- Google Flow;
- NotebookLM.

## 7. Resultados do MVP

O projeto entrega um protótipo funcional capaz de demonstrar o uso prático da IA Generativa no contexto de jogos de interpretação, com foco em criatividade, automação de tarefas repetitivas e experiência visual.

## 8. Potencial de evolução

Possíveis evoluções:

- integração com sistemas de RPG específicos;
- exportação para formatos compatíveis com VTTs;
- autenticação e salvamento em nuvem;
- biblioteca pública de personagens;
- suporte a múltiplos idiomas;
- modo mestre de campanha;
- sistema de templates para aventuras.
