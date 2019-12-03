FROM anapsix/alpine-java:8_jdk_unlimited
ENV JAR_PATH=/application/lib/helloworld.jar
RUN mkdir /application
COPY ./application/ /application/
RUN chmod +x /application/bin/*.sh
CMD [ "/application/bin/start-app.sh" ]