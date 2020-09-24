<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

# Desafio GoRestaurant Mobile

![Badge](https://img.shields.io/badge/types-Flow%20%7C%20TypeScript-blue)
![Badge](https://img.shields.io/badge/Bootcamp%20Rocketseat-React%20Native-blueviolet)
![Badge](https://img.shields.io/badge/node-%3E%3D%2012.18.2-brightgreen)

> Status do Projeto: (✔️ Concluído)

## Tópicos

🔹 [Sobre o desafio](#🚀-sobre-o-desafio)

🔹 [Template da aplicação](#📓-template-da-aplicação)

🔹 [Funcionalidades](#ℹ️-funcionalidades)

🔹 [Pré-requisitos](#✨-pré-requisitos)

🔹 [Como configurar banco de dados](#💾-iniciar/configurar-banco-de-dados)

🔹 [Como rodar a aplicação](#▶️-como-rodar-a-aplicação)

🔹 [Como rodar os testes](#🏗-como-rodar-os-testes)

🔹 [Layout da Aplicação](#💻-layout-da-aplicação)

🔹 [Tarefas em aberto](#💻-tarefas-em-aberto)

🔹 [Resolvendo Problemas](#❗️-resolvendo-problemas)

## 🚀 Sobre o desafio

<p align="justify">
  Nesse desafio, irei desenvolver a aplicação a GoRestaurant, na versão mobile para o cliente.
  <br>
  Essa será uma aplicação que irá se conectar a uma Fake API, e exibir e filtrar os pratos de comida da API e permitir a criação de novos pedidos.
</p>

## 📓 Template da aplicação

O template original utilizado é o que a Rocketseat disponibilizou na seguinte url: **[Acessar Template](https://github.com/rocketseat-education/gostack-template-react-native-delivery)**

**Dica**: Caso não saiba utilizar repositórios do Github como template, temos um guia no **[FAQ](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/faq-desafios).**

## ℹ️ Funcionalidades

✔️ Listar comidas da API

✔️ Listar um prato baseado no `id`

✔️ Listar as categorias cadastradas

✔️ Listar os pedidos efetuados

✔️ Listar os pratos favoritos

## ✨ Pré-requisitos

⚠️ [Node](https://nodejs.org/en/download/)

⚠️ [Yarn](https://yarnpkg.com/getting-started/install)

⚠️ [Google ADB](https://developer.android.com/studio/command-line/adb)

## 💾 Iniciar/Configurar banco de dados

Está configurado no package.json uma dependência chamada json-server, e um arquivo chamado server.json que contém os dados para as rotas, é uma Fake API. Não é necessária nenhuma alteração.

## ▶️ Como rodar a aplicação

### Passos para mobile

Para configurar seu ambiente corretamente siga o [tutorial que a Rocketseat fez](https://react-native.rocketseat.dev/)!

### Inicializar

Agora navegue até a pasta criada e abra no Visual Studio Code, lembre-se de executar o comando `yarn` no seu terminal para instalar todas as dependências.

Executar `yarn json-server server.json -p 3333` para rodar a Fake API

Execute `yarn start` e depois `yarn android` para inicializar a aplicação no Android ou `yarn ios` para inicializar no iOS.

Pronto! Agora basta acessar a aplicação à partir do seu emulador ou aparelho.

Caso a aplicação não apareça, execute `adb reverse tcp:3333 tcp:3333`.

## 🏗 Como rodar os testes

```bash
yarn test
```

## 💻 Layout da Aplicação

### Home e Dashboard

<img src="https://github.com/MGustav0/desafio-react-native-delivery/blob/master/extras/screenshots/01_-_home.jpg" width="320" heigth="180" /> <img src="https://github.com/MGustav0/desafio-react-native-delivery/blob/master/extras/screenshots/02_-_dashboard.jpg" width="320" heigth="180" />

### Selecionar Categoria e Prato

<img src="https://github.com/MGustav0/desafio-react-native-delivery/blob/master/extras/screenshots/03_-_select_categorie.jpg" width="320" heigth="180" /> <img src="https://github.com/MGustav0/desafio-react-native-delivery/blob/master/extras/screenshots/04_-_select_plate.jpg" width="320" heigth="180" />

### Pratos Selecionados

<img src="https://github.com/MGustav0/desafio-react-native-delivery/blob/master/extras/screenshots/05_-_my_foods.jpg" width="320" heigth="180" />

### Selecionar e Mostrar Favoritos

<img src="https://github.com/MGustav0/desafio-react-native-delivery/blob/master/extras/screenshots/06_-_favoriting.jpgv" width="320" heigth="180" /> <img src="https://github.com/MGustav0/desafio-react-native-delivery/blob/master/extras/screenshots/07_-_favorites.jpg" width="320" heigth="180" />

## 📝 Tarefas em aberto

🖊 Nenhuma!

## ❗️ Resolvendo Problemas

Caso encontre algum problema, bug ou erro me conte [aqui](https://github.com/MGustav0/desafio-react-native-delivery/pulls)!

## 🐙 Desenvolvedores

| [<img src="https://avatars1.githubusercontent.com/u/18315899?s=460&u=54d9c6ea66f2b27120bf39dabe1d36ff22a92b9d&v=4>][(https://github.com/MGustav0](https://avatars1.githubusercontent.com/u/18315899?s=460&u=54d9c6ea66f2b27120bf39dabe1d36ff22a92b9d&v=4))" width=115><br><sub>Gustavo Moreira</sub>](https://github.com/MGustav0) |
| :---: |

## Licença

Desafio proposto com 💜 by Rocketseat 👋

The [MIT License](https://opensource.org/licenses/MIT) - Use freely, I am not responsible for the actions of third parties.

©️ Copyright? 2020 - Proffy - Intellectual property does not exist! Copying Is Not Theft.
