##

**_A repo where we will keep various versions of the cardano node and cli binaries built for ARM CPUs_** 🏴‍☠️🦾

BIG Thanks to SPO's [ZW3RK](https://twitter.com/zw3rkpool/) who provides the amazing Static Binaries, [SRN](https://armada-alliance.com/stake-pools/cc1b1c03798884c636703443a23b8d9e827d6c0417921600394198a0) who provides dynamic builds and maintains repo with [PIADA](https://armada-alliance.com/stake-pools/b8d8742c7b7b512468448429c776b3b0f824cef460db61aa1d24bc65) and our friend [Daniel](https://github.com/rekuenkdr) ₳🏴‍☠️🙏

## Cardano Node RTS Parameter Notebook

**This contains information about various run time optimizations Armada Alliance SPOs are using to improve their cardano-node's performance. For more information about GHC RTS parameters and running compiled programs read the Haskell document ["Using GHC"](https://downloads.haskell.org/~ghc/latest/docs/html/users_guide/runtime_control.html)**

**_[Armada Alliance Cardano RTS Notebook](https://docs.google.com/spreadsheets/d/1sw_fzqoubOEG6lMpWKVzCF8yISfY4YFAvnx_5E5T-1s/edit#gid=0)_**

Thank you to [PGWAD](https://armada-alliance.com/stake-pools/7e45a7e6ab3afcf99120e97aedf84e706e43d829ddc610ad667a85a3) for setting it up and all our members who have contributed 🙏🏴‍☠️

##

### Static build (Compatible for all arm based linux. Recommended)

[8.1.2 with cardano-submit-api](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/8_1_2.zip?raw=true) (Mainnet)

```
wget -O 8_1_2.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/8_1_2.zip?raw=true
```

### Additional static binaries

[bech32 1.1.2](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/bech32/bech32-1_1_2.zip?raw=true)

```
wget -O bech32-1_1_2.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/bech32/bech32-1_1_2.zip?raw=true
```

[cardano-wallet-v2023-07-18](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/cardano-wallet/cardano-wallet-v2023-07-18-aarch64-musl.zip?raw=true)

```
wget -O cardano-wallet-v2023-07-18-aarch64-musl.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/cardano-wallet/cardano-wallet-v2023-07-18-aarch64-musl.zip?raw=true
```

##

### Dynamic build (Ubuntu 20.04 LTS and above. Requires [Libsodium, SECP256K1 and libssl.so.1.1](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/8.0.0/README.MD). Please rebuild libsodium using updated instruction for cardano-node/cli 8.0.0.)

[8.1.2](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/8.1.2/cardano-8_1_2-aarch64-ubuntu_2004.zip?raw=true) (Mainnet)

```
wget -O cardano-8_1_2-aarch64-ubuntu_2004.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/8.1.2/cardano-8_1_2-aarch64-ubuntu_2004.zip?raw=true
```

[8.1.2 with ghc-9.2.8](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/8.1.2/cardano-8_1_2-aarch64-ubuntu_2004-ghc_928.zip?raw=true) (Mainnet)

```
wget -O cardano-8_1_2-aarch64-ubuntu_2004-ghc_928.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/8.1.2/cardano-8_1_2-aarch64-ubuntu_2004-ghc_928.zip?raw=true
```

[8.2.0-pre](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/8.2.0/cardano-8_2_0_pre-aarch64-ubuntu_2004.zip?raw=true) (SanchoNet/Public preview test)

```
wget -O cardano-8_2_0_pre-aarch64-ubuntu_2004.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/8.2.0/cardano-8_2_0_pre-aarch64-ubuntu_2004.zip?raw=true
```

[8.2.1-pre](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/8.2.1/cardano-8_2_1_pre-aarch64-ubuntu_2004.zip?raw=true) (SanchoNet/Public preview test)

```
wget -O cardano-8_2_1_pre-aarch64-ubuntu_2004.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/8.2.1/cardano-8_2_1_pre-aarch64-ubuntu_2004.zip?raw=true
```

### Additional dynamic binaries

[cardano-submit-api-3.1.2](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.35.6/cardano-submit-api.zip?raw=true) (Built with cardano-node-1.35.6)

```
wget -O cardano-submit-api.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.35.6/cardano-submit-api.zip?raw=true
```

[cardano-wallet-v2023-07-18](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/cardano-wallet/cardano-wallet-v2023-07-18-aarch64-ubuntu_2004.zip?raw=true)

```
wget -O cardano-wallet-v2023-07-18-aarch64-ubuntu_2004.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/cardano-wallet/cardano-wallet-v2023-07-18-aarch64-ubuntu_2004.zip?raw=true
```

### Official Cardano network environment configuration files can be found [here](https://book.world.dev.cardano.org/environments.html) (Mainnet/Testnets)
