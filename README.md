# TypeScript Boilerplate

## Quick start

Make sure [Node.js](https://nodejs.org/en/download), [Yarn](https://yarnpkg.com/lang/en/docs/install/) and [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) are installed in your system before starting.

1. Clone or download the repo (Click on **Use this template** if you want to create your own repo)
2. Open `package.json` in your editor and change the values of: **name**, **description**, **author**, **repository**, **keywords**
3. Run `yarn install`

You are ready to go. Edit `src/index.ts` and run `yarn start` to execute it.

## Scripts

#### `yarn start`

Starts the app with hot reloading.

The app will refresh every time a file is changed in the `src` folder.

#### `yarn build`

Builds the app in the `build` folder.

#### `yarn build:start`

Builds the app in the `build` folder and starts it.

#### `yarn test`

Runs the tests.

#### `yarn prettier`

Runs `Prettier` in the `src` folder fixing all fixable issues.

#### `yarn lint`

Runs `ESLint` in the `src` folder fixing all fixable issues.

#### `yarn release`

Generates the changelog and increase the version from commit messages.

The most common convention for commit messages is the Angular convention which is [detailed here](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines).

## Tools

#### [Jest](https://jestjs.io)

Testing framework.

#### [Prettier](https://prettier.io)

Code formatter.

#### [ESLint](https://eslint.org/)

Code syntax analyzer.

#### [Husky](https://github.com/typicode/husky)

Allows to run scripts on [git hooks](https://git-scm.com/docs/githooks#_hooks#readme)

#### [Standard Version](https://github.com/conventional-changelog/standard-version#readme)

Automatic changelog generation powered by [Conventional Commits](https://conventionalcommits.org).

## References

[How to Setup a TypeScript + Node.js Project](https://khalilstemmler.com/blogs/typescript/node-starter-project)

[TypeScript Deep Dive](https://basarat.gitbook.io/typescript)
