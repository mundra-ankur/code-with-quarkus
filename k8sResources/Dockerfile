FROM quay.io/jkube/jkube-java:0.0.16
ENV JAVA_OPTIONS=-Dquarkus.http.host=0.0.0.0 JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="" org.label-schema.version=1.0.0-SNAPSHOT org.label-schema.schema-version=1.0 org.label-schema.build-date=2022-10-07T16:59:01.030552221 org.label-schema.name=code-with-quarkus org.label-schema.vcs-ref=b884ed1dd85b56b1a03ed7362318baf3b33698ec org.label-schema.vcs-url=https://github.com/mundra-ankur/code-with-quarkus.git
EXPOSE 8080 8778 9779
COPY /lib/deployments /deployments/
COPY /fast-jar/deployments /deployments/
WORKDIR /deployments
