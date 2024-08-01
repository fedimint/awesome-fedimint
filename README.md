# Awesome Fedimint [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

> The curated list of awesome things related to Fedimint.

# Learning Resources
* [fedimint.org](https://fedimint.org)

# Wallets
* [`fedimint-cli`](https://github.com/fedimint/fedimint/): command line wallet included in Fedimint that is mainly used for testing and debugging.
* [Fedi](https://www.fedi.xyz/): proprietary mobile app and PWA Fedimint wallet
* [Webimint](https://github.com/elsirion/webimint-rs/): open source Fedimint PWA wallet completely written in rust (very hacky, don't rely on it, it's a weekend project)
* [Mutiny Wallet](https://mutinywallet.com/): open source Bitcoin, Lightning and Fedimint PWA wallet
* [Harbor](https://github.com/MutinyWallet/harbor): open source Fedimint wallet (very early, only supports signet)

#  Public Federations (not an endorsement)
This is not a heavily curated list, use your own judgement. We reserve the right to remove Federations at our discretion if there is evidence of unethical behavior.

## Mainnet
* Bitcoin Principles
```
fed11qgqzygrhwden5te0v9cxjtnzd96xxmmfdec8y6twvd5hqmr9wvhxuet59upqzg9jzp5vsn6mzt9ylhun70jy85aa0sn7sepdp4fw5tjdeehah0hfmufvlqem
```

* freedom one
```
fed11qgqzz8mhwden5te0vejkg6tdd9h8gepwvchxjmm5w4hxgunp9e3k7mf0qyqjpj2ykt73ullqfj58lxjh67y5ed53zm8vvfjvk5h65ufz3a8v2nxky9wuce
```

* [Odin Federation](https://odinfederation.xyz)
```
fed11qgqzutrhwden5te0vejkg6tdd9h8gepwvejkg6tdd9h8gtn0v35kuen9v3jhyct5d9hkutnc09az7qqpyp938g2xae96wv4jhzg55u4q5tjcw037jsk6948walv95hlyrunm5tyfcdy
```

* E-Cash Club
```
fed11qgqpv9rhwden5te0vekjucm5wf3zu6t09amhxtcpqys2ajnveq8lc5ct6t25kztgrahdhxjptsmzujhjlc74upqnwqr05ggd78dhm
```

* [bitcoinmints.com](https://bitcoinmints.com/?show=fedimint) lists public Cashu and Fedimint mints

## Testnet
* [Fedi Alpha (Mutinynet)](https://alpha.fedi.xyz/)
```
fed11qgqrgvnhwden5te0v9k8q6rp9ekh2arfdeukuet595cr2ttpd3jhq6rzve6zuer9wchxvetyd938gcewvdhk6tcqqysptkuvknc7erjgf4em3zfh90kffqf9srujn6q53d6r056e4apze5cw27h75
```

# Client Libraries
* [`fedimint-client`](https://github.com/fedimint/fedimint): official Rust client library, requires client modules to become useful (included in main repo: `wallet`, `mint`, `ln`)
* [`fedimint-http-client`](https://github.com/Kodylow/fedimint-http-client): wrapper around `fedimint-client` with its default modules exposing a HTTP API for easier cross-language consumption
* [`fedimint-sdk-ts`](https://github.com/Kodylow/fedimint-sdk-ts): Typescript Fedimint client library using `fedimint-http-client` under the hood
* [`fedimint-sdk-py`](https://github.com/Kodylow/fedimint-sdk-ts): Python Fedimint client library using `fedimint-http-client` under the hood
* [`fedimint-sdk-go`](https://github.com/Kodylow/fedimint-sdk-ts): Go Fedimint client library using `fedimint-http-client` under the hood

# Modules
* [Prediction Markets](https://github.com/toyota-corolla0/fedimint-prediction-markets)
* [ROASTR](https://github.com/m1sterc001guy/roastr): Module for collaboratively signing Nostr events using [ROAST](https://medium.com/blockstream/roast-robust-asynchronous-schnorr-threshold-signatures-ddda55a07d1b).

# Misc
* [Hermes](https://github.com/Kodylow/hermes): lightning address server for Fedimint

# Historic/Discontinued
* [Fluttermint](https://github.com/futurepaul/fluttermint): discontinued, but honourable mention since it was the first graphical Fedimint client
