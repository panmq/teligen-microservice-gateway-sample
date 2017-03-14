FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD teligen-microservice-gateway-sample.jar teligen-microservice-gateway-sample.jar
RUN sh -c 'touch /teligen-microservice-gateway-sample.jar'
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -jar /teligen-microservice-gateway-sample.jar" ]