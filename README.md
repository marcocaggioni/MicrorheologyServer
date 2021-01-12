# microrheology-server


get official docker image for jupyter scipy on dokerhub https://hub.docker.com/r/jupyter/scipy-notebook
```
docker pull jupyter/scipy-notebook
```

run image

```
docker run -it -p 8888:8888 -v F:\microrheology\:/home/jovyan/work 8809973b0203
```

get token from shell and open jupyter notebook in the browser for example:

```
http://127.0.0.1:8888/?token=c5ae2e40409bb4eff8a2064e4f119d142466054a3d5af560
```

Use the jupyter terminal to clone this repository

```
git clone https://github.com/marcocaggioni/microrheology-server.git
```

Install microrheology requireements

```
cd microrheology-server
conda install --yes --file requirements.txt
```


