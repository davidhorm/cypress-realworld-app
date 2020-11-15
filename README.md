## What is this?

This is a fork from [cypress-io/cypress-realworld-app](https://github.com/cypress-io/cypress-realworld-app). Go read their [README](https://github.com/cypress-io/cypress-realworld-app/blob/develop/README.md) for more info about Cypress' Real World App.

### Motivations

I've been consuming a lot of media how to code differently. This is a project for me to refactor and implement the different best practices. What I hope to achieve:

* [Domain-Driven Design](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215/ref=sr_1_3?crid=2ZOO7DKTGNHAP&dchild=1&keywords=domain+driven+design&qid=1605482505&sprefix=domain+dri%2Caps%2C452&sr=8-3)
    * [Functional Domain Modeling](https://www.youtube.com/watch?v=PLFl95c-IiU)
* [Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
* [Living Documentation](https://smile.amazon.com/Living-Documentation-Cyrille-Martraire/dp/0134689321/ref=sr_1_2?crid=2YC145LKAU8YD&dchild=1&keywords=living+documentation&qid=1605479861&sprefix=living+docum%2Caps%2C223&sr=8-2)
    * [Cypress](https://www.cypress.io/)
    * [Storybook](https://storybook.js.org/)
    * [jsdoc-to-markdown](https://github.com/jsdoc2md/jsdoc-to-markdown) + [GitBook](https://github.com/GitbookIO/gitbook)

## Getting Started

### Prerequisites

The only requirement for this project is to have [Node.js](https://nodejs.org/en/) **version 12** installed on your machine. Refer to the [.node-version](./.node-version) file for the exact version.

TypeScript will be added as a local dependency to the project, so no need to install it.

### Installation

```shell
yarn install
```

### Run the app

```shell
yarn dev
```

### Start Cypress

```shell
yarn test
```

### Additional Yarn Scripts

| Script | Description |
| --- | --- |
| list:dev:users | Provides id and username for users in the dev database. The default password for all users is `s3cret`. |
| dev | Starts backend in watch mode and frontend |
| start | Starts backend and frontend |
| test | Open Cypress |
| test:mobile | Open Cypress with mobile viewport |
| test:coverage | Generate Coverage report. view the report at `coverage/index.html`. |
| prettier | Make code prettier |
