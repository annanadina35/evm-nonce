# evm-nonce

> nonce · pending · stub

[![Go 1.22+](https://img.shields.io/badge/go-1.22+-00ADD8)](https://go.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()

EVM nonce manager shell — derive + stub pending count.

## Features

- ETH derivation path m/44'/60'/0'
- Local vault JSON with XOR wrap
- SHA-256 stand-in keys — no live RPC
- stdlib CLI via flag

## Prerequisites

- Go 1.22+
- Git

## Getting Started

```bash
git clone <repo-url>
cd evm-nonce
make build
./bin/evmnonce -help
```

## CLI Usage

```bash
make test
go run ./cmd/evmnonce -help
```

## Project Structure

```
cmd/evmnonce/main.go
internal/config/config.go
internal/crypto/keys.go
internal/wallet/wallet.go
internal/wallet/wallet_test.go
```

## Background

Relayers search evm-nonce, not ethereum-wallet.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.


---

## Topics

![evm](https://img.shields.io/badge/evm-111827?style=flat-square) ![nonce](https://img.shields.io/badge/nonce-111827?style=flat-square) ![evm-nonce](https://img.shields.io/badge/evm%20nonce-111827?style=flat-square) ![cryptocurrency](https://img.shields.io/badge/cryptocurrency-111827?style=flat-square) ![wallet](https://img.shields.io/badge/wallet-111827?style=flat-square) ![blockchain](https://img.shields.io/badge/blockchain-111827?style=flat-square) ![web3](https://img.shields.io/badge/web3-111827?style=flat-square) ![bitcoin](https://img.shields.io/badge/bitcoin-111827?style=flat-square)

`evm` `nonce` `evm-nonce` `cryptocurrency` `wallet` `blockchain` `web3` `bitcoin` `ethereum` `hd-wallet` `open-source` `golang` `go`

Search: evm-nonce · nonce · pending · stub · EVM nonce manager shell — derive + stub pending count.

---

<sub>EVM nonce manager shell — derive + stub pending count.</sub>
