# Docker-Decks

<img src="https://raw.githubusercontent.com/Archfx/docker-decks/master/images/docker-logo.png" alt="docker" width="200" align="right">
Important Docker Images to run linux environments (Focued to run nativly on Apple sillicon). You can direclty pull pre-built images from Docker-Hub.

<!-- [![dockeri.co](https://dockerico.blankenship.io/image/archfx/yosystools)](https://hub.docker.com/r/archfx/yosystools) -->
* [YosysTools](https://github.com/Archfx/docker-decks/tree/master/YosysTools) : Full yosys tool chain with ice40 FPGA support with GUI support
* [rvutils](https://github.com/Archfx/docker-decks/tree/master/RV32I): RISC-V (32/64 bit) toolchain in docker
    - light 
    - qemu : version with the QEMU simulator
* [LinuxDev](https://github.com/Archfx/docker-decks/tree/master/LinuxDev) : GUI supported linux environemt
* [rosette](https://github.com/Archfx/docker-decks/tree/master/rosette) : +racket +jupyter +z3 all in one formal verification framework
* [Ice40Tools](https://github.com/Archfx/docker-decks/tree/master/ice40tools) : Full toolchain for open source ICE40 FPGAs.

### Build Status

| Container  |  tag |  status | docker-hub |
|:-:|:-:|:-:|:-:|
| YosysTools  | latest  |   | [archfx/yosystools](https://hub.docker.com/repository/docker/archfx/yosystools/general) |
|  rvutils     | light   | [![rvutils-latest](https://github.com/Archfx/docker-decks/actions/workflows/docker-image-rvutils.yml/badge.svg)](https://github.com/Archfx/docker-decks/actions/workflows/docker-image-rvutils.yml)  | [archfx/rvutils:latest](https://hub.docker.com/repository/docker/archfx/rvutils/general) |
|  rvutils     |  qumu   |  [![rvutils-qemu](https://github.com/Archfx/docker-decks/actions/workflows/docker-image-rvutils-qemu.yml/badge.svg)](https://github.com/Archfx/docker-decks/actions/workflows/docker-image-rvutils-qemu.yml) | [archfx/rvutils:qemu](https://hub.docker.com/repository/docker/archfx/rvutils/general)|
|  LinuxDev | latest  |  [![LinuxDev](https://github.com/Archfx/docker-decks/actions/workflows/docker-image-linuxdev.yml/badge.svg)](https://github.com/Archfx/docker-decks/actions/workflows/docker-image-linuxdev.yml) | [archfx/linuxdev](https://hub.docker.com/repository/docker/archfx/rv32i/general) |
|  rosette | latest  | [![rosette](https://github.com/Archfx/docker-decks/actions/workflows/docker-image-rosette.yml/badge.svg)](https://github.com/Archfx/docker-decks/actions/workflows/docker-image-rosette.yml)  | [archfx/rosette](https://hub.docker.com/repository/docker/archfx/rv32i/general) |
|  ice40tools | latest  | [![ice40tools](https://github.com/Archfx/docker-decks/actions/workflows/docker-image-ice40tools.yml/badge.svg)](https://github.com/Archfx/docker-decks/actions/workflows/docker-image-ice40tools.yml)  | [archfx/ice40tools](https://hub.docker.com/repository/docker/archfx/ice40tools/general) |


