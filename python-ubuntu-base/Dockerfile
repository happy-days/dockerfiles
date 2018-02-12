FROM ubuntu:latest

ARG PYTHON_VERSION
ARG PIP_VERSION

RUN apt-get update \
    && apt-get install -y "$PYTHON_VERSION" "$PYTHON_VERSION"-pip "$PYTHON_VERSION"-dev gcc
#    && pip install --upgrade pip
