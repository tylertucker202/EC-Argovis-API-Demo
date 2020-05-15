# EC-Argovis-API-Demo

## Demonstration of Argovis Python API - For Earthcube 2020 meeting

You can run these notebooks using your own jupyter kernal. 

The notebooks use some libraries that can take time to set up on some systems (e.g. Cartopy).

I've created a Dockerfile to make this install easier.

This project assumes that [Docker](https://www.docker.com/) is installed on your PC, and that the daemon is running.

First open a terminal

Then build the image with the following command

`docker build --no-cache -t argovis_python_api_demo:1.0 .`

Run the image with this code in terminal or windows powershell

`docker run  -v ${PWD}:/usr/src/av_py_env argovis_python_api_demo:1.0`

Lastly follow the provided link in the terminal. You may be promted to set the kernal on a notebook. Just set the kernal to av_py_env. Good luck!
