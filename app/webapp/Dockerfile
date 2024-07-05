FROM openjdk:24-slim-bullseye

COPY ./DeepScan/target/DeepScan-1.0.jar /application/deepscan.jar
ENTRYPOINT ["java","-jar","/application/deepscan.jar"]
