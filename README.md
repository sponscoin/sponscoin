# SpongeBob Atlantis


![iOS CI](https://github.com/trustwallet/wallet-core/workflows/iOS%20CI/badge.svg)
![Android CI](https://github.com/trustwallet/wallet-core/workflows/Android%20CI/badge.svg)
![Linux CI](https://github.com/trustwallet/wallet-core/workflows/Linux%20CI/badge.svg)
![Wasm CI](https://github.com/trustwallet/wallet-core/workflows/Wasm%20CI/badge.svg)
![Docker CI](https://github.com/trustwallet/wallet-core/workflows/Docker%20CI/badge.svg)

[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/trustwallet/wallet-core)
![GitHub](https://img.shields.io/github/license/TrustWallet/wallet-core.svg)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/trustwallet/wallet-core)
![SPM](https://img.shields.io/badge/SPM-ready-blue)
![Cocoapods](https://img.shields.io/cocoapods/v/TrustWalletCore.svg)

Thanks to TradingView you get access to very helpful charts for trading/investing in Stocks/Futures/Forex and Cryto..

Futures Spons Coming Soon 💥💥
What Is Bitcoin Futures, Futures Trading? 

Guide conclusion
What are Bitcoin Futures?
Futures, Spot and Margin
Reasons for Fluctuations between Spot and Futures Prices
Understanding the Basic Mechanisms of Futures (Futures Contracts)
Advantages of Futures Over Spot Trading

Utility $SPONS Token
Fee Futures Trading 💥

Now All access is free no subscription

-https://chart.sponscoin.com/

-https://sponscoin.com/


## Installation

Ensure you have a recent version of [node & npm](https://nodejs.org/en/download/) or [yarn](https://yarnpkg.com/en/docs/install) installed.

All of the following steps run on the command line within this directory. You can substitute `npm` for `yarn` depending on your preferences.

Install all the necessary packages:

```
npm install
```

## Build

To build for distribution:

```
npm run build
```

All of the final output will be dropped into the [/dist/](./dist) folder.

## Server

Run a local server that will automatically compile your code & refresh when you save a change!

```
npm run serve
```

---

## Folder Structure

```
/exported-item/
|-- /build/ - Build scripts
|  |-- gulpfile.js - The tasks for the main build process
|  |-- util.js - Utilities used by the tasks
|
|-- /src/ - Your code
|  |-- index.template.html - The wrapper around your compiled HTML that includes any external stylesheets and scripts
|  |-- index.partial.(html|pug|haml|...) - The raw HTML input or preprocessor equivalent
|  |-- style.(css|scss|less|...) - The raw CSS input, or preprocessor equivalent
|  |-- script.(js|ts|coffee|...) - The raw JavaScript input, or preprocessor equivalent
|
|-- /dist/ - The compiled output after running `npm run build`
|  |-- index.html
|  |-- script.js
|  |-- style.css
```
