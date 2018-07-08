# Life Design | Mongeral Aegon

[![GitHub forks](https://img.shields.io/github/forks/rafaeltorres89/tvt-mg-ds.svg)](https://github.com/rafaeltorres89/tvt-mg-ds/network)
[![npm](https://img.shields.io/npm/v/npm.svg)](https://github.com/rafaeltorres89/tvt-mg-ds/npm)

-------

<h3 align="center">
  <img src="https://madstyle.mongeralaegon.com.br/assets/app/css/img/site/global/mongeral-aegon-logo-site.png" alt="Mongeral Aegon" />
</h3>

<p align="center">
    <a href="#about">About</a> &bull;
    <a href="#features">Features</a> &bull;
    <a href="#organization">Organization</a> &bull;
    <a href="#installation">Installation</a>
</p>

## About

The Life Design of Aegon Mongeral was thought of as an enterprise desgin system. Where all development and creation content is presented directly on the website (http://lifedesign-mongeral.com).

The goal since git directory, is to store the developed and created structure as a backup. In addition, you are thinking of contributing to the development of Life Design, you will be able to learn in an easy and effective way what and how we work in our team.

Welcome, and good luck!



## Features

Write



## Organization

Complete design structure

```
gulp-file/
├── assets
│   ├── css
│   │   │── app.css
│   │   └── mongeral.min.css
│   ├── img
│   └── js
├── node_modules* (ignore git)
├── src
│   └── scss
│       │── base
│       │   └── _nomalize.scss
│       │── components
│       │   │── _button.scss
│       │   └── _checkbox.scss
│       │── helpers
│       │   │── _animate.scss
│       │   │── _colors.scss
│       │   │── _fonts.scss
│       │   │── _mixins.scss
│       │   │── _settings.scss
│       │   └── _variables.scss
│       │── _general.scss
│       └── app.scss
├── .gitignore
├── gulpfile.js
├── index.html
└── packege.json
README.md
```



## Installation

For this work, we are using technologies such as [Gulp](https://gulpjs.com/), [Sass](https://sass-lang.com/), [NPM](https://www.npmjs.com/) and [React Native](http://www.reactnative.com/). If you do not know these technologies, click on the links and read about them.

To work on the project, you need to perform some functions on your system and git.

Configure your machine as follows:

* Logue com sua conta no GIT.

<h4 align="center">
  <img src="https://image.ibb.co/cmZs7T/git_init.png" alt="Git" />
</h4>

* Acesse o projeto no link [Life Design Mongeral no Git](https://github.com/rafaeltorres89/tvt-mg-ds).

<h4 align="center">
  <img src="https://image.ibb.co/hzxR1o/git_repositorio.png" alt="Repositorio" />
</h4>

* No botão "FORK", no canto superior do seu git, clique e espere o ok da página. 

<h4 align="center">
  <img src="https://blog.da2k.com.br/uploads/2015/02/fork-repository.png" alt="Fork" />
</h4>

* Após o fork do repositório, repare que abaixo do nome do repositório é mostrado o repositório original.

<h4 align="center">
  <img src="https://blog.da2k.com.br/uploads/2015/02/forked-from.png" alt="Repositório real" />
</h4>

* Clone o respositório no botão verde acima do conteúdo. 

<h4 align="center">
  <img src="https://image.ibb.co/fDvw1o/clone.png" alt="Clone" />
</h4>

Vá ao terminal, encontre a pasta desejada e digite:
```
git clone https://github.com/rafaeltorres89/tvt-mg-ds.git
```

* Crie uma brach para codar as features. 
```
git branch
```
A resposta deve ser: 
```
* master
```
Por convenção, o git utiliza a branch master como padrão, para o código estável do projeto. Então, tudo o que estiver nessa branch, em qualquer repositório, ~~teóricamente~~ é código estável. Logo, você nunca irá mexer diretamente nela, mas em outras branchs, para então fazer merge com a master.

Agora vamos criar a branch com nossa feature. Temos duas formas de fazer isso. A forma mais rápida é:
```
git checkout -b improve_method_watch
```
"improve_method_watch" é o nome da nossa branch

* Em paralelo, instale o npm em sua máquina.
* Agora instale o gulp
* Instale o Dev-Gulp (repare que aparecerá a pasta XPTO)
* Instale o Sass-Gulp