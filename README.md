# CryptoMark TwinSeeker

Fun app to measure CPU performance and play with the innerworkings of Crypto!

### Introduction

CryptoMark 2 is redesigned from the ground up with fun and education in mind, together with a new engine supporting mining of testnet primecoins!

CryptoMark was first introduced in 2020 with novel concepts. Benchmark is based on proof-of-work of cryptocurrencies represented by Primecoin and Bitcoin. Two types of benchmark ratings are provided, one linear, one logarithmic. The linear ratings which provide more accurate comparisons of CPU performance, is measured in twin/minute for Primecoin and hash/second for Bitcoin. The logarithmic rating is known as the `diffeq`, with a graphic representation called `diffeometer`. Diffeq rating is used to provide a sense of scale of the given proof-of-work system.

### FAQ

* ***How to mine testnet primecoins?*** To enable mining of testnet primecoins, a Primecoin testnet address must be provided to cryptomark. First fully close cryptomark app. In [Gemmer](https://github.com/primecoin/gemmer) (0.3.3+ needed), switch to Primecoin testnet view via typing `testnet primecoin` into amount input box. Hold the QRcode for a second to share the testnet address with other apps, then in the Android popup choose cryptomark app to share with. Cryptomark app would start upon sharing and display the address on the upper right corner, with the mining cart button now enabled.

* ***How to run bitcoin benchmark?*** Tap CPU button to switch from mining mode, or toggle between Primecoin benchmark, Bitcoin benchmark and idle modes. The coin symbol on the diffeometer dial tells which coin's benchmark is currently running.

* ***What does the rating above the meter mean?*** The rating is known as `diffeq`. It is an estimate of the stabilized network difficulty assuming your miner is the only miner in the proof-of-work network. The number to the right of diffeometer is the current Primecoin network difficulty. Diffeq rating provides a sense of logarithmic scale to the amount of computation resource.

* ***What are the four words on the upper left corner?*** These are the names of the mining pools providing service to CryptoMark 2. These pools are `solo pools`, meaning that the pool will distribute coins to your wallet in real time upon finding of block as if you are solo mining to a node. The solo pools support both getwork API and getblocktemplate API. When using getwork API, coins are not distributed via coinbase so are not subject to maturity restrictions. When cryptomark is mining, it chooses one of the pools to work with and also performs auto-failover as needed.

### Feature Implemented So Far

* Twin miner engine
* Foreground service allowing Android phones to work as miners for Primecoin testnet
* Solo pool infrastructures supporting Primecoin testnet mining
* Work with [Gemmer](https://github.com/primecoin/gemmer) together to support Primecoin testnet mining
* Primecoin benchmark
* Bitcoin benchmark

### Tentative Milestones

* Q1 2021 - Mining on Primecoin testnet, Primecoin mining benchmark, Bitcoin mining benchmark, Foreground service
* Q2 2021 - Support getblocktemplate/submitblock API
* Q4 2021 - Experimental service restart
* Q2 2023 - Embedded cryptomark

### Community

Questions? Please feel at ease and have fun at the [Primecoin Discord](https://discord.gg/g9mctgx) :)
