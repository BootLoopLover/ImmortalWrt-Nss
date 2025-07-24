# HOW TO BUILD

```
git clone https://github.com/BootLoopLover/ImmortalWrt-Nss.git
```

```
./scripts/feeds update -a
./scripts/feeds install -a
```

```
cp nss-setup/config-nss.seed .config
```

```
make menuconfig
```

# TICK ALL THE PACKAGE YOU NEED

```
make -j5 V=s
```


# Based On ImmortalWrt Official firmware v24.10.2
# Add On Nss Package Firmware By Qosmio
