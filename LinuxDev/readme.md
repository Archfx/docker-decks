# X11 server enabled linux development envirnment

Pull direclty from the Docker-Hub
```shell
docker pull archfx/linuxdev
```

Run the Docker image
```shell
docker run -t -p 6080:6080 -v "${PWD}/:/linuxdev" -w /linuxdev archfx/linuxdev
```

This will generate a VNC server link, that you can access the GUI environment with the browser
