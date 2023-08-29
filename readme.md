# Docker-Decks

<img src="https://cdn.freebiesupply.com/logos/large/2x/docker-logo-png-transparent.png" alt="docker" width="200" align="right">
Important Docker Images to run linux environments (Focued to run nativly on Apple sillicon). You can direclty pull pre-built images from Docker-Hub.

<!-- [![dockeri.co](https://dockerico.blankenship.io/image/archfx/yosystools)](https://hub.docker.com/r/archfx/yosystools) -->
* [YosysTools : Full yosys tool chain with ice40 FPGA support with GUI support](https://github.com/Archfx/docker-decks/tree/master/YosysTools)
* [RV32I: RISC-V toolchain in docker](https://github.com/Archfx/docker-decks/tree/master/RV32I)
    - light 
    - qemu : version with the QEMU simulator
* [LinuxDev : GUI supported linux environemt](https://github.com/Archfx/docker-decks/tree/master/LinuxDev)
* [rosette: +racket +jupyter +z3 all in one](https://github.com/Archfx/docker-decks/tree/master/rosette)


### Build Status

| Container  |  tag |  status | docker-hub |
|:-:|:-:|:-:|:-:|
| YosysTools  | latest  |   | [archfx/yosystools](https://hub.docker.com/repository/docker/archfx/yosystools/general) |
|  RV32I      | light   | [![rv32i-latest](https://github.com/Archfx/docker-decks/actions/workflows/docker-image-rv32i.yml/badge.svg)](https://github.com/Archfx/docker-decks/actions/workflows/docker-image-rv32i.yml)  | [archfx/rv32i:latest](https://hub.docker.com/repository/docker/archfx/rv32i/general) |
|  RV32I      |  qumu   |   | [archfx/rv32i:qemu](https://hub.docker.com/repository/docker/archfx/rv32i/general)|
|  LinuxDev | latest  |   | [archfx/linuxdev](https://hub.docker.com/repository/docker/archfx/rv32i/general) |
|  rosette | latest  |   | [archfx/rosette](https://hub.docker.com/repository/docker/archfx/rv32i/general) |

