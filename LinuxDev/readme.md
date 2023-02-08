# X11 server-enabled Linux development envirnment

[![dockeri.co](https://dockerico.blankenship.io/image/archfx/linuxdev)](https://hub.docker.com/r/archfx/linuxdev)

Pull directly from the Docker-Hub
```shell
docker pull archfx/linuxdev
```
Set the expected location to share with the container
```shell
export LOC=<directory you want>
```

Run the Docker image
```shell
docker run -t -p 6080:6080 -v "${PWD}/:/$LOC" -w /$LOC archfx/linuxdev
```

This will generate a VNC server link, that you can access the GUI environment with the shared directory on the browser
