# `web3-react-wallet`

This is a fork of the web3-react project with wallet integrated and only contains the following connectors:

- Ledger Connector

- Injected Connector

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

 | Packages                              | `@latest` Version                                                                                                                                                         | Size                                                                                                                                                                                 | Description                                                                         |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------- |
| 🏠 **Core**                           |
| `@web3-react/core`                    | [![npm version](https://img.shields.io/npm/v/@web3-react/core/latest.svg)](https://www.npmjs.com/package/@web3-react/core/v/latest)                                       | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/core/latest.svg)](https://bundlephobia.com/result?p=@web3-react/core@latest)                                       | [React](https://reactjs.org/) Interface                                             |
| 🔌 **Connectors**                     |
| _Browser Extension/dApp Browser_      |
| `@web3-react/injected-connector`      | [![npm version](https://img.shields.io/npm/v/@web3-react/injected-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/injected-connector/v/latest)           | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/injected-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/injected-connector@latest)           | [Injected](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1193.md) Connector |
| _Remote API_                          |
| `@web3-react/network-connector`       | [![npm version](https://img.shields.io/npm/v/@web3-react/network-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/network-connector/v/latest)             | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/network-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/network-connector@latest)             | [RPC](https://github.com/ethereum/wiki/wiki/JSON-RPC) Connector                     |
| _Hardware_                            |
| `@web3-react/ledger-connector`        | [![npm version](https://img.shields.io/npm/v/@web3-react/ledger-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/ledger-connector/v/latest)               | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/ledger-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/ledger-connector@latest)               | [Ledger](https://www.ledger.com/) Connector                                         |
| 🐉 **Low-Level**                      |
| `@web3-react-wallet/abstract-connector`      | [![npm version](https://img.shields.io/npm/v/@web3-react/abstract-connector/latest.svg)](https://www.npmjs.com/package/@web3-react/abstract-connector/v/latest)           | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/abstract-connector/latest.svg)](https://bundlephobia.com/result?p=@web3-react/abstract-connector@latest)           | Shared Connector Class                                                              |
| `@web3-react-wallet/types`                   | [![npm version](https://img.shields.io/npm/v/@web3-react/types/latest.svg)](https://www.npmjs.com/package/@web3-react/types/v/latest)                                     | [![minzip](https://img.shields.io/bundlephobia/minzip/@web3-react/types/latest.svg)](https://bundlephobia.com/result?p=@web3-react/types@latest)                                     | Shared [TypeScript](https://www.typescriptlang.org/) Types                          |

## Local Development

- Clone repo\
  `git clone https://github.com/EdsonAlcala/web3-react-connectors.git`

- Install top-level dependencies\
  `yarn`

- Install sub-dependencies\
  `yarn bootstrap`

- Build and watch for changes\
  `yarn start`
