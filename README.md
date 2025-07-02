# 파랑 프로젝트 (Parang Project)

## 📌 프로젝트 개요
**낚시를 즐기는 사람들을 위한 해양 정보 및 커뮤니티 플랫폼**  
- 해양기상청 API를 활용해 파고, 금어기, 히트확률 정보 제공  
- 사용자 간 SNS 기능 을 통한 실시간 소통 및 커뮤니티 형성  
- 해양 안전 정보와 낚시 관련 커뮤니케이션을 통합 제공
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

 ### ✅ 주요 외부 API
- **카카오맵 API**: 위치 및 지도 서비스  
- **기상청 단기 예보 API**: 해양 날씨 및 단기 기상 정보  
- **국립해양조사원 API**: 파고, 조석, 해양 데이터 제공  
- **해양수산부 Open API**: 금어기 및 해양 관련 공공 데이터  
- **Geocode API**: 좌표 변환 및 위치 정보 활용  

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
