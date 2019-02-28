FROM circleci/golang:1.11

USER root

RUN apt-get update \
    && apt-get install -y librdkafka1 librdkafka-dev gcc musl-dev

USER circleci