FROM openjdk:18
ARG DATABASE
WORKDIR app
COPY . .
EXPOSE 8080
ENV DATABASE ${DATABASE}
CMD sh -c './mvnw spring-boot:run -Dspring-boot.run.profiles=$DATABASE'
