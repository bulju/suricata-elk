FROM ubuntu:latest
MAINTAINER JREY
RUN apt-get update
RUN apt-get install -y suricata ethtool
RUN cd /home/ 
RUN wget http://rules.emergingthreats.net/open/suricata/emerging.rules.tar.gz 
RUN tar zxf emerging.rules.tar.gz 
RUN cp -r rules /etc/suricata/
ENTRYPOINT [ "suricata", "-c", "/etc/suricata/suricata-debian.yaml", "-i", "ens160", "-k", "none" ]

