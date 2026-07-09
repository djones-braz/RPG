# Publicação no GitHub Pages

Este projeto foi preparado para publicação estática no GitHub Pages usando a pasta `docs/`.

## Configuração recomendada

1. Crie um repositório no GitHub.
2. Envie todos os arquivos deste pacote para a branch `main`.
3. Abra o repositório no GitHub.
4. Acesse **Settings**.
5. Clique em **Pages** no menu lateral.
6. Em **Build and deployment**, selecione:
   - **Source:** Deploy from a branch;
   - **Branch:** main;
   - **Folder:** /docs.
7. Clique em **Save**.
8. Aguarde a publicação.

## URL esperada

A URL normalmente seguirá o padrão:

```text
https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/
```

## Estrutura publicada

A página pública será:

```text
docs/index.html
```

O MVP funcional ficará em:

```text
docs/app/index.html
```

## Atenção às chaves de API

Nunca publique chaves privadas no GitHub.

O MVP foi organizado para que cada usuário insira sua própria chave no navegador. A chave é armazenada localmente no dispositivo do usuário.
