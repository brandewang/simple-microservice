FROM harbor.corp.gihtg.com/base/openjdk:8-jdk-alpine
LABEL maintainer www.ctnrs.com
ENV JAVA_ARGS="-Dfile.encoding=UTF8 -Duser.timezone=GMT+08"
COPY ./target/portal-service.jar ./
#COPY pinpoint /pinpoint
EXPOSE 8080
CMD java -jar $JAVA_ARGS $JAVA_OPTS /portal-service.jar
