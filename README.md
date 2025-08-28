# 📝 Java Study: 코드 개선 및 테스트 코드 작성

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Java Version](https://img.shields.io/badge/Java-17-blue)](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html)  
[![Spring Boot](https://img.shields.io/badge/Spring-Boot-6DB33F?logo=spring)](https://spring.io/projects/spring-boot)

---

## 프로젝트 소개
**Java 코드 개선과 테스트 코드 작성**을 학습하는 연습용 프로젝트입니다.  
JPA 및 Spring 기본 구조 학습. 테스트 코드 작성을 통한 **코드 안정성과 유지보수성 확보**를 목표로 합니다.

📌 핵심 학습:
- Given-When-Then 패턴을 적용한 테스트 코드 작성
- 오류 메시지 읽기
- 오류를 패턴화 하여 test 진행
---

## 학습 내용

### Lv 1: ArgumentResolver
**학습 요소**
- `HandlerMethodArgumentResolver` 사용법
- `@Auth` 커스텀 어노테이션
- `WebMvcConfigurer`에서 `Resolver` 등록 방법
- `HttpServletRequest`에서 `setAttribute/getAttribute` 사용용

## Lv 2. [코드 개선]  
---
### Lv 2-1. [코드 개선]  Early Return
**학습 요소**
- Early Return 패턴
- if문 조건 판단 순서
- 불필요한 연산 최소화

### Lv 2-2. [코드 개선 ] 리팩토링 퀴즈 - 불필요한 if-else 피하기
**학습 요소**
- HttpStatus 확인
- 배열 null/empty 체크
  
### Lv 2-3. [코드 개선] 코드 개선 퀴즈 - Validation
**학습 요소**
- `@Valid` 사용법
- `@Size`, `@Pattern` 등 Bean Validation 어노테이션
- DTO에서 Validation 처리 후 컨트롤러에서 `@Valid`로 적용

### Lv 3. N+1 문제
**학습 요소**
- @EntityGraph 사용법
- N+1 문제 개념
- Repository 쿼리 최적화

## Lv 4 [테스트코드 연습]
### Lv 4-1. [테스트코드 연습] 예상대로 성공하는지
**학습 요소**
- JUnit 테스트 구조
- Given-When-Then 패턴
- PasswordEncoder.matches(raw, encoded) 순서 확인

### Lv 4-2. [테스트코드 연습] 예상대로 예외처리 하는지.
**학습 요소**
- `InvalidRequestException`
-  `Optional`
-  `NPE(NullPointerException)` 가능성 체크

---

## Git Commit 컨벤션
- 단계별 레벨 표시

