FROM openjdk:17-oracle

RUN mkdir -p /opt/logs
WORKDIR /opt/logs
ENTRYPOINT [ "sh", "-c" ]
CMD ["exec java -Duser.timezone-America/Lima  \
				-jar *.jar"]