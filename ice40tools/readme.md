# Ice40 FPGA tool chain in a Docker Container

[![dockeri.co](https://dockerico.blankenship.io/image/archfx/ice40tools)](https://hub.docker.com/r/archfx/ice40tools)

Pull directly from the Docker-Hub
```shell
docker pull archfx/ice40tools
```
Set the expected location to share with the container
```shell
export LOC=<directory you want>
```

Run the Docker image
```shell
sudo docker run -t -p 6080:6080 -v "${PWD}/:/$LOC" -w /$LOC --name ice40tools archfx/ice40tools
```

