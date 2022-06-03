# Jupyter datascience notebook + web3.py container 

## Build and run for the first time

Download this repository  
https://github.com/kentwait/datascience_notebook_web3py

Change directory and launch using `docker-compose`.

    cd datascience_notebook_web3py
    docker-compose up -d

## Run

    cd jupyter_web3py
    docker-compose up -d

Open web browser to http://localhost:10000/

## Remove

    docker container ls

Look for container image name "datascience_notebook_web3py" and copy the container ID

    docker kill {container ID}
