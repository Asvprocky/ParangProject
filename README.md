# 파랑 프로젝트 (Parang Project)

## 📌 프로젝트 개요
여행 일정 관리 및 커뮤니티 플랫폼 개발  
- 사용자 간 여행 일정 공유  
- 일정 캘린더, 커뮤니티, 댓글 기능 제공  
- AWS 기반 서비스 배포

---

## 🔧 사용 기술

### ✅ Backend
- **Spring Boot 2.7.2**
- Spring Data JPA
- MyBatis
- Spring Security (JWT 기반 인증)
- Thymeleaf (서버사이드 렌더링)
- MySQL
- AWS 연동 (Spring Cloud AWS)
- 이메일 발송 기능 (Spring Boot Mail)
- Lombok, Devtools

### ✅ Frontend
- **React 18**
- MUI (Material-UI)
- Styled-components, Emotion
- MobX 상태관리
- React Router
- ApexCharts, Recharts (차트 시각화)
- Calendar, Lottie, Tagify, Bootstrap
- AWS S3 이미지 업로드
- Axios (비동기 통신)
- JWT Decode, UUID

### ✅ 기타
- Java 17
- Gradle
- Jest, React Testing Library

---

## 🛠️ 담당 역할 및 개발 범위
- 팀 프로젝트로 진행 (본인: 백엔드 프론트엔드 개발)
- Spring Boot 기반 REST API 개발
- JWT 로그인·회원가입·인증 구현
- MyBatis & JPA를 활용한 DB 설계
- AWS S3 이미지 업로드 기능 개발
- 이메일 인증 기능 및 보안 설정
- 프론트엔드(React)는 팀원과 협업 진행

---

## 📂 프로젝트 구조
> 전체 소스코드는 각 폴더 내 확인 가능  
> - `/backend` : Spring Boot 프로젝트  
> - `/frontend` : React 프로젝트  

---

## 🚀 실행 방법

### Backend
```bash
./gradlew build
java -jar build/libs/*.jar
