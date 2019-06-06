# Spring 5 web programming
* DI(Dependency Injection) 지원
* AOP(Aspect-Oriented Programming) 지원
* MVC Web Framework(Model View Controller) 지원
* JDBC, JPA 연동, 선언적 트랜잭션 처리 등 DB 지원

## 1. 환경설정
* JDK 8 이상 , JSP 2.3
* Spring 5
* Servlet 3.1
* Maven 3.6.0 & Gradle 5.2.1
* Tomcat 8.5

## 2. 참고사항
~~~
Maven 경로 설정
export M3_HOME=[apache-maven 경로]
export PATH=$PATH:$M3_HOME/bim

Gradle 경로 설정
export GRADLE_HOME=[gradle 경로]
export PATH=$PATH:$GRADLE_HOME/bin

Maven 원격 리포지토리에서 다운로드
$ mvn compile (pom.xml 파일에 추가한 의존을 다운로드)
~~~
