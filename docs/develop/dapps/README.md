# Overview


## Prerequisites

Here you can links to the most important resources for you to get started with TON:

- [Wallets](https://ton.org/wallets) — a list of popular wallets for TON.
- [Explorers](https://ton.app/explorers) — to read transactions in the blockchain.
- [Testnet](/develop/smart-contracts/environment/testnet) — testnet and how to use it.

## Learning by Examples

In case you are web or bot developer, you could find useful these repositories:

### Examples

* [TonCenter API Examples](https://github.com/toncenter/examples) (JavaScript, with comments)
* [Payment Channels Example](https://github.com/toncenter/payment-channels-example) (JavaScript, with comments)
* [TON Bridge front-end](https://github.com/ton-blockchain/bridge) (Vue.js, no comments)
* [Web Wallet source code](https://github.com/toncenter/ton-wallet) (JavaScript, no comments)

## SDK to interact with TON

Here is a list of modern SDKs that continuously supported and improved:

### JavaScript SDK

* [tonweb](https://github.com/toncenter/tonweb) — JavaScript API for TON blockchain.
* [ton-js](https://github.com/tonwhales/ton) — Cross-platform client for TON blockchain.
* [@tegro/ton3-client](https://github.com/TegroTON/ton3-client) — ton3 client

### Python SDK

* [psylopunk/pytonlib](https://github.com/psylopunk/pytonlib) — Python SDK.
* [toncenter/pytonlib](https://github.com/toncenter/pytonlib) — Python SDK.
* [tonfactory/tonsdk](https://github.com/tonfactory/tonsdk) — Analogue of the tonweb js library.

### Other SDK

* [tonutils-go](https://github.com/xssnick/tonutils-go) — Go utils for TON blockchain.
* [ton-kotlin](https://github.com/andreypfau/ton-kotlin) — Kotlin SDK for TON blockchain.

## Telegram Web Apps (TWA)

One of the first repositories made by community:
* [ton-defi-org/tonstarter-twa](https://github.com/ton-defi-org/tonstarter-twa)

## Authorization & TON Connect

In case you want to add login to your website using wallet exists these approaches:

* [TON Connect](https://github.com/tonkeeper/ton-connect/blob/main/TonConnectSpecification.md) by Tonkeeper
  * [Authorization](https://tonapi.io/docs#authorization) by tonapi.io (using TON Connect)
* [Tonhub Extensions](https://developers.tonhub.com/docs/apps) by Tonhub


## TonLib SDK

:::caution deprecated
These technologies contains outdated, very low-level stack, so please use it if any other SDK are not working for you. It will save your time a lot.
:::

TonLib was a one of the first libraries for working with TON blockchain.

* [C++ TonLib](https://github.com/ton-blockchain/ton/tree/master/example/cpp)
* [Python TonLib wrapper](https://github.com/toncenter/pytonlib)
* [Golang TonLib wrapper](https://github.com/ton-blockchain/tonlib-go)
* [Java TonLib wrapper (JNI)](https://github.com/ton-blockchain/tonlib-java)
* [tonlib-xcframework](https://github.com/labraburn/tonlib-xcframework) - builder for Apple that generates .xcramework for all architectures
* [labraburn/SwiftyTON](https://github.com/labraburn/SwiftyTON) - native Swift wrapper for tonlib with async/await
* [labraburn/node-tonlib](https://github.com/labraburn/node-tonlib) - C++ addon for NodeJS to work with tonlibjson

#### Usage examples

* [Desktop standard wallet (C++ and Qt)](https://github.com/ton-blockchain/wallet-desktop)
* [Android standard wallet (Java)](https://github.com/ton-blockchain/wallet-android)
* [iOS standard wallet (Swift)](https://github.com/ton-blockchain/wallet-ios)
* [TonLib CLI (C++)](https://github.com/ton-blockchain/ton/blob/master/tonlib/tonlib/tonlib-cli.cpp)



## APIs

* [TonCenter](https://toncenter.com/) — Fast and reliable HTTP API for The Open Network
* [TonApi.io](https://tonapi.io/) — API that allows to work with indexed blockchain information.

### End-points  

* [GetBlock Nodes](https://getblock.io/nodes/ton/) — connect and test your dApp to TON using GetBlocks Nodes.