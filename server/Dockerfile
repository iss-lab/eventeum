FROM openjdk:8-jre
WORKDIR /
ADD target/eventeum-server.jar eventeum-server.jar
ADD docker-scripts/start-eventeum.sh start-eventeum.sh
ENV CONF ""
EXPOSE 8060
CMD ./start-eventeum.sh