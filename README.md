# EC-Argovis-API-Demo

## Demonstration of Argovis Python API - For Earthcube 2020 meeting

You can run these notebooks using your own jupyter kernal. 

The notebooks use some libraries that can be painful to download (ahem, Cartopy).

I've created a Dockerfile to make this install easier. 

First open a terminal

Then build the image with the following command

`docker build --no-cache -t argovis_python_api_demo:1.0 .`

Run the image with this code if linux

`docker run --net=host -v ${PWD}:/usr/src/av_py_env argovis_python_api_demo:1.0`

and this if Windows

`docker run --net=host -v %cd%:/usr/src/av_py_env argovis_python_api_demo:1.0`

Lastly follow the provided link in the terminal. You may be promted to set the kernal on a notebook. Just use ioam_env. Good luck!
