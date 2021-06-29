[![Author](https://img.shields.io/badge/author-marioandre01-61dafb?style=flat-square)](https://github.com/marioandre01)
[![Languages](https://img.shields.io/github/languages/count/marioandre01/user-api-node-loopback?color=%2361dafb&style=flat-square)](#)
[![Stars](https://img.shields.io/github/stars/marioandre01/user-api-node-loopback?color=61dafb&style=flat-square)](https://github.com/marioandre01/user-api-node-loopback/stargazers)
[![Forks](https://img.shields.io/github/forks/marioandre01/user-api-node-loopback?color=%2361dafb&style=flat-square)](https://github.com/marioandre01/user-api-node-loopback/network/members)
[![Contributors](https://img.shields.io/github/contributors/marioandre01/user-api-node-loopback?color=61dafb&style=flat-square)](https://github.com/marioandre01/user-api-node-loopback/graphs/contributors)
[![Licence](https://img.shields.io/github/license/marioandre01/user-api-node-loopback?color=%2361dafb&style=flat-square)](https://github.com/marioandre01/user-api-node-loopback/blob/master/LICENCE.md)


<h1 align="center">
  <img alt="LoopBack-Badge" title="LoopBack-Badge" src="https://github.com/strongloop/loopback-next/raw/master/docs/site/imgs/branding/Powered-by-LoopBack-Badge-(blue)-@2x.png" />
  <br>
  <br>
  user-api-node-loopback
</h1>

<p align="center">
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-run-the-application">Run the application</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#gear-contribution">Contribution</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

## 💻 Project

This application is generated using [LoopBack 4 CLI](https://loopback.io/doc/en/lb4/Command-line-interface.html) with the
[initial project layout](https://loopback.io/doc/en/lb4/Loopback-application-layout.html).

<!-- O resultado da aplicação pode ser acessado através da seguinte URL: -->
<!-- [https://podcastr-next-nlw5.vercel.app/](https://podcastr-next-nlw5.vercel.app/) -->


## 📋 Technologies

The project was developed with the following technologies:

- [Loopback 4](https://loopback.io/doc/en/lb4/Command-line-interface.html)

## 💻 running the application

## Install dependencies

By default, dependencies were installed when this application was generated.
Whenever dependencies in `package.json` are changed, run the following command:

```sh
yarn install
```
Run docker-compose
```sh
sudo docker-compose up
```
Change mySql password method to native mode
```sql
ALTER USER 'root' IDENTIFIED WITH mysql_native_password BY 'root';
```
```sql
flush privileges;
```
Create schemas/tables for our models in database MySql
```sh
yarn run migrate
```

## Run the application

```sh
yarn start
```

You can also run `node .` to skip the build step.

Open http://127.0.0.1:3000 in your browser.

## Rebuild the project

To incrementally build the project:

```sh
yarn run build
```

To force a full build by cleaning up cached artifacts:

```sh
yarn run rebuild
```

## Fix code style and formatting issues

```sh
yarn run lint
```

To automatically fix such issues:

```sh
yarn run lint:fix
```

## Other useful commands

- `yarn run migrate`: Migrate database schemas for models
- `yarn run openapi-spec`: Generate OpenAPI spec into a file
- `yarn run docker:build`: Build a Docker image for this application
- `yarn run docker:run`: Run this application inside a Docker container

## Tests

```sh
yarn test
```
## :gear: Contribution

To contribute to this project, take the following steps:

- Fork this repository;
- Create a branch with your feature: `git checkout -b my-feature`;
- Commit your changes: `git commit -m 'feat: My new feature'`;
- Push to your branch: `git push origin my-feature`.

## What's next

Please check out [LoopBack 4 documentation](https://loopback.io/doc/en/lb4/) to
understand how you can continue to add features to this application.

[![LoopBack](https://github.com/strongloop/loopback-next/raw/master/docs/site/imgs/branding/Powered-by-LoopBack-Badge-(blue)-@2x.png)](http://loopback.io/)
