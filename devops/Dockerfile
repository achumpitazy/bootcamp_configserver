FROM openjdk:11

RUN mkdir -p /opt/logs
WORKDIR /opt/logs
ENTRYPOINT [ "sh", "-c" ]
CMD ["exec java -Duser.timezone-America/Lima  \
				-jar *.jar"]