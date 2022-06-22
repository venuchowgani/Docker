FROM ubuntu:focal
LABEL purpose="sri-cloud" author="venu"
RUN export DEBIAN_FRONTEND=noninteractive && apt update && apt install apache2 -y
EXPOSE 80
CMD [ "sleep", "1d" ]