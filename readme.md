#Build

docker build https://github.com/bak772/docker.git  -f Dockerfile -t img_nb_dockerfile

#Start

docker run -it --rm --name c_nb_dockerfile img_nb_dockerfile

