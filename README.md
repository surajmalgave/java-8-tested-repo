# gradle-and-java8

[![Build Status](https://travis-ci.org/butcherless/gradle-and-java8.svg?branch=master)](https://travis-ci.org/butcherless/gradle-and-java8)
[![Build Status](https://semaphoreci.com/api/v1/butcherless/scala/branches/master/badge.svg)](https://semaphoreci.com/butcherless/scala)
[![Coverage Status](https://coveralls.io/repos/github/butcherless/gradle-and-java8/badge.svg?branch=master)](https://coveralls.io/github/butcherless/gradle-and-java8?branch=master)
[![Sputnik](https://sputnik.ci/conf/badge)](https://sputnik.ci/app#/builds/butcherless/gradle-and-java8)


## Research and POCs with:

- Gradle 4.x
- Multimodule application
- Java 8
- Spring Boot 2.0.x
- Springframework 5.0.x
- REST API
- Continuous Integration
- Software testing
- Spock
- Jacoco

## Gradle:

- gradle wrapper --gradle-version 4.7
- ./gradlew bootRun
- ./gradlew bootJar
- java -jar application/build/libs/application-1.0.0-SNAPSHOT.jar
- curl http://localhost:8081/mybank/accounts
- http http://localhost:8081/mybank/accounts
- ./gradlew repository:jacocoTestReport
