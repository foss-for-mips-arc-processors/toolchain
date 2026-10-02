# ARC GNU Toolchain

This is the main Git repository for the ARC GNU toolchain. It contains
documentation & various supplementary materials required for development,
verification & releasing of pre-built toolchain artifacts.

## Documentation

There are several documentation sites for ARC GNU toolchain:

1. [GNU toolchain documentation site](https://foss-for-mips-arc-processors.github.io/documentation/latest) - the documentation site for all ARC targets.
2. [Old GNU toolchain documentation site](https://foss-for-mips-arc-processors.github.io/toolchain/) - the documentation site for ARC Classic targets
for release `arc-2023.03` and earlier.

## Building ARC GNU toolchains

Follow [Building ARC Toolchains](https://foss-for-mips-arc-processors.github.io/documentation/latest/toolchain/building-toolchains/) 
guide to build any ARC GNU toolchain manually using Crosstool-NG.

## Usage examples

In all of the following examples, it is expected that GNU toolchain for ARC has
been added to the user's `PATH` environment variable. Please note that built toolchain
by default gets installed in the current users's `~/x-tools/TOOLCHAIN_TUPLE` folder,
where `TOOLCHAIN_TUPLE` is by default dynamically generated based on the toolchain type
(bare-metal, glibc or uclibc), CPU's bitness (32- or 64-bit), provided vendor name etc.

For example:

* With `gf-arc-multilib-elf32` sample built toolchain will be installed in `~/x-tools/arc-gf-elf`
* With `gf-arc64-unknown-elf` sample built toolchain will be installed in `~/x-tools/arc64-gf-elf`

You can find general information about GNU ARC toolchains and usage examples on
[the official documentation page](https://foss-for-mips-arc-processors.github.io/documentation/latest/toolchain/).

Usage examples for ARC Classic:

* [Getting Started with nSIM](https://foss-for-mips-arc-processors.github.io/documentation/latest/toolchain/arc-classic/getting-started-nsim/)
* [Getting Started with Picolibc](https://foss-for-mips-arc-processors.github.io/documentation/latest/toolchain/arc-classic/getting-started-picolibc/)
* [ARC HS Development Kit](https://foss-for-mips-arc-processors.github.io/documentation/latest/platforms/board-hsdk/)
* [ARC EM Software Development Platform](https://foss-for-mips-arc-processors.github.io/documentation/latest/platforms/board-emsdp/)
* [Debugging applications on Linux](https://foss-for-mips-arc-processors.github.io/documentation/latest/linux/hsdk/build/#debugging-applications-using-gdbserver)

Usage examples for ARC-V:

* [Getting Started with Picolibc](https://foss-for-mips-arc-processors.github.io/documentation/latest/toolchain/arc-v/getting-started-picolibc/)
* [Getting Started with Newlib](https://foss-for-mips-arc-processors.github.io/documentation/latest/toolchain/arc-v/getting-started-newlib/)
* [Running on nSIM](https://foss-for-mips-arc-processors.github.io/documentation/latest/toolchain/arc-v/running-on-nsim/)
* [Running on QEMU](https://foss-for-mips-arc-processors.github.io/documentation/latest/toolchain/arc-v/running-on-qemu/)

## Getting help


Everyone is welcome to open an issue against
[toolchain](https://github.com/foss-for-mips-arc-processors/toolchain)
repository on GitHub.
