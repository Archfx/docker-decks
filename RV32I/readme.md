# Tool chain for PicoRV32 - A Size-Optimized RISC-V CPU


[![dockeri.co](https://dockerico.blankenship.io/image/archfx/rv32i)](https://hub.docker.com/r/archfx/rv32i)

Pull directly from the Docker-Hub
```shell
docker pull archfx/rv32i
```
Set the expected location to share with the container
```shell
export LOC=<directory you want>
```

Run the Docker image
```shell
sudo docker run -t -p 6080:6080 -v "${PWD}/:/$LOC" -w /$LOC --name rv32i archfx/rv32i
```

PicoRV repo : https://github.com/YosysHQ/picorv32
