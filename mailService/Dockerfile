FROM openjdk:8-jre
COPY target/*.jar /app/mailService.jar
COPY ./run.sh /app/
WORKDIR /app
RUN chmod 777 /app/run.sh
EXPOSE 8080
#CMD ["java", "jar","mailService.jar"]
CMD ["/app/run.sh"]
