# 프로젝트명
>  실시간 소통 웹소설 컨텐츠 플랫폼 "ReadMe" 입니다!


## 멤버
* 팀장 : 송진영(BE) : 섹션 서비스, 데이터 플로우 처리
* 팀원
  * FE
    - 김민경 : User 서비스, Search, Viewer 서비스, BFF 처리, Client Data 최적화
    - 이시현 : User Sign In/Up 플로우 처리, 충전/결제 기능, 관리자, 내서재, Profile 포함 운영 기능
  * BE
    - 정현준 : 유저 서비스, 결제 Flow 처리, OAuth API 처리, 보안담당(JWT), 실시간 처리
    - 주영민 : 소설, 유틸, Gateway 서비스, 서버 설계, CI/CD, 모니터링, DevOps

## 기능

|메인|소설|검색|
|:-:|:-:|:-:|
|<img src="https://github.com/BTS-ReadMe/.github/assets/110506500/48d5b681-c6b7-4471-aeb5-a19c10ff144f" width="200" height="500" alt="이미지">|<img src="https://github.com/BTS-ReadMe/.github/assets/110506500/ad986a26-091f-4db4-8382-25479707c984" width="200" height="500" alt="이미지">|<img src="https://github.com/BTS-ReadMe/.github/assets/110506500/9315179f-606c-4085-8be2-3f5731d59e3e" width="200" height="500" alt="이미지">


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
## FrontEnd 개발 환경 설정

```sh
설치 : npm install or yarn
실행 : npm run devlocal or yarn devlocal
```


## 페이지 접근 권한
|권한|이름|
|:-:|:-:|
|ADMIN|관리자|
|USER|로그인한 유저|
|GUEST|게스트|


## 기여 방법

### Tech stack
Back-end  
<img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Java&logoColor=white" />
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=Spring&logoColor=white" />
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=Spring Boot&logoColor=white" />
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat&logo=Spring Security&logoColor=white" />
<img src="https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=flat&logoColor=white" />
<img src="https://img.shields.io/badge/Spring%20Batch-6DB33F?style=flat&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&for-the-badge&logo=MongoDB&logoColor=white" />
<img src="https://img.shields.io/badge/Kafka-231F20?style=flat&for-the-badge&logo=apachekafka&logoColor=white" />
<img src="https://img.shields.io/badge/Zookeeper-FF0000?style=flat&for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Axon%20server-004088?style=flat&for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/JWT-000000?style=flat&logo=JWT&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat&logo=Grafana&for-the-badge&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat&for-the-badge&logo=Prometheus&logoColor=white" />
<img src="https://img.shields.io/badge/Amazonaws-232F3E?style=flat&for-the-badge&logo=amazonaws&logoColor=white" /> 
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Gitaction-2088FF?style=flat&for-the-badge&logo=githubactions&logoColor=white" />


FrontEnt  
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=white" />
<img src="https://img.shields.io/badge/React%20Query-FF4154?style=flat&logo=ReactQuery&logoColor=white" />
<img src="https://img.shields.io/badge/Recoil-5A29E4?style=flat&logo=Recoil&logoColor=white" />
<img src="https://img.shields.io/badge/PWA-5A0FC8?style=flat&logo=PWA&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=TypeScript&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=Next.js&logoColor=white" />
<img src="https://img.shields.io/badge/Ant%20Design-0170FE?style=flat&logo=AntDesign&logoColor=white" />
<img src="https://img.shields.io/badge/Axios-000000?style=flat&logo=Axios&logoColor=white" />


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
