# gbdc-ppda-slides

Slides for Big Data Conference / Bootcamp 2016

The slides are live at: [http://lgautier.github.io/gbdc-ppda-slides/]

The conference version of edible art: a docker container to reproduce all code in an interactive notebook.

## Setup

### Docker

If you already have docker installed and running, go to the next section. Otherwise check [https://www.docker.com/]

### Starting

The following two-step process should be all that is needed:

Open a terminal and run:

```bash
docker run --rm -it -p 8888:8888 \
            rpy2/gbdc-ppda-slides
```

Open a web browser and point it to the jupyter notebook server running in the container: [http://localhost:8888/]

**note:** is using docker-machine (OSX or Windows) the host for the jupyter server will not be `localhost` but the IP returned by: 

```bash
docker-machine ip [MACHINE]
```

## Dataset

J. McAuley and J. Leskovec. From amateurs to connoisseurs: modeling the evolution of user expertise through online reviews. WWW, 2013. [http://snap.stanford.edu/data/web-FineFoods.html]
