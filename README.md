# Awesome Fedimint [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

> The curated list of awesome things related to Fedimint.

# Learning Resources
* [fedimint.org](https://fedimint.org)

# Wallets
* [`fedimint-cli`](https://github.com/fedimint/fedimint/): command line wallet included in Fedimint that is mainly used for testing and debugging.
* [Fedi](https://www.fedi.xyz/): proprietary mobile app and PWA Fedimint wallet
* [Harbor](https://github.com/MutinyWallet/harbor): open source Fedimint wallet (very early, only supports signet)
* [Vipr-Wallet](https://github.com/ngutech21/vipr-wallet): open source PWA Fedimint wallet (beta stage, expect incomplete features and potential bugs)
* [Ecash App](https://ecash.love): open source Fedimint wallet under the Fedimint organization

#  Public Federations Lists
* [Fedimint Observer](https://observer.fedimint.org/) lists public Fedimints and monitors their health
* [bitcoinmints.com](https://bitcoinmints.com/?show=fedimint) lists public Cashu and Fedimint mints

# Client Libraries
* [`fedimint-sdk`](https://github.com/fedimint/fedimint-sdk) ([docs](https://sdk.fedimint.org)): SDK for building fedimint clients on the web, mobile, …
* [`fedimint-client`](https://github.com/fedimint/fedimint): official Rust client library, requires client modules to become useful (included in main repo: `wallet`, `mint`, `ln`)

# Modules
* [Prediction Markets](https://github.com/toyota-corolla0/fedimint-prediction-markets)
* [ROASTR](https://github.com/m1sterc001guy/roastr): Module for collaboratively signing Nostr events using [ROAST](https://medium.com/blockstream/roast-robust-asynchronous-schnorr-threshold-signatures-ddda55a07d1b).

# Misc
* [Fedimint-Charts](https://github.com/ngutech21/fedimint-charts): Helm Charts for deploying Fedimint on Kubernetes
* [Fedimint Observer](https://github.com/elsirion/fedimint-observer): Data analysis tool for Fedimint
* [Paper Ecash Tool](https://github.com/elsirion/paper-ecash): Tool to create paper ecash notes using Fedimint
* [Ecash Candy Dispenser](https://github.com/elsirion/candypi): Candy dispenser using Fedimint to receive LN payments

# Historic/Discontinued
## Wallets
* [Fluttermint](https://github.com/futurepaul/fluttermint): discontinued, but honourable mention since it was the first graphical Fedimint client
* [Webimint](https://github.com/elsirion/webimint-rs/): open source Fedimint PWA wallet completely written in rust (very hacky, don't rely on it, it's a weekend project)
* [Mutiny Wallet](https://mutinywallet.com/): open source Bitcoin, Lightning and Fedimint PWA wallet

## Client Libraries
* [`fedimint-http-client`](https://github.com/Kodylow/fedimint-http-client): wrapper around `fedimint-client` with its default modules exposing a HTTP API for easier cross-language consumption
* [`fedimint-sdk-ts`](https://github.com/Kodylow/fedimint-sdk-ts): Typescript Fedimint client library using `fedimint-http-client` under the hood
* [`fedimint-sdk-py`](https://github.com/Kodylow/fedimint-sdk-ts): Python Fedimint client library using `fedimint-http-client` under the hood
* [`fedimint-sdk-go`](https://github.com/Kodylow/fedimint-sdk-ts): Go Fedimint client library using `fedimint-http-client` under the hood

# Misc
* [Hermes](https://github.com/Kodylow/hermes): lightning address server for Fedimint

