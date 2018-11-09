# Ecosystem

There are many auxiliary pieces of software that greatly enhance a blockchain's functionality. The expectation will be for the community to develop these tools as they become necessary.

The following are suggestions; additions to this list are welcome.

Each listed repository will be forked into https://github.com/bsha3 for development.

**Join the conversation:** https://discord.gg/tjzc3AZ 

## To-Do

### High Priority
- [x] Full Node (Wallet + P2P + RPC) - [bsha3/bsha3](https://github.com/bsha3/bsha3)
- [x] CPU Miner - Part of full node; use `setgenerate true <num_cores>`, alternatively [cpuminer-multi](https://github.com/bsha3/cpuminer-multi)
- [ ] GPU Miner - [ravencoin/miner](https://github.com/bsha3/miner), [tpruvot/ccminer](https://github.com/bsha3/ccminer)
- [ ] ASIC Miner
- [x] BSHA3 Logo - [bsha3/design-assets](https://github.com/bsha3/design-assets)
- [x] BSHA3 Website - [bsha3/bsha3.github.io](https://github.com/bsha3/bsha3.github.io)
- [x] SLIP-44 - `0`
- [x] SLIP-173 - `bsha3`
- [ ] Travis CI

### Medium Priority

- [x] SPV Wallet Server - [kyuupichan/electrumx](https://github.com/kyuupichan/electrumx)
- [x] Block Explorer - [janoside/btc-rpc-explorer](https://github.com/bsha3/bsha3-rpc-explorer)
- [ ] JS - [bitcoinjs/bitcoinjs-lib](https://github.com/bsha3/bitcoinjs-lib)
- [ ] Paper Wallet - [iancoleman/bip39](https://github.com/iancoleman/bip39)
- [ ] [dgarage/NBitcoin](https://github.com/dgarage/nbitcoin), [dgarage/NBXplorer](https://github.com/dgarage/nbxplorer)
- [ ] BSHA3 Docs - Doxygen
- [ ] [Gitian Build](https://github.com/bitcoin-core/gitian.sigs)
- [ ] Testnet & Regtest Genesis - [bsha3/bsha3](https://github.com/bsha3/bsha3)

### Low Priority

- [ ] [btcpayserver/BTCPayServer](https://github.com/btcpayserver/btcpayserver), [btcpayserver/BTCPayServer-docker](https://github.com/btcpayserver/btcpayserver-docker)
- [ ] SPV (Lite) Wallet - [spesmilo/electrum](https://github.com/spesmilo/electrum)
- [ ] Wasabi Wallet - [zksnacks/walletwasabi](https://github.com/zksnacks/walletwasabi)

- [ ] Mempool & History - [jhoenicke/mempool](https://github.com/bsha3/mempool)

### Any Time

- [ ] Trezor, Ledger, KeepKey

- [ ] Icon Pack - [atomiclabs/cryptocurrency-icons](https://github.com/atomiclabs/cryptocurrency-icons)

- [ ] SMS, Telegram, Discord, Twitch, Twitter Send & Tip Bots

**Note - Addresses aren't compatible with Bitcoin wallet code where normally a prefix version byte is just changed; full replacement of SHA256 -> SHA3-256 is necessary.**
