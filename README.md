# Spring Boot + Thymeleaf 강의안 (회원가입/로그인 중심)

본 교재는 **회원가입, 로그인, 세션 관리 기능**을 기준으로 진행한다.
그 외 주제(강의 목록/등록/조회 등)는 제외한다.

## 학습 범위
1. 프로젝트 실행 환경 준비
2. 회원가입 화면 구성 (`/signup`)
3. 로그인 화면 구성 (`/login`)
4. Controller 매핑 (GET/POST)
5. Service 검증 로직 기초
6. Repository 데이터 저장/조회 기초
7. 세션 기반 로그인 상태 관리
8. 예외 처리 (`AppException`) 적용
9. 통합 실행 점검

## URL 기준
- `GET /signup` : 회원가입 화면
- `POST /signup` : 회원가입 처리
- `GET /login` : 로그인 화면
- `POST /login` : 로그인 처리

## 템플릿 기준
- `templates/signup.html`
- `templates/login.html`
- `templates/error/app-error.html` (예외 안내)

## 실습 목표
- 회원가입 요청 데이터를 검증할 수 있다.
- 로그인 요청 흐름을 구현할 수 있다.
- 로그인 성공 시 세션을 생성하고, 로그아웃 시 세션을 종료할 수 있다.
- 예외 발생 시 `AppException`으로 처리할 수 있다.

## 실행
```bash
./gradlew bootRun
```
