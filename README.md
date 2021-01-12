# microrheology-server


Modifying official docker image for jupyter scipy on dokerhub https://hub.docker.com/r/jupyter/scipy-notebook

to build the microrheologyserver image use docker build:

```
docker build https://github.com/marcocaggioni/MicrorheologyServer.git#main:Docker -t microrheologyserver
```

after building image run it

```
docker run -it -p 8888:8888 -v F:\microrheology\:/home/jovyan/work microrheologyserver
```

copy the token from the shell and open server from browser

```
http://127.0.0.1:8888/?token=f8d13a4d44d7729b1b8a6d52b141946be49979b53fdcc10e
```

using the token you can set the password for the future

From a jupyter terminal clone this repository

```
git clone https://github.com/marcocaggioni/MicrorheologyServer.git
```

Use notebooks in the notebooks folder to perform microrheology
