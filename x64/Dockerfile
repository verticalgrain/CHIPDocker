FROM ubuntu:16.04
MAINTAINER Harsha Kuchampudi <harshakuchampudi@gmail.com>
WORKDIR /
RUN apt-get update && apt-get install -y git curl wget usbutils
RUN git clone https://github.com/verticalgrain/CHIPDocker.git
RUN cd /CHIPDocker && git pull && chmod +x /CHIPDocker/x64/setup_ubuntu.sh
RUN ./CHIPDocker/x64/setup_ubuntu.sh
