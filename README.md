coova-chilli openwrt
====================

Customized coova-chilli package for OpenWRT.

Compile
-------

```
./scripts/feeds update -a
./scripts/feeds install -a
make -j1 V=s tools/install
make -j1 V=s toolchain/install
make -j1 V=s package/coova-chilli/compile
make -j1 V=s package/coova-chilli/install
```
