#build
docker build -t jupyter-notebook .

#create container
docker run -it --publish 8888:8888 --env NOTEBOOK_DIR=/usr/local/notebook jupyter-notebook
