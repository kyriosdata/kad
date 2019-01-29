FROM maven:3.6.0-jdk-11-slim

# Primeiro: instala GIT

RUN apt-key adv --keyserver hkp://pool.sks-keyservers.net --recv-keys 023EDB0B && \
    echo deb https://dl.bintray.com/gauge/gauge-deb nightly main | sudo tee -a /etc/apt/sources.list && \
    apt-get update && \
    apt-get install -y git && \
    apt-get install gauge && \
     rm -fr /var/lib/apt/lists/*
