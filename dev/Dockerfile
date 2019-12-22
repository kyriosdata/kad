FROM maven:3.6.0-jdk-11-slim

RUN apt-get update

RUN apt-get install -y git

# Gauge
RUN mkdir -p /root/.gauge/config/
RUN touch /root/.gauge/config/gauge.properties
RUN curl -SsL https://downloads.gauge.org/stable | sh
RUN gauge install java
RUN gauge install html-report

# Remove arquivos
RUN rm -fr /var/lib/apt/lists/*

# Executar quando iniciado o contêiner
ENTRYPOINT /bin/bash
