# Get latest Deno from docker Hub
FROM denoland/deno:latest

# Install required system packages
RUN apt-get update && apt-get install -y \
    curl \
    git \
    nano \
    python3 \
    build-essential \
    ca-certificates \
    && apt-get clean
    
# Install nvm
RUN rm /bin/sh && ln -s /bin/bash /bin/sh
RUN curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash

# install Node.js
RUN source ~/.nvm/nvm.sh && nvm i --lts

# Change the shell prompt
ENV PS1="deno:\\w# "

WORKDIR /com.docker.devenvironments.code/
