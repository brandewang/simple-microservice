FROM harbor.corp.gihtg.com/base/openjdk:8-jdk-alpine
LABEL maintainer www.ctnrs.com
ENV JAVA_ARGS="-Dfile.encoding=UTF8 -Duser.timezone=GMT+08"
COPY ./target/order-service-biz.jar ./
#COPY pinpoint /pinpoint
EXPOSE 8020
CMD java -jar $JAVA_ARGS $JAVA_OPTS /order-service-biz.jar
