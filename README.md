# Lista de Usuários

Aplicação em HTML, CSS e JavaScript puro que consome APIs públicas para listar usuários, exibir detalhes individuais e mostrar dicas aleatórias.

## Funcionalidades

- Busca uma lista de usuários na API [JSONPlaceholder](https://jsonplaceholder.typicode.com/) e exibe em uma tabela (nome, usuário, email e empresa)
- Botão "exibir" que busca os detalhes de um usuário específico e preenche um formulário
- Exibição de dicas aleatórias periódicas, consumidas da API [Advice Slip](https://api.adviceslip.com/)
- Mensagem de "carregando..." enquanto os dados são buscados
- Tratamento de erros de requisição (caso a API não responda)
- Layout responsivo para telas menores

## Tecnologias utilizadas

- HTML5
- CSS3 (Flexbox, media queries, `table-layout: fixed`)
- JavaScript (async/await, fetch, manipulação de DOM)

## Como rodar o projeto

1. Clone o repositório:
   ```
   git clone https://github.com/CaioFranciscoCS/lista-usuarios.git
   ```
2. Abra a pasta do projeto no VS Code.
3. Use a extensão **Live Server** e clique com o botão direito no arquivo `index.html` → **"Open with Live Server"**.

> Obs: os arquivos usam caminhos relativos a partir da raiz do projeto, por isso é necessário rodar com um servidor local (como o Live Server).

## Melhorias futuras

- Adicionar `try/catch` também nas funções `updateTable()` e `userDetail()`
- Permitir busca/filtro de usuários na tabela
