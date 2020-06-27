# Jupyter-lab docker environment for geospatial data science research



## Contents

This project is a containerised environment devoted to managing dependencies efficiently, as well as working under controlled and replicable environments. 
The dependencies have been addressed in `requirements.txt` (inside the folder `docker`). Feel free to use this repo as a whiteboard to add further dependencies. 


## Requirements

Make sure you have installed docker and docker compose in your machine. Click [here](https://docs.docker.com/compose/install/) for further info.


## How to run it

Just type `docker-compose up` for creating the container and launching jupyter-lab.
If executing from a remote instance, make sure you map the `localhost` address provided by the remote instance to the actual remote address. 
The port mapping is  `8888:8888`.
The access token is provided once the docker-compose command is executed in the command line.
The folder `wkdir` is mounted as a volume in the work directory folder inside the container, so your files can be saved after the session.


## Suggestions
Please, do not hesitate to drop any questions or suggestions. Your comments are very much appreciated. 

