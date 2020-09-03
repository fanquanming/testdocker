# 指定基础镜像 这里springboot项目运行只需要java jdk环境即可
FROM java:8

COPY *.jar /app.jar

CMD ["--server.port=9090"]

EXPOSE 9090
# 运行
ENTRYPOINT ["java", "-jar", "app.jar"]