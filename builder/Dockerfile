FROM ghcr.io/engineer-man/piston:latest

ADD . /piston/packages/

RUN mkdir -p /tmp/isolate && chmod 777 /tmp/isolate
ENV ISOLATE_DIR=/tmp/isolate
ENV PISTON_TMP=/tmp
