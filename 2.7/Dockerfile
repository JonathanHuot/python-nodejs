FROM python:2.7
RUN apt-get update \
    && apt-get install -y sudo \
    && apt-get install -y build-essential \
    && apt-get install -y nodejs \
    && apt-get install -y npm \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
RUN useradd -m docker && \
    echo "docker:docker" | chpasswd && \
    adduser docker sudo

USER docker
