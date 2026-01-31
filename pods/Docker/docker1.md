DOCKER INSTALLATION SCRIPT
---------------------------
curl -fsSL https://get.docker.com -o /tmp/install-docker.sh
sh /tmp/install-docker.sh

sudo usermod -aG docker ubuntu

DOCKERFILE - BUILDING DOCKER IMAGE FROM PACKAGE  [JAVA APPLICATION]
-----------------------------------------------
FROM eclipse-temurin:21-alpine
LABEL author=harshitha
LABEL project=learning
LABEL version=3.3.0
RUN adduser -D -h /app -s /bin/sh spc
USER spc
EXPOSE 8080
COPY --chown=spc:spc /spc/target/spring-petclinic-3.3.0-SNAPSHOT.jar /app/spring-petclinic-3.3.0-SNAPSHOT.jar
WORKDIR /app
CMD ["java", "-jar", "spring-petclinic-3.3.0-SNAPSHOT.jar"]
