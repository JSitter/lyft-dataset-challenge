# Lyft Dataset Challenge

This repo analyzes data and trains machine learning algorithms to determine which one produces the best results.

My money is on Yolo v3, but of course we haven't checked anything out yet.

Visualisations can be made using [Lyft's dev tool](https://github.com/lyft/nuscenes-devkit) and [tutorial for using it](https://github.com/lyft/nuscenes-devkit/blob/master/notebooks/tutorial_lyft.ipynb).

This repo is set up with docker to manage the dependencies. Included is a sample titanic.ipynb to demonstrate how to integrate notebook files and datasets.

## Installation

Make sure Docker is installed on your machine. Otherwise [go here](https://docs.docker.com/docker-for-mac/install/).

Run `docker-compose build`

After the build process finishes, run `docker-compose up` to start the containers. 

Jupyter labs will be available in the browser at `127.0.0.1:8888`.

The terminal will output the required access token that will be asked in order to proceed to the kernel.

Docker will also allow access to our host's GPU if it has one - [per the documentation](https://www.tensorflow.org/install/docker).

Download the [85 Gb dataset]() and place it into the datasets folder.

The `datasets` and `notebooks` directories are mounted as volumes and are immediately available when updated instead of having to be packaged into the containers.

## Included Files
