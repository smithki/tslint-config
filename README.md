# ⚙️ tslint-config

[![code style: airbnb](https://img.shields.io/badge/code%20style-airbnb-blue.svg?style=flat)](https://github.com/airbnb/javascript)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat)](https://github.com/prettier/prettier)

> A [TSLint config](https://palantir.github.io/tslint/usage/configuration/) with sensible rules for React, RxJS, Prettier, and more.

## 🔗 Installation

Install via `npm`:

```sh
npm install @smithkistyle/tslint-config --save-dev
```

Ensure you also have the required `peerDependencies` installed:

```sh
npm install tslint@^5.5.0 typescript@^2.5.0 prettier@^1.4.0 rxjs@^5.0.0 --save-dev
```

## 🛠️ Usage

In `tslint.json`:

```json
{
  "extends": "@smithkistyle/tslint-config"
}
```

## ⚡ Configuration

### Rules

- [`tslint`](https://palantir.github.io/tslint/rules/)
- [`tslint-react`](https://github.com/palantir/tslint-react)
- [`tslint-config-airbnb`](https://github.com/progre/tslint-config-airbnb)
  - [`tslint-eslint-rules`](https://github.com/buzinas/tslint-eslint-rules)
  - [`tslint-consistent-codestyle`](https://github.com/ajafff/tslint-consistent-codestyle)
  - [`tslint-microsoft-contrib`](https://github.com/Microsoft/tslint-microsoft-contrib)
- [`tslint-config-prettier`](https://github.com/alexjoverm/tslint-config-prettier)
- [`rxjs-tslint-rules`](https://github.com/cartant/rxjs-tslint-rules)

### Plugins

- [`tslint-plugin-prettier`](https://github.com/ikatyang/tslint-plugin-prettier)

## 🗜️ Versioning

```
+————— Major version is synchronized with TSLint's major version.
| +——— Minor version has BREAKING CHANGES or features.
| | +— Patch version has non-breaking changes.
| | |
x.x.x
```

## ⚖️ License

[MIT](./LICENSE)
