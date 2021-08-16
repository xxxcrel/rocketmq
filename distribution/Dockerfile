FROM openjdk:8-jdk
COPY target/rocketmq-4.9.0/rocketmq-4.9.0/ /opt/rocketmq-4.9.0/
ENTRYPOINT ["sh", "/opt/rocketmq-4.9.0/bin/mqbroker", "-n host.docker.internal:9876", "-c /opt/rocketmq-4.9.0/conf/broker-slave.conf"]
