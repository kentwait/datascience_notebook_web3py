# Jupyter datascience notebook + web3.py container 

## Build and run for the first time

    unzip jupyter_web3py.zip
    cd jupyter_web3py
    docker-compose up -d

## Run

    cd jupyter_web3py
    docker-compose up -d

## Remove

    docker container ls

Look for container image name "jupyter_web3py_notebook" and copy the container ID

    docker kill {container ID}