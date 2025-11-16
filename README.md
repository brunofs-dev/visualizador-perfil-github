# Visualizador de Perfil do GitHub

Um simples visualizador de perfil do GitHub construído com HTML, CSS e JavaScript.

## Funcionalidades

- Pesquisar por um usuário do GitHub
- Exibir informações do perfil do usuário, como nome, avatar, biografia, seguidores e contagem de seguidores
- Listar os 10 repositórios mais recentes do usuário
- Exibir estatísticas do repositório, como estrelas, forks e watchers
- Links diretos para os repositórios no GitHub

## Tecnologias Utilizadas

- HTML
- CSS
- JavaScript
- [GitHub API](https://docs.github.com/en/rest)

## Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/visualizador-perfil-github.git
   ```
2. Abra o arquivo `index.html` em seu navegador.
3. Digite um nome de usuário do GitHub na caixa de pesquisa e clique em "Buscar".

## Endpoints da API

Este projeto utiliza os seguintes endpoints da API do GitHub:

- **Perfil do Usuário:** `GET /users/:username`
- **Repositórios do Usuário:** `GET /users/:username/repos`
  - Parâmetros de consulta utilizados: `per_page=10` e `sort=created`

---

_Este README foi gerado com o auxílio do Gemini._
