# API Test Swagger2

* Swagger2를 활용해 API를 테스트 해볼 수 있는 서버입니다
* oauth2 토큰 발급을 통한 인증/인가
* BFF, Raw 데이터 조회 및 수정 테스트

## 프로젝트 환경

- Java 12
- SpringBoot 2.1.x
- jdbc MySQL
- Spring Data JPA
- Spring Security
- Springfox Swagger2

## 주소
<http://ec2-18-237-61-191.us-west-2.compute.amazonaws.com::8080/swagger-ui.html>

## 배포

```
> mvn 설치
sudo apt-get install maven

> 패키징
sudo mvn package

> target 내 jar 실행
sudo nohup java -jar {jar 파일} &
```
