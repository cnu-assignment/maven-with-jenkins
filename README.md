# 9jo

- github commit push시 webhook으로 jenkins build - 성공!
- jenkins job이 종료된 후 slack notify - 성공!
- SonarQube 연동 - 성공!
---

download this project and review pom.xml and project folder structures.

1. mvn clean spring-boot:run
2. mvn -Pdev clean spring-boot:run
3. mvn -Pprod clean spring-boot:run

in browser check the url "http://localhost:8080"


Jenkins url "http://ec2-18-223-180-118.us-east-2.compute.amazonaws.com:8080"
