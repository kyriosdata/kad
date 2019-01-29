FROM maven:3.6.0-jdk-11-slim

# Primeiro: instala GIT

RUN curl -SsL https://downloads.gauge.org/stable | sh && \
    apt-get update && \
    apt-get install -y git && \
    apt-get install gauge && \
     rm -fr /var/lib/apt/lists/*
