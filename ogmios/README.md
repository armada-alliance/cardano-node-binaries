This is ogmios compiled for ARM
Details here https://ogmios.dev/

If you want to use this binary then you may also have to compile the following

```
git clone https://github.com/bitcoin-core/secp256k1.git
cd secp256k1
git reset --hard ac83be33d0956faf6b7f61a60ab524ef7d6a473a
./autogen.sh
./configure --prefix=/usr --enable-module-schnorrsig --enable-experimental
make
make check
sudo make install
```

To run ogmios, 
1) Allow port in for ogmios
2) Your cardano-node should be started and should be in synced state
3) Start ogmios and connect with browser <your relay ip>:1337

```
sudo ufw allow 1337

ogmios --host 0.0.0.0 --node-socket $NODE_HOME/db/socket --node-config ${NODE_CONFIG}-config.json

```



