FROM docker.elastic.co/elasticsearch/elasticsearch:5.6.3
MAINTAINER JREY
ADD config/ /home/config/
RUN cd /home/config/ && \
    cp elasticsearch.yml /usr/share/elasticsearch/config
