FROM docker.elastic.co/beats/filebeat:6.4.3

#COPY filebeat-test.yml /usr/share/filebeat/filebeat.yml
COPY ./logstash-tutorial-dataset /usr/share/filebeat/

USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml
USER filebeat