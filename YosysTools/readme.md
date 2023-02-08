# X11 server-enabled Linux development envirnment

[![dockeri.co](https://dockerico.blankenship.io/image/archfx/yosystools)](https://hub.docker.com/r/archfx/yosystools)

Pull directly from the Docker-Hub
```shell
docker pull archfx/yosystools
```
Set the expected location to share with the container
```shell
export LOC=<directory you want>
```

Run the Docker image
```shell
sudo docker run -t -p 6080:6080 -v "${PWD}/:/yosystools" -w /yosystools --name linuxdev archfx/yosystools
```

This will generate a VNC server link, that you can access the GUI environment with the shared directory on the browser

In order to access the container with CLI

```shell
sudo docker exec -it linuxdev /bin/bash
```
