FROM frolvlad/alpine-oraclejdk8:slim
ENV SYSTEM_PROPS -Dfoo=bar
ADD /sampleapp-1.0-RELEASE.jar //
ENTRYPOINT ["sh", "-c", "java ${SYSTEM_PROPS} -Djava.security.egd=file:/dev/./urandom -jar /sampleapp-1.0-RELEASE.jar"]
