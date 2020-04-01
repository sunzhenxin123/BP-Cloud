FROM openjdk
VOLUME /tmp
ADD server_center.jar server_center.jar
EXPOSE 8761
CMD exec java -Xmx512m -Xms512m  -Djava.security.egd=file:/dev/./urandom -jar /server_center.jar
