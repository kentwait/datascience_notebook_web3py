FROM jupyter/datascience-notebook:ubuntu-20.04

USER root

# install required libraries

RUN apt-get update \
  && apt-get install -y \
    libssl-dev

RUN pip install --no-cache-dir \
  web3

USER jovyan
