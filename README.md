# Spring Boot + Thymeleaf 강의안 (회원가입/로그인 중심)

본 교재는 **회원가입, 로그인, 세션 관리 기능**을 기준으로 진행한다.
그 외 주제(강의 목록/등록/조회 등)는 제외한다.

## 학습 진행
- 교재는 `01.md`부터 `10.md` 순서로 학습한다.
- 각 교시는 이전 교시 결과를 확장하는 방식으로 진행한다.

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
- `01.md` 프로젝트 시작과 흐름 이해
- `02.md` 회원가입 화면/Controller
- `03.md` 로그인 화면/Controller
- `04.md` Service 분리 + 세션
- `05.md` Repository(DB 테이블)
- `06.md` AppException + 전역 예외 처리
- `07.md` 화면 피드백 개선
- `08.md` 표현식 연습 전용 페이지 매핑
- `09.md` 기존 화면 표현식 전환
- `10.md` 통합 점검

## 실습 목표
- 회원가입 요청 데이터를 검증할 수 있다.
- 로그인 요청 흐름을 구현할 수 있다.
- 로그인 성공 시 세션을 생성하고, 로그아웃 시 세션을 종료할 수 있다.
- 예외 발생 시 `AppException`으로 처리할 수 있다.

## 실행
```bash
./gradlew bootRun
```
