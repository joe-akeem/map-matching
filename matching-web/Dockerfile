FROM openjdk:11-jre
MAINTAINER Joachim Lengacher <info@singletrail-map.eu>

COPY target/graphhopper-map-matching-web.jar graphhopper-map-matching-web.jar
ENV JAVA_OPTS=""
ENTRYPOINT exec java $JAVA_OPTS -jar /graphhopper-map-matching-web.jar $0 $@