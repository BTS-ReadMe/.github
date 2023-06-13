# 프로젝트명
>  실시간 소통 웹소설 컨텐츠 플랫폼 "ReadMe" 입니다!


## 멤버
* 팀장 : 송진영(BE)
* 팀원
  * FE : 김민경, 이시현
  * BE : 정현준, 주영민

## 기능

<img src="https://github.com/BTS-ReadMe/.github/assets/110506500/48d5b681-c6b7-4471-aeb5-a19c10ff144f" width="300" height="500" alt="이미지">
<img src="https://github.com/BTS-ReadMe/.github/assets/110506500/ad986a26-091f-4db4-8382-25479707c984" width="300" height="500" alt="이미지">
<img src="https://github.com/BTS-ReadMe/.github/assets/110506500/9315179f-606c-4085-8be2-3f5731d59e3e" width="300" height="500" alt="이미지">


## 설치 방법

OS X & 리눅스, 윈도우:

1. GitHub Repository에서 fork 버튼을 누른다. 
2. GitHub Access Token 발급 후 Secrets 등록한다.
3. [환경설정](#enviroment) 설정


BackEnd
```sh
 - Java 11 이상 (이 프로젝트에 빌드 된 버전은 11 버전입니다.)
```

## BackEnd 개발 환경 설정

```sh
./gradlew -x build
```



## 페이지 접근 권한
|권한|이름|
|:-:|:-:|
|USER|로그인한 유저|
|GUEST|게스트|

## Enviroment


|권한 이름|내용|
|:-:|:-:|
|$DB_USERNAME|DB 이름|
|$DB_PWD|DB 비밀번호|
|$SCHEMA_NAME| SCHEMA 이름|
|$PORT|포트번호|
|$IP|아이피|
|$ADMIN_MAIL_ID| 메일 아이디 |
|$ADMIN_MAIL_PWD| 메일 비밀번호|
|SECRETKEY| Encryption Key |

- application.yml 설정
```
spring:
  datasource:
    driver-class-name: com.mysql.cj.jdbc.Driver
    username: ${{ DB_USERNAME }}
    url: jdbc:mysql://${{ IP }}:${{ PORT }}/${{ SCHEMA_NAME }}
    password: {{ DB_PWD }}
  jpa:
    properties:
      hibernate:
        dialect: org.hibernate.dialect.MySQL5Dialect
        format_sql: true
    hibernate:
      ddl-auto: update
  data:
    redis:
      host: ${{ IP }}
      port: ${{ PORT }}
SECRET_KEY: ${{ SECRETKEY }}
```

- email.properties 설정
```
mail.smtp.socketFactory.class=javax.net.ssl.SSLSocketFactory
mail.smtp.socketFactory.fallback=false
mail.smtp.socketFactory.port=465
mail.smtp.starttls.required=true
mail.smtp.starttls.enable=true
mail.smtp.port=465
mail.smtp.auth=true

AdminMail.id={ADMIN_MAIL_ID}
AdminMail.password={ADMIN_MAIL_PWD}
```


## 기여 방법

### Tech stack
Back-end  
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=Spring Boot&logoColor=white" />
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=Spring&logoColor=white" />
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat&logo=Spring Security&logoColor=white" />
<img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Java&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white" />
<img src="https://img.shields.io/badge/JWT-000000?style=flat&logo=JWT&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=Redis&logoColor=white" />

FrontEnt  
<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=Next.js&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=TypeScript&logoColor=white" />
<img src="https://img.shields.io/badge/Recoil-5A29E4?style=flat&logo=Recoil&logoColor=white" />
<img src="https://img.shields.io/badge/Axios-000000?style=flat&logo=Axios&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white" />


Tool  
<img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=flat&logo=IntelliJ IDEA&logoColor=white" />
<img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat&logo=Visual Studio Code&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=flat&logo=GitHub Actions&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=white" />
<img src="https://img.shields.io/badge/Google Cloud-4285F4?style=flat&logo=Google Cloud&logoColor=white" />




<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
