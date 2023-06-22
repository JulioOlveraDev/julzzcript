# Julzzscript

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

Compound project for managing my personal side projects

## Project structure

There are 2 packages inside this project:

- api: NestJS application
- expenses-tracker: VueJS application

Each of the packages have their own package.json file, so they define their dependencies as well as they have fully autonomy to publish a new version of the package into NPM or Yarn registry.

## How to install and execute

1. Clone this repository
2. Install the dependencies. Inside the root `$ npm install`
3. Start both applications. `$ npm run dev`
