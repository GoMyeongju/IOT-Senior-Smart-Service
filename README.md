#### IOT-Senior-Smart-Service

# Smart Senior Welfare System

## 프로젝트 목표
> 본 프로젝트는 초고령 사회와 노인 단독세대 증가로 인한 독거노인 인구 증가, 부족한 노인복지 관련 인력 해결을 위해 최근 많이 사용되는 스마트 산업 기술(음성인식, 데이터 분석, 웹 애플리케이션 서비스 등)과 IOT 기술을 융합하여 거주지 내의 독거노인을 원격으로 확인하고 생활방식 분석을 통해 위험요소를 사전에 제거할 수 있도록 하는 스마트 실버 케어 시스템(이하 ‘노인 종합 복지 시스템’)을 목표로 한다.

---
## 프로젝트 주요 구현 사항
- AWS의 EC2를 활용한 공공서버를 구축
- RDS를 통한 데이터베이스(MYSQL) 서버를 구축
- 서버와의 통신을 위한 HTTP, MQTT 통신 방식을 구현
- 라즈베리파이4B를 통한 센서 데이터 전달을 구현
- 전달받은 데이터를 웹 프레임워크 Flask를 활용하여 DB 내에 저장
- DB 내에 저장된 데이터를 웹 페이지에 표시
- 동적 웹 환경 제공을 위한 부트스트랩 프레임워크 사용
- 네이버 음성 API를 활용한 STT-TTS 기능을 사용

--- 
## 시스템 아키텍처
<img width="1002" alt="architecture" src="https://user-images.githubusercontent.com/51225037/105514805-48af2180-5d17-11eb-88fe-691401106060.png">

---
## 주요 화면
### 메인 화면
> ![main](https://user-images.githubusercontent.com/51225037/105514820-4cdb3f00-5d17-11eb-848a-d43e7f95d0e8.png)

### 노인 상세 조회
> ![detail](https://user-images.githubusercontent.com/51225037/105514824-4d73d580-5d17-11eb-9ccd-06a1798d2ce6.png)

### 신규 등록 화면
> ![add](https://user-images.githubusercontent.com/51225037/105514827-4e0c6c00-5d17-11eb-995f-4cce28ace29d.png)
