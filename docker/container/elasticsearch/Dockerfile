FROM docker.elastic.co/elasticsearch/elasticsearch:6.0.1
LABEL maintainer "kuryu <revision279@gmail.com>"

RUN elasticsearch-plugin install analysis-icu
RUN elasticsearch-plugin install analysis-kuromoji
RUN elasticsearch-plugin install ingest-attachment
