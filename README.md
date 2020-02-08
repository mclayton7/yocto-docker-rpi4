# yocto-docker-rpi4
This is a repository for a baseline Raspberry Pi 4 (64bit) Yocto image with docker and wifi enabled.

## Building on a Linux Machine
1. Clone this repository
2. Run the following from root of the repository to set up the build environment: 
```console
user@server$ source layers/poky/oe-init-build-env build
```
3. To build an image, run the following command:
```console
user@server$ bitbake -k rpi-basic-image
```

## Sources
- https://medium.com/@shantanoodesai/run-docker-on-a-raspberry-pi-4-with-yocto-project-551d6b615c0b
