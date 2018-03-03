FROM python:3.6
RUN apt-get update \
    && apt-get install -y build-essential \
    && apt-get install -y nodejs \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
