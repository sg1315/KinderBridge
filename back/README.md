# 백엔드 (Spring Boot)

## 프로젝트 구조
- Spring Boot 기반 REST API 서버
- JWT를 활용한 인증/인가 구현
- JPA를 활용한 객체지향적인 엔티티 설계 및 데이터베이스 연동 구현

## 주요 라이브러리
- Spring Boot
- Spring Security
- Spring Data JPA
- Spring WebSocket
- Gradle
- JWT (JSON Web Token)
- AWS S3
- MySQL

## 실행 방법

```bash
cd back
./gradlew bootRun
```

## API 명세

| 메서드 | 엔드포인트        | 설명           |
| ------ | ---------------- | -------------- |
| POST   | /api/auth/login  | 로그인         |
| POST   | /api/auth/signup | 회원가입       |
| GET    | /api/user/me     | 내 정보 조회   |

## 환경 변수
- `application.yml`에서 DB 및 JWT 시크릿 키 설정 
