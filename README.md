# FirstSpirit Connect for Commerce - Mock-o-Merce

This repository contains a reference project which generates and delivers a fake e-commerce REST API.

### Prerequisites

- Docker and Docker Compose
- NPM

## Getting Started

- Clone the project using Git
  - `git clone https://github.com/e-Spirit/fcecom-mock-o-merce.git`
- Navigate to the directory called `mock-o-merce`

### Development with Docker

- Start the project with `./start.sh`

### Development without Docker

- Run `npm install` to install the dependencies
- Start the project with `npm start`

## Generate new fake data

Use `npm run create:db` and follow the guided creation process

Strings were generated with [random-words](https://www.npmjs.com/package/random-words), where "_translations_" are only single letter masks.
[JSON Server](https://github.com/typicode/json-server) is used to deliver the data.

## Author

[Crownpeak Technology GmbH](https://www.crownpeak.com)

## License

This project is licensed under the Apache License Version 2.0, January 2004 - see the [LICENSE](LICENSE) file for details
