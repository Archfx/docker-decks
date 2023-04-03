This is a complete Racket image with rosette. And configured to work with jupyter notebook.
You can find the full tutorial [here](https://archfx.github.io/posts/2023/04/racketutes1/).

Run the docker container by

```shell 
 docker run -t -p 8888:8888 -v "${PWD}/:/rosette" -w /rosette --name rosette archfx/rosette
```

Inside the container run the Jupyter server by

```shell
jupyter notebook --ip 0.0.0.0 --no-browser --allow-root
```

Click on the link that appers on the container terminal.

Enjoy coding!
