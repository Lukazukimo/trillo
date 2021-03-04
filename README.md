<p align="center">
    <img src="/github/logoTitle.svg" height='200'>
</p>

<p align="center">
    <img src="https://img.shields.io/static/v1?label=made with&message=html5&color=FF5722&style=for-the-badge&logo=html5"/>
    <img src="https://img.shields.io/static/v1?label=made with&message=css3&color=039BE5&style=for-the-badge&logo=CSS3"/>
    <img src="https://img.shields.io/static/v1?label=made with&message=sass&color=CF649A&style=for-the-badge&logo=sass"/>
    <img src="https://img.shields.io/static/v1?label=made with&message=node&color=4CAF50&style=for-the-badge&logo=node.js"/>
    <img src="https://img.shields.io/static/v1?label=by&message=Lukazukimo&color=bd93f9&style=for-the-badge"/>
</p>

---

<h4 align="center">
 🚧  Concluído 🚧
</h4>

<p align="center">
    <a href="#-sobre-o-projeto">Sobre</a> •
    <a href="#movie_camera-demonstração">Demo</a> •
    <a href="#-pré-requisitos">Pré-requisitos</a> •
    <a href="#cd-como-executar-o-projeto">Como executar</a> •
    <a href="#game_die-script">Script</a> •
    <a href="#-tecnologias">Tecnologias</a> •
    <a href="#-autor">Autor</a> •
    <a href="#créditos">Créditos</a>
</p>

### 💻 Sobre o projeto

Landing Page de um website de viagens.

Projeto desenvolvido com foco no aprendizado do _Flexbox_ no curso da udemy **_Advanced CSS and Sass: Flexbox, Grid, Animations and More!_** por **_[Jonas Schmedtmann](https://github.com/jonasschmedtmann)_**.

<p align="center">
    <img src="/github/img.png" height='400'>
<p/>

### :movie_camera: Demonstração

Segue o [link](https://lukazukimo.github.io/trillo/) para a demonstração do projeto ao vivo.

### 📌 Pré-requisitos

Antes de começar, será ncessário ter instalado [Node.js](https://nodejs.org/en/)

<!-- ### :cd: Como executar o projeto -->

### :cd: Como executar o projeto

```bash
# Clone este repositório
$ git clone <https://github.com/Lukazukimo/trillo>

# Acesse a pasta do projeto no terminal/cmd
$ cd trillo

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run devserver

> ⚠️ O servidor iniciará na porta:8080 - Acesse <http://localhost:8080 <
```

### :game_die: Script

Para os seguintes scripts utilize `npm run` _comando_

#### watch:sass

Comando utilizado para que o pré-processador observe as alterações nos aquivos de origem e recompile o _Css_ cada vez que salvar o _Sass_

<!-- prettier-ignore -->
```node
<!-- npm run watch:sass -->
watch:sass: "node-sass sass/main.scss css/style.css -w"
```

#### devserver

Comando utilizado para carregar um pequeno servidor de desenvolvimento com o objetivo de recarregar ao vivo

```node
<!-- npm run devserver -->
devserver: "live-server"
```

#### start

Comando utilizado para executar o devserver e o watch:sass em paralelo

```node
<!-- npm run start -->
start: "npm-run-all --parallel devserver watch:sass";
```

#### compile:sass

Comando utilizado para compilar o arquivo _Sass_ para o _Css_

<!-- prettier-ignore -->
```node
<!-- npm run compile:sass -->
compile:sass: "node-sass sass/main.scss css/style.comp.css";
```

#### prefix:css

Comando utilizado para adicionar os prefixos que suportem nas últimas 10 versões dos navegadores ao arquivo _Css_

<!-- prettier-ignore -->
```node
<!-- npm run prefix:css -->
prefix:css: "postcss --use autoprefixer -b \"last 10 versions\" css/style.concat.css -o css/style.prefix.css"

```

#### compress:css

Comando utilizado para comprimir o arquivo _Css_ para deixá-lo mais leve

<!-- prettier-ignore -->
```node
<!-- npm run compress:css -->
compress:css: "node-sass css/style.prefix.css css/style.css --output-style compressed"
```

#### build:css

Comando utilizado para criar o arquivo final do _Css_ executando todos os scripts anteriores, sendo eles: `compile:sass`, `concat:css`, `prefix:css`, `compress:css`

<!-- prettier-ignore -->
```node
<!-- npm run build:css -->
build:css: "npm-run-all compile:sass concat:css prefix:css compress:css"
```

### 🛠 Tecnologias

As seguintes ferramentas foram utilizadas na construção do projeto:

<!-- prettier-ignore -->
- [Html](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [Css](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [Sass](https://sass-lang.com/)
- [Node](https://nodejs.org/en/)

### 🧑‍💻 Autor

<img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/13020420?s=400&v=4" width="100px;" alt=""/>
<br />
Fabio Wu Huang
<br />

[![Linkedin Badge](https://img.shields.io/badge/-Fabio-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fabio-wu-huang/)](https://www.linkedin.com/in/fabio-wu-huang/) [![Gmail Badge](https://img.shields.io/badge/-lukazukimomr@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:lukazukimomr@gmail.com)](mailto:lukazukimomr@gmail.com)

### Créditos

Este projeto foi desenvolvido por **_[Jonas Schmedtmann](https://github.com/jonasschmedtmann)_**
Confira no **_[repositório](https://github.com/jonasschmedtmann/advanced-css-course)_** oficial

---
