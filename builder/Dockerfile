FROM ghcr.io/engineer-man/piston:latest

ADD . /piston/packages/

USER root

RUN mkdir -p /isolate && chmod 777 /isolate

ENV PISTON_TMP=/tmp
