<p align="center">
  <h1> Food Explorer - Elizandra Monteiro </h1>
</p>

<p align="center">
  <img alt="Imagem Ilustrativa Light Mode" src="./public/01details.png" width="100%">
</p>

Este é o resultado do desafio final do Explorer, o Food Explorer.
<br>
Nele realizei a criação do FrontEnd e do BackEnd completo da aplicação.

___

## 💻 Sobre
O Food Explorer é uma aplicação web de um restaurante. Após se cadastrar na plataforma o usuário estará apto a criar os pedidos e acompanhar o status dele. Há ainda uma customização de perfil, filtragem de favoritos, campo de busca e seção de contato com o restaurante. O carrinho é 100% funcional e o usuário pode escolher entre 2 formas de pagamento (cartão ou Pix). O Administrador terá a capacidade de criar/editar/remover os pratos da forma que desejar. Ele poderá ainda alterar o status dos pedidos, de acordo com a linha de preparo dos mesmos na cozinha. Este status será imediatamente atualizado na tela dos consumidores. Como a possibilidade de mudança de tema da página, customização do perfil do usuário(avatar, nome e senha), conta ainda com diversos efeitos visuais e o mais importante de tudo: É responsivo para a utilização em diversos tipos de dispositivos!

Este repositório contém os dados do Frontend da minha aplicação em React.js.

___

## 🎨 Layout
A página inicial em formato desktop é vista na imagem abaixo:

<img alt="Imagem Ilustrativa Light Mode" src="./public/img02.png" width="100%">
<img alt="Imagem Ilustrativa Simulador de celular " src="./public/mobile.png" width="40%">

___

## 🛠 Tecnologias

As seguintes tecnologias foram empregadas na criação deste projeto:

- [ReactJs](https://reactjs.org)
- [Node.js](https://nodejs.org/en/)
- [Javascript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [Vite](https://vitejs.dev/)
- [Express](https://expressjs.com)
- [Nodemon](https://nodemon.io/)
- [SQLite](https://www.sqlite.org/index.html)
- [Knex](https://knexjs.org/)
- [BCryptjs](https://www.npmjs.com/package/bcryptjs)
- [JSON Web Token](https://www.npmjs.com/package/jsonwebtoken)
- [Multer](https://www.npmjs.com/package/multer)
- [CORS](https://www.npmjs.com/package/cors)
- [Axios](https://www.npmjs.com/package/axios)
- [Styled Components](https://styled-components.com/)
- [React Icons](https://react-icons.github.io/react-icons/)
- [Swiper](https://swiperjs.com/)
- [React Router Dom](https://react-icons.github.io/react-icons/)

___

## 🚀 Como utilizar

Clone o projeto para o local desejado em seu computador.

```bash
$ git clone git@github.com:ElizandraMonteiro/Food-Explorer-Frontend
```
___

#### 🚧 Executando o BackEnd
```bash
# No BackEnd insira uma porta e um secret no arquivo .env vazio
  AUTH_SECRET=
  PORT=

# Navegue até o diretório do BackEnd
$ cd food-explorer-backend

# Instale as dependências necessárias
$ npm install

# Agora inicie o servidor do BackEnd
$ npm run dev
```
___

#### 💻 Executando o FrontEnd
```bash
# Navegue até o diretório do FrontEnd
$ cd food-explorer-frontend

# Instale as dependências necessárias
$ npm install

# Agora inicie o servidor do FrontEnd
$ npm run dev

# O terminal irá exibir o endereço local onde a aplicação está sendo executada. Basta digitar o mesmo endereço em seu navegador preferido. O endereço usado na criação do projeto foi este:

  http://localhost:5173/
```

#### 🔑 Quer ver como a aplicação funciona vista pelo Admin? Use a conta a seguir:

```bash
  e-mail: admin@foodexplorer.com
  senha: 123456
```
___

Este BackEnd foi hospedado diretamente no Render.
Já o Frontend foi hospedado diretamente no Netlify.

___
⚠️ **Importante**: Este projeto está utilizando uma hospedagem gratuita para o seu backend, portanto, pode haver atrasos no tempo de resposta do servidor. 
