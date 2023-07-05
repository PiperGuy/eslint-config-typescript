# 💎 eslint-config

[![version][version-badge]][npm]
[![downloads][downloads-badge]][npm]

_My personal [eslint][eslint] configuration._

## 📦 Installation

This package is hosted on [npm][npm].

Install the configuration and it's peer dependencies as a development dependency.

```
npx install-peerdeps --dev @piperguy/eslint-config
```

> This installs peer dependencies automatically using [npx][npx] and [install-peerdeps][peer] so you don't have to!

## 🥑 Usage

Create an `.eslintrc` file in the root of your project and tell it to extend the configuration.

```
{
    extends: "@piperguy/eslint-config"
}
```

> You can add more ESLint configuration options in this file if you want.

## ❔ Questions

🐛 report bugs by filing [issues][issues]  
📢 provide feedback with [issues][issues] or on [twitter][twitter]

[version-badge]: https://img.shields.io/npm/v/@piperguy/eslint-config.svg?color=FB3B49&style=flat-square
[downloads-badge]: https://img.shields.io/npm/dt/@piperguy/eslint-config?style=flat-square
[npm]: https://www.npmjs.com/package/@piperguy/eslint-config
[eslint]: https://eslint.org
[npx]: https://www.npmjs.com/package/npx
[peer]: https://www.npmjs.com/package/install-peerdeps
[issues]: https://github.com/piperguy/eslint-config/issues
[twitter]: https://twitter.com/_PiperGuy_
