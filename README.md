# Desafio-Conceito-Nodejs

<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />

<h3 align="center">
  Desafio 02: Conceitos do Node.js
</h3>


## :rocket: Sobre o desafio
Nesse desafios foi estabelecido conceitos que foi ensinado durantes o primeiro módulo do bootcamp. O projeto consiste em armazenar positórios do meu (seu) portifólio. Essa aplicação permite a criação, listagem, atualização e a remoção de um repositórios, também adicionamos uma rota onde o usuário pode alterar o like.

### Rotas da aplicação

- [x]  **`POST /repositories`**: A rota deve receber `title`, `url` e `techs` dentro do corpo da requisição, sendo a URL o link para o github desse repositório. Ao cadastrar um novo projeto, ele deve ser armazenado dentro de um objeto no seguinte formato: `{ id: "uuid", title: 'Desafio Node.js', url: 'http://github.com/...', techs: ["Node.js", "..."], likes: 0 }`; Certifique-se que o ID seja um UUID, e de sempre iniciar os likes como 0.
- [x]  **`GET /repositories`**: Rota que lista todos os repositórios;
- [x]  **`PUT /repositories/:id`**: A rota deve alterar apenas o `title`, a `url` e as `techs` do repositório que possua o `id` igual ao `id` presente nos parâmetros da rota;
- [x]  **`DELETE /repositories/:id`**: A rota deve deletar o repositório com o `id` presente nos parâmetros da rota;
- [x]  **`POST /repositories/:id/like`**: A rota deve aumentar o número de likes do repositório específico escolhido através do `id` presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes deve ser aumentado em 1;

### Clonando o projeto

#### Requisitos para instalação
- NodeJS na versão 8 ou superior;
- yarn ou npm;
- curl, postman ou insomnia.

```jsx
git clone https://github.com/mauriani/Desafio-Conceito-Nodejs
```

### Executando

Antes de dá start na aplicação você tem que instalar as dependências através do comando:

```jsx
yarn 
or 
npm install
```

Depois disso basta rodar:

```jsx
yarn dev
```






