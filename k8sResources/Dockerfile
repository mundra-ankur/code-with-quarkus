FROM quay.io/jkube/jkube-java:0.0.16
ENV JAVA_OPTIONS=-Dquarkus.http.host=0.0.0.0 JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="" org.label-schema.version=1.0.0-SNAPSHOT org.label-schema.schema-version=1.0 org.label-schema.build-date=2022-10-12T13:48:53.634843796 org.label-schema.name=code-with-quarkus org.label-schema.vcs-ref=59edf690c60b54914fa5b9fe43a4d1dd09a698aa org.label-schema.vcs-url=https://github.com/mundra-ankur/code-with-quarkus.git
EXPOSE 8080 8778 9779
COPY /lib/deployments /deployments/
COPY /fast-jar/deployments /deployments/
WORKDIR /deployments
