ARG FROM_TAG=latest
FROM quay.io/continuouspipe/solr6:${FROM_TAG}

MAINTAINER Kieren Evans <kieren.evans+cp-dockerfiles@inviqa.com>

ENV SOLR_CORE_NAME=d8
COPY ./docker-entrypoint-initdb.d/ /docker-entrypoint-initdb.d
COPY ./usr/ /usr
