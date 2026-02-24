# Spring Boot + Thymeleaf 강의안 (회원가입/로그인 중심)

본 교재는 **회원가입, 로그인, 세션 관리 기능**을 기준으로 진행한다.
그 외 주제(강의 목록/등록/조회 등)는 제외한다.

## 학습 범위
1. 프로젝트 실행 환경 준비
2. 회원가입 화면 구성 (`/signup`)
3. 로그인 화면 구성 (`/login`)
4. Service 계층 분리 + 세션 저장/종료
5. Repository 데이터 저장/조회 기초
6. 예외 처리 (`AppException`) 적용
7. 화면 피드백 개선
8. 표현식 연습 전용 페이지 매핑
9. 기존 화면을 표현식 기반으로 전환
10. 통합 실행 점검

## URL 기준
- `GET /signup` : 회원가입 화면
- `POST /signup` : 회원가입 처리
- `GET /login` : 로그인 화면
- `POST /login` : 로그인 처리
- `GET /logout` : 로그아웃(세션 종료)

## 템플릿 기준
- `templates/signup.html`
- `templates/login.html`
- `templates/error/app-error.html` (예외 안내)

## 교재 파일
- `1.md` 프로젝트 시작과 흐름 이해
- `2.md` 회원가입 화면/Controller
- `3.md` 로그인 화면/Controller
- `4.md` Service 분리 + 세션
- `5.md` Repository(DB 테이블)
- `6.md` AppException + 전역 예외 처리
- `7.md` 화면 피드백 개선
- `8.md` 표현식 연습 전용 페이지 매핑
- `9.md` 기존 화면 표현식 전환
- `10.md` 통합 점검

## 실습 목표
- 회원가입 요청 데이터를 검증할 수 있다.
- 로그인 요청 흐름을 구현할 수 있다.
- 로그인 성공 시 세션을 생성하고, 로그아웃 시 세션을 종료할 수 있다.
- 예외 발생 시 `AppException`으로 처리할 수 있다.

## 표현식 적용 원칙
- `th:if`, `th:text`는 초반 교시(3교시 이후)부터 적극 사용한다.
- 8교시는 표현식 전용 연습, 9교시는 표현식 확장/정리 단계로 운영한다.

## 실행
```bash
./gradlew bootRun
```
