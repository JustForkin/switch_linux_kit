### Switch Linux Kit
Build Linux for Nintendo Switch from Sourcecode using [Docker Toolchain](https://hub.docker.com/r/nold360/switch_linux_toolchain/)

### Cloning
```
 git clone https://github.com/Nold360/switch_linux_kit
 cd switch_linux_kit
 git submodule update --init
```

### Compiling
***Note:*** You'll still need to get `coreboot/tegra_mtc.bin` on your own.
```
 docker run -ti --rm nold360/switch_linux_toolchain bash build.sh
```


