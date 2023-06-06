FROM debian:latest
RUN apt update \
  && apt upgrade -y \
  && apt install -y prometheus-node-exporter \
  && apt install -y nagios-nrpe-plugin
