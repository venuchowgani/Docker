FROM openjdk:11
LABEL author="venu"
LABEL project="sricloud"
ARG SOURCE_JAR_LOCATION=https://referenceapplicationskhaja.s3.us-west-2.amazonaws.com/spring-petclinic-2.4.2.jar
ADD ${SOURCE_JAR_LOCATION} /spring-petclinic-2.4.2.jar
ARG TESTING="FUN"
ENV TESTING=${TESTING}
RUN set & echo "ENV: ${TESTING}, ARG ${SOURCE_JAR_LOCATION}"
EXPOSE 8080
CMD [ "java", "-jar", "/spring-petclinic-2.4.2.jar" ]