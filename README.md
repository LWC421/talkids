# README

<div align="center">
<img src="https://github.com/LWC421/talkids/assets/61939201/b19f1d34-5ae3-4bc7-a330-631ec1da45e8" width="600px" />
</div>

<br>  

## 📰 프로젝트 소개

**TALKIDS: 언어교류를 위한 온라인 플랫폼**

TALKIDS는 언어 교류를 촉진하고 기존의 제약조건을 극복하는 웹 플랫폼입니다. 이 플랫폼은 언어 교환에 참여하는 사람들에게 진입 장벽을 낮추고, 시간과 공간의 제약 없이 더 많은 기회를 제공합니다. 선생님과 학생들은 간편하게 언어 교류 파트너를 찾을 수 있으며, 다양한 학급 간의 매칭도 가능합니다.

개발 기간 : `23.07.17 ~ 23.08.18`

<br>  

## 💡 주요 기능

### 화상 전화

- 사용자 간의 화상 전화 (1 : 1 & 1 : N)
    - WebRTC API 중 하나인 RTCPeerConnection 기반의 p2p 방식으로 구현
    

### Speech to Text & 번역

- 사용자의 음성을 실시간으로 텍스트로 변환
    - Web Speech API 기반의 react-speech-recognition 라이브러리 활용
- 텍스트로 변환된 음성과 채팅에 대한 번역 수행
    - 사용자 음성이 특정 주기 동안 입력되지 않을 경우 이전까지의 음성을 하나의 문장으로 판단하여 번역, 실시간성 및 속도 개선
    - 채팅 측면의 번역 버튼 클릭 시 해당 채팅의 번역 결과를 하단에 출력
        - 번역한 채팅은 북마크에 추가하여 추후 찾아볼 수 있도록 구현
    

### DM

- 사용자 간의 채팅 기능
    - WebSocket을 이용하여 실시간성 보장
    - 채팅방에 접속 중이지 않을 때에도 해당 채팅방에 온 메시지를 확인 할 수 있도록 구현

### 매칭

- 일정 등록을 통한 매칭 관리
- 매칭 요청과 수락 및 거절을 통해 매칭 처리

### 메인 페이지

- React-three-fiber를 이용하여 사용자의 경험치를 시각화, 흥미로운 3D 요소 적용.

<br>  

## 💻 실행 화면

|그룹페이지|로그인 후 메인페이지|
| --- | --- |
|<img src="https://github.com/LWC421/talkids/assets/61939201/d4013ca5-08e2-4565-a4e0-3af03758a9b9" width="800px"/>|<img src="https://github.com/LWC421/talkids/assets/61939201/c074534f-41f7-4d9c-a759-9eccebd4b0b1" width="800px"/>|


|메인화면 레벨1|메인화면 레벨2|
| --- | --- |
|<img src="https://github.com/LWC421/talkids/assets/61939201/b8ba0165-adbd-4618-a091-12b19e996d02" width="800px"/>|<img src="https://github.com/LWC421/talkids/assets/61939201/52e154fd-ff5b-4cab-8dbc-adf08dbfdd40" width="800px"/>|

|메인화면 레벨3|번역 및 사전|
| --- | --- |
|<img src="https://github.com/LWC421/talkids/assets/61939201/1897c3b3-27c8-4a9c-b4f9-567ca8c5e9eb" width="800px"/>|<img src="https://github.com/LWC421/talkids/assets/61939201/647e7fe5-7274-4ae4-8dd0-e4799d97686b" width="800px"/>|


|팔로우 기능|학생 매칭 기능|
| --- | --- |
|<img src="https://github.com/LWC421/talkids/assets/61939201/42e3a83d-51af-4a7b-a459-2e9de4ffbddb" width="800px"/>|<img src="https://github.com/LWC421/talkids/assets/61939201/041c86f4-d400-45b0-b258-8cdb2f658d09" width="800px"/>|

[화상회의기능](https://youtu.be/snwouXY9Zlk)

<br>  


## ⚙️ 기술 스택

### Frontend

<div style="display:flex;align-items:row">
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white">
<img src="https://img.shields.io/badge/redux-764ABC?style=for-the-badge&logo=redux&logoColor=white">
</div>

### **Backend**

<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
<img src="https://img.shields.io/badge/jpa-6DB33F?style=for-the-badge&logo=javapersistenceapi&logoColor=white">
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/springsecurity-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white">
<img src="https://img.shields.io/badge/socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white">

### **Infra**

<img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
<img src="https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">
<img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">


### **Cooperation**

<img src="https://img.shields.io/badge/gitlab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white">
<img src="https://img.shields.io/badge/jira-0052CC?style=for-the-badge&logo=jira&logoColor=white">
<img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
<img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"> <br>  


<br>  

  
## 📊 ERD

<img src="https://github.com/LWC421/talkids/assets/61939201/1ad3da3e-21c6-4fd9-961d-b93d82d722d1" width="700px"/>  <br>  

<br>  
 
  
## 📄 아키텍처 설계도

<img src="https://github.com/LWC421/talkids/assets/61939201/06ee5649-6e94-410a-a449-0438cb06b15a" width="700px"/>  <br>  

<br>  



## ✨ 팀원 소개
<table>
 <tr align="center">
   <th colspan="3">Front-End</th>
   <th colspan="2">Back-End</th>
 </tr>
 <tr align = "center">
  <td>
   김선영
  </td>
  <td>
   박종욱
  </td>
  <td>
   서동현
  </td>
    <td>
   유영서
  </td>
    <td>
   이우철
  </td>
 </tr>
</table>
