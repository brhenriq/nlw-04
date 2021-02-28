<h1 align="center">NPS Calculator</h1>

<h4 align="center"> 
	🚧  NPS Calculator ✔ Concluído 🚀 🚧
</h4>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-layout">Layout</a> • 
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> 
</p>


## 💻 Sobre o projeto

O Projeto trata-se de uma API, com foco no cálculo do NPS (Net Promoter Score)


Projeto desenvolvido durante a **4ª Edição do NLW - Next Level Week** oferecida pela [Rocketseat](https://blog.rocketseat.com.br/primeira-next-level-week/).
O NLW é uma experiência online com muito conteúdo prático, desafios e hacks onde o conteúdo fica disponível durante uma semana.

---

## ⚙️ Funcionalidades

- [x] Cadastro de usuários;
- [x] Cadastro de pesquisas;
- [x] Envio de e-mail, com as pesquisas, para os usuários;
- [x] Cálculo do NPS a partir da resposta do usuário;

---

## 🚀 Como executar o projeto

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### 🎲 Rodando o Backend (servidor)

```bash

# Clone este repositório
$ git clone https://github.com/brhenriq/nlw-04

# Acesse a pasta do projeto no terminal/cmd
$ cd nlw-04

# Instale as dependências
$ npm install

# Cire o banco sqlite
$ npm typeorm migration:run

# Execute a aplicação
$ npm dev

# O servidor inciará na porta:3333 - acesse http://localhost:3333 

```
---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [	<img alt="NodeJS" src="https://img.shields.io/badge/node.js%20-%2343853D.svg?&style=for-the-badge&logo=node.js&logoColor=white"/>](https://nodejs.org/en/)
-   [<img alt="TypeScript" src="https://img.shields.io/badge/typescript%20-%23007ACC.svg?&style=for-the-badge&logo=typescript&logoColor=white"/>](https://www.typescriptlang.org/)
-   [<img alt="Express.js" src="https://img.shields.io/badge/express.js%20-%23404d59.svg?&style=for-the-badge"/>](https://expressjs.com/)
-   [<img alt="SQLite" src ="https://img.shields.io/badge/sqlite-%2307405e.svg?&style=for-the-badge&logo=sqlite&logoColor=white"/>](https://github.com/mapbox/node-sqlite3)
-   [<img alt="Jest" src="https://img.shields.io/badge/-jest-%23C21325?&style=for-the-badge&logo=jest&logoColor=white"/>](https://jestjs.io)
- [TypeORM](https://typeorm.io/#/)
- [Ethereal Mail](https://ethereal.email)
- [Handlebars](https://handlebarsjs.com)

> Veja o arquivo  [package.json](https://github.com/brhenriq/nlw-04/blob/main/package.json)


#### **Utilitários**

- Editor:  [Visual Studio Code](https://code.visualstudio.com/)  → Extensions:  [SQLite](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite)
- Teste de API:  [Insomnia](https://insomnia.rest/)