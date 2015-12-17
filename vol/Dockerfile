FROM debian:jessie

RUN mkdir /home/strong-pm && \
    useradd -ms /bin/bash strong-pm &&  \
    chown -R strong-pm:strong-pm /home/strong-pm

VOLUME /home/strong-pm
VOLUME /db/data
VOLUME /opt/splunk/etc
VOLUME /opt/splunk/var
VOLUME /var/lib/rabbitmq/mnesia/rabbit@mq