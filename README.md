<h1 align="center">
     🛒 <a href="#" alt=""> GoMarketplace </a>
</h1>

<h3 align="center">
    🛒 App mobile de e-commerce com página de produtos e carrinho de compras 🏬
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/lucasbarzan/gomarketplace?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/lucasbarzan/gomarketplace">
  
  <a href="https://github.com/lucasbarzan/gofinances/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/lucasbarzan/gomarketplace">
  </a>
    
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/lucasbarzan/gomarketplace/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/lucasbarzan/gomarketplace?style=social">
  </a>
</p>

<h4 align="center">
	Concluído 🚀
</h4>

Tabela de conteúdos
=================

   * [Sobre o projeto](#sobre-o-projeto)
   * [Funcionalidades](#funcionalidades)
   * [Layout](#layout)
     * [Mobile](#layout-mobile)
   * [Como executar o projeto](#como-executar-o-projeto)
     * [Pré-requisitos](#pre-requisitos)
     * [Rodando a fake API](#rodando-o-backend)
     * [Rodando a aplicação mobile (Frontend)](#rodando-a-aplicacao-mobile-frontend)
   * [Tecnologias](#tecnologias)
     * [Mobile](#tecnologias-mobile)
     * [Utilitários](#utilitarios)
   * [Como contribuir no projeto](#como-contribuir)
   * [Autor](#autor)
   * [Licença](#licenca)



## 💻 Sobre o projeto <a name="sobre-o-projeto"></a>

🛒 O GoMarketplace é um app mobile feito com React Native que simula uma página de produtos e um carrinho de compras.


Projeto desenvolvido durante o bootcamp **GoStack** oferecido pela [Rocketseat](https://rocketseat.com.br/).

---

## ⚙️ Funcionalidades <a name="funcionalidades"></a>

- [x] Os usuários tem acesso ao app mobile, onde podem:
  - [x] Listar os produtos
  - [x] Adicionar itens ao carrinho
  - [x] Editar os itens no carrinho (aumentar e diminuir a quantidade)
  - [x] Visualizar o valor total do carrinho

---

## 🎨 Layout <a name="layout"></a>

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/VClTghBlXGYDhD7EAXjcWi/GoMarketplace?node-id=0%3A1">
  <img alt="Layout mobile no Figma" src="https://img.shields.io/badge/Acessar%20Mobile%20-Figma-%2304D361">
</a>

### Mobile <a name="layout-mobile"></a>

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="Screenshot mobile 1" src="./assets/mobile-list.svg" width="200px">

  <img alt="Screenshot mobile 2" src="./assets/mobile-cart.svg" width="200px">
</p>

---

## 🚀 Como executar o projeto <a name="como-executar-o-projeto"></a>

Este projeto consiste em:
1. Frontend Mobile (pasta mobile)

💡 O Frontend Mobile utiliza uma fake API que roda na porta 3333

### Pré-requisitos <a name="pre-requisitos"></a>

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/).

#### 🎲 Rodando a fake API <a name="rodando-o-backend"></a>

```bash

# Clone este repositório
$ git clone git@github.com:lucasbarzan/gomarketplace.git

# Acesse a pasta do projeto no terminal/cmd
$ cd gomarketplace

# Vá para a pasta do frontend (mobile)
$ cd mobile

# Instale as dependências
$ npm install

# Execute o script da fake API
$ npm run json-server server.json -p 3333

# O servidor inciará na porta:3333 - acesse http://localhost:3333 

```


#### 📱 Rodando a aplicação mobile (Frontend) <a name="rodando-a-aplicacao-mobile-frontend"></a>

Siga as instruções [deste link](https://react-native.rocketseat.dev/) para configurar o ambiente de desenvolvimento mobile em React Native e poder rodar a aplicação na sua máquina.

---

## 🛠 Tecnologias <a name="tecnologias"></a>

As seguintes ferramentas foram usadas na construção do projeto:

-   **[EditorConfig](https://editorconfig.org/)**
-   **[ESLint](https://eslint.org/)**
-   **[Prettier](https://prettier.io/)**
-   **[json-server](https://github.com/typicode/json-server)**

#### **Mobile**  ([React Native](https://reactnative.dev/)  +  [TypeScript](https://www.typescriptlang.org/)) <a name="tecnologias-mobile"></a>


-   **[React Navigation](https://reactnavigation.org/)**
-   **[React Native Gesture Handler](https://github.com/software-mansion/react-native-gesture-handler)**
-   **[React Native Screens](https://github.com/software-mansion/react-native-screens)**
-   **[React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)**
-   **[React Native Safe Area Context](https://github.com/th3rdwave/react-native-safe-area-context)**
-   **[React Native iPhone X Helper](https://github.com/ptelad/react-native-iphone-x-helper)**
-   **[@react-native-community/async-storage](https://github.com/react-native-community/async-storage)**
-   **[Styled Components](https://styled-components.com/)**
-   **[Axios](https://github.com/axios/axios)**

> Veja o arquivo  [package.json](https://github.com/lucasbarzan/gomarketplace/blob/master/mobile/package.json)

#### **Utilitários** <a name="utilitarios"></a>

-   Protótipo:  **[Figma](https://www.figma.com/)**
-   Editor:  **[Visual Studio Code](https://code.visualstudio.com/)**
-   Teste de API:  **[Insomnia](https://insomnia.rest/)**


---

## 💪 Como contribuir no projeto <a name="como-contribuir"></a>

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`

---

## 🦸 Autor <a name="autor"></a>

<a href="https://github.com/lucasbarzan/">
 <img src="https://avatars2.githubusercontent.com/u/25365429?s=460&u=ac94c8da0e69db2558f031d01dbca5c60aa19b77&v=4" width="100px" alt="Lucas Barzan" />
 <br />
 <sub><b>Lucas Barzan</b></sub></a>
 <br />

[![Linkedin Badge](https://img.shields.io/badge/-LucasBarzan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lucasbarzan/)](https://www.linkedin.com/in/lucasbarzan/) 
[![Gmail Badge](https://img.shields.io/badge/-lucasbarzand@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:lucasbarzand@gmail.com)](mailto:lucasbarzand@gmail.com)

---

## 📝 Licença <a name="licenca"></a>

Este projeto esta sob a licença [MIT](./LICENSE).

Feito com ❤️ por Lucas Barzan 👋🏽 [Entre em contato!](https://www.linkedin.com/in/lucasbarzan/)


