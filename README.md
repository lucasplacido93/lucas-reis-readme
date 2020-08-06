# Template Readme Lucas Reis
> Repositorio para praticar readme

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

## Requisitos

- [Git](https://git-scm.com/) 
- [Node.js](https://nodejs.org/)
- [Npm](https://www.npmjs.com/) 
- [Angular](https://pt-br.reactjs.org/)

## Configuração

Após clonar o repositório, tenha certeza de ter Node e NPM instalados na sua máquina. Após resolver essas dependências, instale as dependências e o Angular CLI (versão 1.7.0) através do comando:

```sh 
npm setup
``` 

Esse comando irá instalar as dependências externas e compilar as dependências internas através da pasta *libs*. Para verificar o comando abra o arquivo *package.json* e procure pela seção *scripts*

Para iniciar o projeto, execute o comando:

```sh ng serve
``` 

A aplicação estará disponível no endereço [http://localhost:4200](http://localhost:4200)

*Obs*.: A versão inicia do frontend usava Angular 5 com Angular CLI (1.7.0).

## Usage example

A few motivating and useful examples of how your product can be used. Spice this up with code blocks and potentially more screenshots.

_For more examples and usage, please refer to the [Wiki][wiki]._

## Development setup

Describe how to install all development dependencies and how to run an automated test-suite of some kind. Potentially do this for multiple platforms.

```sh
make install
npm test
```

## Release History

* 0.2.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.2.0
    * CHANGE: Remove `setDefaultXYZ()`
    * ADD: Add `init()`
* 0.1.1
    * FIX: Crash when calling `baz()` (Thanks @GenerousContributorName!)
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

## Meta

Your Name – [@YourTwitter](https://twitter.com/dbader_org) – YourEmail@example.com

Distributed under the XYZ license. See ``LICENSE`` for more information.

[https://github.com/yourname/github-link](https://github.com/dbader/)

## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
