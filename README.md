# AI(인공지능) 기반 챗봇 맛집 추천 서비스-강릉 맛집 추천 챗봇 '릉이'
## 프로젝트 소개

본 서비스는 인간이 가장 이해하기 쉬운 '대화'라는 형태의 서비스인 챗봇을 활용하여 많은 사람이 사용하는 메신저 앱에서 직접 검색하지 않아도 대화를 통해 강릉 지역의 맛집을 추천한다.  
  
<a href="https://chocochip101.tistory.com/entry/%EA%B0%95%EB%A6%89-%EC%B1%97%EB%B4%87-%EB%A6%89%EC%9D%B4-Images?category=962284">
  <img src="https://user-images.githubusercontent.com/73146678/134644150-0e49b0cd-dd83-416c-8225-c44ea5f6f766.png"  width="200" height="200"/>
  <img src="https://user-images.githubusercontent.com/73146678/134645565-10e7c13a-5382-4bd5-afed-6f916bc29381.png"  width="300" height="200"/>
</a>



## 주요 기능

**-SW**

#### 사용자 대화 모델 Chatbot
 1. 사용자와 대화를 할 수 있는 챗봇 모델을 구현

 2. 사용자가 입력한 발화의 의도(Intent)와 개체(Entity) 인식 후, 사용자가 원하는 답변 파악
 
 3. Back-end 영역에서 답변을 가져와 DialogFlow에서 Line으로 전달하여 Chat bot 서비스를 구현  

 
#### 바로 연결 버튼

 1. 사용자에게 내비게이션 역할을 하여 쉽게 챗봇 사용 가능
 - 대화뿐만 아니라 시각적으로 어떤 키워드로 강릉 맛집을 검색하는지 보여준다. 

 2. 강릉 관련 키워드를 통한 연결이나 webUrl로의 연결의 이동 유도 
 - 

 3. 필요한 데이터나 연결 Url을 Back-End 영역에서 처리해 전달 
 - 


#### 추천 서비스

 1.  
 - 

 2.  
 - 

 3.  
 - 

#### '릉이' 추천 맛집

 1.  


## 구성도
![image](https://user-images.githubusercontent.com/73146678/134649545-315b7e73-6330-48b3-b313-95dcda3967e6.png)

## 주요 기술


■ DialogFlow : Google Machine Learning Engine을 통한 자연어 기반의 사용자 발화 처리

■ Flask : Back-End 영역에서의 통신

■ Naver Open Api : 강릉 맛집 정보 취합

■ Python & Selenium : 취합한 맛집 정보들의 추가 정보(가격, 영업시간 등)의 크롤링

■ MongoDB : 강릉 맛집 정보 저장을 위한 DB

■ AWS(Amazon Web Server) : 클라우드 서버를 활용한 유저와 관리자의 사용성 증가 및 유지보수 배포 효율 증가 


## 역할 분담

| 멘토 | 역할 | Contact |
| ------ | ------ | ------ |
| 서지훈 | 온라인 미팅과 주기적인 TColla, KakaoTalk을 통한 피드백 및 이슈 해결 | ------ |


| 멘티 | 역할 | Contact | 
| ------ | ------ | ------ |
| 권기호 | 프로젝트 관리 총괄 및 정기회의 일정 수립, 요구사항 정의 및 시스템 설계, Back-End 개발| [Github](https://github.com/Chocochip101), [BLOG](https://chocochip101.tistory.com/), [Email](chocochip.dev@gmail.com) |
| 남주연 | ... | ... |
| 이성호 | ... | ... |


