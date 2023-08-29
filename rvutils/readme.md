# GCC Tool chain for Risc-V


[![dockeri.co](https://dockerico.blankenship.io/image/archfx/rv32i)](https://hub.docker.com/r/archfx/rv32i)

Pull directly from the Docker-Hub
```shell
docker pull archfx/rvutils
```
Set the expected location to share with the container
```shell
export LOC=<directory you want>
```

Run the Docker image
```shell
sudo docker run -t -p 6080:6080 -v "${PWD}/:/$LOC" -w /$LOC --name rvutils archfx/rvutils
```

PicoRV repo : https://github.com/YosysHQ/picorv32


## Simulation

There are two simulation options with Spike simulator and QEMU.

- Find the spike simulator at `archfx/rv32i:spike`
- Find the QEMU simulator at `archfx/rv32i:qemu`
