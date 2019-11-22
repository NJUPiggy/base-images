FROM debian:stretch-slim

COPY ./prometheusbeat /
COPY ./prometheusbeat.yml /

ENTRYPOINT ["/prometheusbeat"]

CMD ["-e", "-c", "prometheusbeat.yml"]