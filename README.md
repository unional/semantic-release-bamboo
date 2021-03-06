# semantic-release-bamboo

[![NPM version][npm-image]][npm-url]
[![NPM downloads][downloads-image]][downloads-url]
[![Build status][travis-image]][travis-url]
[![Coverage Status][coveralls-image]][coveralls-url]
![badge-size-es5-url]

[![Greenkeeper][greenkeeper-image]][greenkeeper-url]
[![Semantic Release][semantic-release-image]][semantic-release-url]

[![Visual Studio Code][vscode-image]][vscode-url]
[![Wallaby.js][wallaby-image]][wallaby-url]

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
npm install

# begin making changes
git checkout -b <branch>
npm run watch

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
[travis-image]: https://img.shields.io/travis/unional/semantic-release-bamboo/master.svg?style=flat
[travis-url]: https://travis-ci.org/unional/semantic-release-bamboo?branch=master
[coveralls-image]: https://coveralls.io/repos/github/unional/semantic-release-bamboo/badge.svg
[coveralls-url]: https://coveralls.io/github/unional/semantic-release-bamboo
[badge-size-es5-url]: http://img.badgesize.io/unional/semantic-release-bamboo/master/dist/semantic-release-bamboo.es5.js.svg?label=es5_size
[greenkeeper-image]:https://badges.greenkeeper.io/unional/semantic-release-bamboo.svg
[greenkeeper-url]:https://greenkeeper.io/
[semantic-release-image]:https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[semantic-release-url]:https://github.com/semantic-release/semantic-release
[wallaby-image]:https://img.shields.io/badge/wallaby.js-configured-green.svg
[wallaby-url]:https://wallabyjs.com
[vscode-image]:https://img.shields.io/badge/vscode-ready-green.svg
[vscode-url]:https://code.visualstudio.com/
