# DotSharpSpace prettier default configuration

```
Prettier is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.
```

The `@dotsharpspace/prettier-config` contains custom configuration for [prettier npmjs package](https://www.npmjs.com/package/prettier).

## Installation

Install prettier :

_NPM_

```
npm install --save-dev prettier
```

_YARN_

```
yarn add prettier --dev
```

Install `@dotsharpspace/prettier-config` :

_NPM_

```
npm install --save-dev @dotsharpspace/prettier-config
```

_YARN_

```
yarn add @dotsharpspace/prettier-config --dev
```

## Configuration

The configuration of the project can be done through package.json file or .prettierrc.json file

_package.json example :_

You need to add prettier configuration :

```
{
    "name": "some project name",
    "version": "current project version",
    "prettier": "@dotsharpspace/prettier-config",
    ...
}
```

_.prettierrc.json example :_

Or just add configuration in .prettierrc.json :

```
{
    "prettier": "@dotsharpspace/prettier-config"
}
```
