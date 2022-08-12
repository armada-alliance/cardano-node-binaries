##
***A repo where we will keep various versions of the cardano node and cli binaries built for ARM CPUs*** 🏴‍☠️🦾

BIG Thanks to SPO's [ZW3RK](https://twitter.com/zw3rkpool/) who provides the amazing Static Binaries, [SRN](https://armada-alliance.com/stake-pools/cc1b1c03798884c636703443a23b8d9e827d6c0417921600394198a0) who provides dynamic builds and maintains repo with [PIADA](https://armada-alliance.com/stake-pools/b8d8742c7b7b512468448429c776b3b0f824cef460db61aa1d24bc65) and our friend [Daniel](https://github.com/rekuenkdr) ₳🏴‍☠️🙏
## Cardano Node RTS Parameter Notebook

**This contains information about various run time optimizations Armada Alliance SPOs are using to improve their cardano-node's performance. For more information about GHC RTS parameters and running compiled programs read the Haskell document ["Using GHC"](https://downloads.haskell.org/~ghc/latest/docs/html/users_guide/runtime_control.html)**

***[Armada Alliance Cardano RTS Notebook](https://docs.google.com/spreadsheets/d/1sw_fzqoubOEG6lMpWKVzCF8yISfY4YFAvnx_5E5T-1s/edit#gid=0)***

Thank you to [PGWAD](https://armada-alliance.com/stake-pools/7e45a7e6ab3afcf99120e97aedf84e706e43d829ddc610ad667a85a3) for setting it up and all our members who have contributed 🙏🏴‍☠️

##
### Static build (Compatible for all arm based linux. Recommended)
[1.34.1 with cardano-submit-api](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/1_34_1.zip?raw=true) (Mainnet)

```
wget -O 1_34_1.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/1_34_1.zip?raw=true
```

[1.35.0 with cardano-submit-api](https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/1_35_0.zip?raw=true) (Deprecated - Do Not Use)

```
wget -O 1_35_0.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/static-binaries/1_35_0.zip?raw=true
```

##
### Dynamic build (Ubuntu 20.04 and above. Requires [Libsodium and SECP256K1](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.35.0/README.MD).)
[1.35.3](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.35.3/cardano-1_35_3-aarch64-ubuntu_2004.zip?raw=true) (Mainnet)

```
wget -O cardano-1_35_3-aarch64-ubuntu_2004.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.35.3/cardano-1_35_3-aarch64-ubuntu_2004.zip?raw=true
```

[1.35.2](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.35.2/cardano-1_35_2-aarch64-ubuntu_2004.zip?raw=true) (Public Testnet)

```
wget -O cardano-1_35_2-aarch64-ubuntu_2004.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.35.2/cardano-1_35_2-aarch64-ubuntu_2004.zip?raw=true
```

[1.35.3-rc1](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.35.3-rc1/cardano-1_35_3_rc1-aarch64-ubuntu_2004.zip?raw=true) (Vasil-dev Testnet)

```
wget -O cardano-1_35_3_rc1-aarch64-ubuntu_2004.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.35.3-rc1/cardano-1_35_3_rc1-aarch64-ubuntu_2004.zip?raw=true
```

### Additional dynamic binaries

[cardano-submit-api-3.1.2](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.34.1/cardano-submit-api.zip?raw=true) (Built with cardano-node-1.34.1)

```
wget -O cardano-submit-api.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.34.1/cardano-submit-api.zip?raw=true
```

[cardano-node-chairman/cardano-topology/cardano-testnet](https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.35.2/cardano-additional-binaries-1_35_2-aarch64-ubuntu_2004.zip?raw=true) (Built with cardano-node-1.35.2)

```
wget -O cardano-additional-binaries-1_35_2-aarch64-ubuntu_2004.zip https://github.com/armada-alliance/cardano-node-binaries/blob/main/dynamic-binaries/1.35.2/cardano-additional-binaries-1_35_2-aarch64-ubuntu_2004.zip?raw=true
```

##
### Current Configuration files for the Cardano Blockchain Protocol

[Cardano Configuration Files](https://hydra.iohk.io/build/7654130/download/1/index.html)


##
### Latest Unnoffical Mainnet/Testnet Configuration Files
[Latest Configuration Files](https://hydra.iohk.io/job/Cardano/iohk-nix/cardano-deployment/latest-finished/download/1/index.html)
