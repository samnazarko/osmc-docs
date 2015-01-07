# Build environment

To build parts of OSMC you will need to be running a 64-bit version of [Debian Jessie](https://www.debian.org/releases/jessie/). 50GB of hard disk space and 4GB of memory are recommended. You will also need an Internet connection as OSMC obtains sources from the network during the build process.
> You can check you're running a 64-bit version of Debian with this command:
```shell
uname -m
```
> If you're on a 64-bit system, this should return:
```shell
x86_x64
```
<aside class="notice">
Although most recent Ubuntu releases will be able to compile most of OSMC, we recommend you stick with the Debian Jessie release. This is particularly important when building for ARM platforms: older Debian based distributions do not have recent versions of the QEMU userspace emulation packages.
</aside>

You will be able to build almost all of OSMC with a Debian installation with the exception of some of the host installers. These will need to be built on Windows, Mac or other Linux distributions respectively.