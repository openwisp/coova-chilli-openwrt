coova-chilli openwrt
====================

Coova-chilli package for OpenWRT with some minor tweaks.

Compile
-------

```
./scripts/feeds update -a
./scripts/feeds install -a
make -j1 V=s tools/install
make -j1 V=s toolchain/install
make -j1 V=s target/linux/compile
make -j1 V=s package/coova-chilli/compile
```
