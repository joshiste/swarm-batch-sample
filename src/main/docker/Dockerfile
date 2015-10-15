FROM java:8
MAINTAINER Johannes Edmeier
ADD swarm-batch-sample-0.0.1-SNAPSHOT.jar swarm-batch-sample.jar
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom", "-jar","swarm-batch-sample.jar"]
