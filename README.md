# Docker

## Build image

`docker build -t jupyter-projet-ia .`

## Run image

`docker run -it --rm -v "$(realpath ./notebooks)":/tf/notebooks -p 8888:8888 jupyter-projet-ia`
