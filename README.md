# Lyft Dataset Challenge
This repo analyses and trains machine learning algorithms to determine which algorithm produces the best results.

My money is on Yolo v3, but of course we haven't checked anything out yet.

Visualisations can be made using [Lyft's dev tool](https://github.com/lyft/nuscenes-devkit) and [tutorial for using it](https://github.com/lyft/nuscenes-devkit/blob/master/notebooks/tutorial_lyft.ipynb).

This repo is set up with docker to manage the dependencies. Included is a sample titanic.ipynb to demonstrate how to integrate notebook files and datasets.

# Installation

Run `docker-compose build`

After the build process finishes run `docker-compose up` to run the notebooks in the browser. 

After running the container, it should be available in the brower at 127.0.0.1:8888/

The terminal will output the required access token that will asked in order to proceed to the kernel.