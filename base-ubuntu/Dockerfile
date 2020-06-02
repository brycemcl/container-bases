FROM ubuntu:rolling
RUN apt-get update && apt-get dist-upgrade -y && apt-get autoremove -y && apt-get clean -y && apt-get install -y --no-install-recommends tini && DEBIAN_FRONTEND="noninteractive" TZ="Canada/Pacific" apt-get -y install tzdata
