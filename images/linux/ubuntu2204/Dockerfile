FROM ubuntu:22.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update -y \
    && apt-get upgrade -y \
    && apt-get install -y build-essential python3 python3-pip \
    && pip install awscli \
    && apt-get -y clean