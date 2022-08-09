FROM ubuntu:22.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update -y \
    && apt-get upgrade -y \
    && apt-get install -y build-essential python3 python3-pip nodejs npm \
    && npm install --global yarn \
    && pip install awscli \
    && apt-get -y clean