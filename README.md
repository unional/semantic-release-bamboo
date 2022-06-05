# semantic-release-bamboo

[![NPM version][npm-image]][npm-url]
[![NPM downloads][downloads-image]][downloads-url]

[![GitHub NodeJS][github-nodejs]][github-action-url]

[![Semantic Release][semantic-release-image]][semantic-release-url]

[![Visual Studio Code][vscode-image]][vscode-url]

[`semantic-release`](https://github.com/semantic-release/semantic-release) plugin for [Bamboo](https://www.atlassian.com/software/bamboo).

## Usage

```js
// package.json
{
    "release": {
        "verifyConditions": ["semantic-release-bamboo", "@semantic-release/npm"]
    }
}
```

## Contribute

```sh
# after fork
yarn install

# begin making changes
git checkout -b <branch>
yarn watch

# edit `webpack.config.dev.js` to exclude dependencies for the global build.

# after making change(s)
git commit -m "<commit message>"
git push

# create PR
```

## Npm Commands

There are a few useful commands you can use during development.

```sh
# Run tests (and lint) automatically whenever you save a file.
npm run watch

# Run tests with coverage stats (but won't fail you if coverage does not meet criteria)
npm run test

# Manually verify the project.
# This will be ran during 'npm preversion' so you normally don't need to run this yourself.
npm run verify

# Build the project.
# You normally don't need to do this.
npm run build

# Run tslint
# You normally don't need to do this as `npm run watch` and `npm version` will automatically run lint for you.
npm run lint
```

[npm-image]: https://img.shields.io/npm/v/semantic-release-bamboo.svg?style=flat
[npm-url]: https://npmjs.org/package/semantic-release-bamboo
[downloads-image]: https://img.shields.io/npm/dm/semantic-release-bamboo.svg?style=flat
[downloads-url]: https://npmjs.org/package/semantic-release-bamboo
[semantic-release-image]:https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[semantic-release-url]:https://github.com/semantic-release/semantic-release
[vscode-image]:https://img.shields.io/badge/vscode-ready-green.svg
[vscode-url]:https://code.visualstudio.com/
[github-action-url]: https://github.com/unional/semantic-release-bamboo/actions
[github-nodejs]: https://github.com/unional/semantic-release-bamboo/workflows/nodejs/badge.svg
