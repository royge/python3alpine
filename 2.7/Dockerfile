# The base image is python 2.7
FROM python:2.7-stretch

# Author: Roy Evangelista
MAINTAINER Roy Evangelista <royevangelista@gmail.com>

# Install required packages

RUN apt-get update && apt-get -y install unzip

# Install ansible
RUN pip install flake8

# Copied from base image
CMD ["python"]
