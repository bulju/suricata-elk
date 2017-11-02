FROM docker.elastic.co/logstash/logstash:5.6.3
MAINTAINER JREY
ADD dist/ /home/dist
RUN cd /home/dist/ && \
    cp logstash.conf /opt/logstash/pipeline/logstash.conf
    #chmod 775 /var/log/suricata/eve.json


