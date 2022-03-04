# Build notes

Cardano 1.34.1 binaries built via Ubuntu 20.04 (glibc-2.31)

Contains network config and alonzo genesis files for mainnet and testnet.

## Requires libsodium

### Instructions to install libsodium

Create a working directory for your builds:

```
mkdir -p ~/src

cd ~/src
```

Download and install libsodium:

```
git clone https://github.com/input-output-hk/libsodium

cd libsodium

git checkout 66f017f1

./autogen.sh

./configure

make

sudo make install
```

Add the following to your .bashrc file and source it:

```
echo "export LD_LIBRARY_PATH="/usr/local/lib:$LD_LIBRARY_PATH"" >> ~/.bashrc

echo "export PKG_CONFIG_PATH="/usr/local/lib/pkgconfig:$PKG_CONFIG_PATH"" >> ~/.bashrc

source ~/.bashrc
```

For those who run cardano-node as a systemd service, run the following:

```
sudo ldconfig
```

This ensures the system is aware of libsodium (not just at the user level).
