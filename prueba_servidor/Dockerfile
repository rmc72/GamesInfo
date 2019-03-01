FROM openjdk:8-jre
COPY target/*.jar /app/webService.jar
COPY ./run.sh /app/
WORKDIR /app
RUN chmod 777 /app/run.sh
EXPOSE 8443
CMD ["/app/run.sh"]


