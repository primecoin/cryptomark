# CryptoMark 2.0 TwinSeeker

Fun app to measure CPU performance and play with the innerworkings of Crypto!

### Introduction

CryptoMark 2.0 is redesigned with fun and education in mind, together with a new engine supporting mining of testnet primecoins!

CryptoMark was first introduced in 2020 with novel concepts. Benchmark is based on proof-of-work of cryptocurrencies represented by Primecoin and Bitcoin. Two types of benchmark ratings are provided, one linear, one logarithmic. The linear ratings which provide more accurate comparisons of CPU performance, is measured in twin/minute for Primecoin and hash/second for Bitcoin. The logarithmic rating is known as the `diffeq`, with a graphic representation called `diffeometer`. Diffeq rating is used to provide a sense of scale of the given proof-of-work system.

### FAQ

* ***How to mine testnet primecoins?*** To enable mining of testnet primecoins, a Primecoin testnet address must be provided to cryptomark. First fully close cryptomark app. In [Gemmer](https://github.com/primecoin/gemmer) (0.3.3+ needed), switch to Primecoin testnet view via typing `testnet primecoin` into amount input box. Hold the QRcode for a second to share the testnet address with other apps, then in the Android popup choose cryptomark app to share with. Cryptomark app would start upon sharing and display the address on the upper right corner, with the mining cart button now enabled.

* ***What does the rating above the meter mean?*** The rating is known as `diffeq`. It is an estimate of the stabilized network difficulty assuming your miner is the only miner in the proof-of-work network. The number to the right of diffeometer is the current Primecoin network difficulty. Diffeq rating provides a sense of logarithmic scale to the amount of computation resource.

* ***What are the four words on the upper left corner?*** These are the names of the mining pools providing service to CryptoMark 2. These pools are `solo pools`, meaning that the pool will distribute coins to your wallet in real time upon finding of block as if you are solo mining to a node. Unlike actual solo mining, the coins are not in coinbase so are not subject to maturity restrictions. When cryptomark is mining, it chooses one of the pools to work with and also does failover as needed.

### Feature Implemented So Far

* Twin miner engine
* Service allowing Android phones to work as miners for Primecoin testnet
* Solo pool infrastructures supporting Primecoin testnet mining
* Work with [Gemmer](https://github.com/primecoin/gemmer) together to support Primecoin testnet mining
* Primecoin benchmark

### Tentative Milestones

* Q1 2021 - Mining on Primecoin testnet, Primecoin mining benchmark
* Q2 2021 - Bitcoin mining benchmark

### Community

Questions? Please feel at ease and have fun at the [Primecoin Discord](https://discord.gg/g9mctgx) :)
