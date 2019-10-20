# phaser-quickstart

## Sobre o phaser-quickstart

O Intellisense, sem dúvida facilita muito a produção de novas aplicações, e trabalhar sem ele, dependendo sempre da documentação pode ser estressante e desmotivador, para isso, foi criado o phaser-quickstart, que vem com uma demo simples do [Hello World da Phaser](https://phaser.io/tutorials/getting-started-phaser3/part5), e integração com o webpack e ES6 modules, facilitando o acesso ao intellisense!

## Como começar?

Utilizar o phaser-quickstart é extremamente simples!<br/>
Você precisará dos seguintes programas em seu computador:<br/>
- [git](https://git-scm.com/downloads)
- [nodeJS/npm](https://nodejs.org/en/)

Passo 1: Clonar o repositório, substituindo "nome-do-seu-jogo" pelo nome do seu jogo:
```
git clone https://github.com/PQrux/phaser-quickstart.git nome-do-seu-jogo
```
Passo 2: Instalar os pacotes:
```
npm install
```
Passo 3: Nomear seu jogo:
Edite o arquivo package.json
```
{
  "name": "nome-do-seu-jogo",
  ...
}
```
Edite o arquivo public/index.html
```
<html lang="en">
  <head>
    <title>nome-do-seu-jogo</title>
    ...
  </head>
</html>
```
Passo 4: Executar!
```
npm start
```

## Outros projetos como esse

Existem outros projetos com a mesma ideia do phaser-quickstart, porém com aspectos diferentes, sendo o maior deles a complexidade, diferente desses projetos que adicionam camadas de complexidade para tornar o projeto mais otimizado, e possuem também, Demos muito complexas, o phaser-quickstart se preocupa em trazer um simples projeto com integração ao webpack para facilitar o uso da framework em conjunto com o Intellisense, para programadores que estão iniciando seu aprendizado com a framework.<br/>
Alguns desses projetos são: <br/>
- [create-phaser-app](https://github.com/simiancraft/create-phaser-app)
- [phaser-es6-webpack](https://github.com/lean/phaser-es6-webpack)
- [phaser3-es6-webpack](https://github.com/nkholski/phaser3-es6-webpack)

## Referências

- https://www.sitepoint.com/bundle-static-site-webpack/ Utilizado para aprender a utilização do webpack.
- https://github.com/simiancraft/create-phaser-app Me baseei na configuração do webpack deste projeto para criar a minha.
