#Build

docker build https://github.com/bak772/docker.git  -f Dockerfile -t img_gm_dockerfile

#Start

docker run -it --rm --name c_gm_dockerfile img_gm_dockerfile

