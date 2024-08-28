##

**_A repo where we will keep various versions of the cardano node and cli binaries built for ARM CPUs_** 🏴‍☠️🦾

BIG Thanks to SPO's [ZW3RK](https://twitter.com/zw3rkpool/) who provides the amazing Static Binaries, [SRN](https://armada-alliance.com/stake-pools/cc1b1c03798884c636703443a23b8d9e827d6c0417921600394198a0) who provides static/dynamic builds and maintains repo with [PIADA](https://armada-alliance.com/stake-pools/b8d8742c7b7b512468448429c776b3b0f824cef460db61aa1d24bc65) and our friend [Daniel](https://github.com/rekuenkdr) ₳🏴‍☠️🙏

## Cardano Node RTS Parameter Notebook

**This contains information about various run time optimizations Armada Alliance SPOs are using to improve their cardano-node's performance. For more information about GHC RTS parameters and running compiled programs read the Haskell document ["Using GHC"](https://downloads.haskell.org/~ghc/latest/docs/html/users_guide/runtime_control.html)**

**_[Armada Alliance Cardano RTS Notebook](https://docs.google.com/spreadsheets/d/1sw_fzqoubOEG6lMpWKVzCF8yISfY4YFAvnx_5E5T-1s/edit#gid=0)_**

Thank you to [PGWAD](https://armada-alliance.com/stake-pools/7e45a7e6ab3afcf99120e97aedf84e706e43d829ddc610ad667a85a3) for setting it up and all our members who have contributed 🙏🏴‍☠️

**Older binary versions are found within the respective subfolders

##

### Static build (Compatible for all arm based linux)
#### Mainnet/Preprod/Preview/SanchoNet

[9.1.0 with ghc-9.6.4 (Moritz)](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/9_1_0.tar.zst?raw=true)

```
wget -c https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/9_1_0.tar.zst?raw=true -O - | tar -I zstd -xv
```

[9.1.0 with ghc-9.6.6](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/cardano-9_1_0-aarch64-static-musl-ghc_966.tar.zst?raw=true)

```
wget -c https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/cardano-9_1_0-aarch64-static-musl-ghc_966.tar.zst?raw=true -O - | tar -I zstd -xv
```

##

### Additional static binaries

[cardano-wallet-v2024-07-07](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/cardano-wallet/cardano-wallet-v2024-07-07-aarch64-musl.tar.zst?raw=true)

```
wget -c https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/cardano-wallet/cardano-wallet-v2024-07-07-aarch64-musl.tar.zst?raw=true -O - | tar -I zstd -x
```

[mithril version 2430.0](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/mithril-binaries-version-2430_0.tar.zst?raw=true)

```
wget -c https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/mithril-binaries-version-2430_0.tar.zst?raw=true -O - | tar -I zstd -x
```

[db-analyser (ouroboros-consensus-cardano-0.18.0.0)](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/ouroboros-consensus-cardano-0.18.0.0/db-analyser.tar.zst?raw=true)

```
wget -c https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/ouroboros-consensus-cardano-0.18.0.0/db-analyser.tar.zst?raw=true -O - | tar -I zstd -x
```

[db-synthesizer (ouroboros-consensus-cardano-0.18.0.0)](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/ouroboros-consensus-cardano-0.18.0.0/db-synthesizer.tar.zst?raw=true)

```
wget -c https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/ouroboros-consensus-cardano-0.18.0.0/db-synthesizer.tar.zst?raw=true -O - | tar -I zstd -x
```

[db-truncater (ouroboros-consensus-cardano-0.18.0.0)](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/ouroboros-consensus-cardano-0.18.0.0/db-truncater.tar.zst?raw=true)

```
wget -c https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/ouroboros-consensus-cardano-0.18.0.0/db-truncater.tar.zst?raw=true -O - | tar -I zstd -x
```

[immdb-server (ouroboros-consensus-cardano-0.18.0.0)](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/ouroboros-consensus-cardano-0.18.0.0/immdb-server.tar.zst?raw=true)

```
wget -c https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/ouroboros-consensus-cardano-0.18.0.0/immdb-server.tar.zst?raw=true -O - | tar -I zstd -x
```

[db-immutaliser (ouroboros-consensus-cardano-0.18.0.0)](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/ouroboros-consensus-cardano-0.18.0.0/db-immutaliser.tar.zst?raw=true)

```
wget -c https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/ouroboros-consensus-cardano-0.18.0.0/db-immutaliser.tar.zst?raw=true -O - | tar -I zstd -x
```

##

### Official Cardano network environment configuration files can be found [here](https://book.world.dev.cardano.org/environments.html) (Mainnet/Testnets)

