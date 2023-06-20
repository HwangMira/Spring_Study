# Spring_Study

### 6/20 스프링 라이브러리, 뷰 
Gradle은 의존관계가 있는 라이브러리를 함께 다운로드한다.
#### 스프링 부트 라이브러리
- spring-boot-starter-web
 - spring-boot-starter-tomcat:톰캣(웹서버)
 - spirng-webmvc: 스프링 웹MVC
- spring-boot-starter-thymeleaf: 타임리프 템플릿 엔진(View)
- spring-boot-stater(공통): 스프링부트 + 스프링 코어 + 로깅
 - spring-boot
  - spring-core
 - spring-boot-starter-logging
  - logback, slf4j
#### 스프링 테스트 라이브러리
- spring-boot-starter-test
- junit(테스트 프레임워크), mockito(목 라이브러리), assertj(테스트 코드를 더 펺게 작성하도록 도와주는 라이브러리), spring-test(스프링 통합 테스트 지원)

### View 환경설정
#### Welcom Page 만들기
 - 스프링 부트가 제공하는 Welcome Page 기능
 - static/index.html을 올려두면 Welcome page 기능을 제공한다.
 - 
