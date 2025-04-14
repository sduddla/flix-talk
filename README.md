## FlixTalk
- HTML/CSS 학습 목적
- Figma로 UI 디자인 설계 후 코드 구현  
- 노마드코더 코코아 클론 강의 참고 (디자인과 구성은 직접 기획)  
- 넷플릭스와 카카오톡의 UI 스타일 참고

<br>

## 구성
#### [Login] 로그인 화면
- 이메일 또는 휴대폰 번호를 입력하는 로그인 폼 UI
- 로그인 버튼 클릭 시 UI 변화
  
#### [Programs] 프로그램 목록 화면
- 카카오톡의 친구 목록 스타일로 넷플릭스 프로그램들을 리스트 형태로 표시
- 프로그램 포스터와 제목 함께 보여주는 UI

#### [Chats] 프로그램별 채팅 화면
- 선택한 프로그램별로 참여 가능한 채팅방 목록을 표시
- 사용자의 프로그램 관련 질문에 챗봇이 정보를 대화 형식으로 응답하는 흐름을 구상

#### [Find] 콘텐츠 탐색 화면
- 드라마, 영화, 게임 카테고리를 클릭 형식으로 탐색 가능
- 카카오톡 오픈채팅과 유사한 채팅 UI 제공

#### [More] 사용자 프로필 및 저장한 콘텐츠, 공개될 콘텐츠, 인기 콘텐츠
- 사용자 프로필 사진과 닉네임을 보여주는 UI
- 저장한 콘텐츠, 공개될 콘텐츠, 인기 콘텐츠로 나뉘는 카테고리 UI를 구성

<br>

## UI
<img width="1260" alt="ui" src="https://github.com/user-attachments/assets/631e8daf-dcb0-43f1-8b38-482e4dc6e5e9" />

<br>

## 코드 구현
| Splash Screen | Login | Programs | Chats |
| :-----------: | :---: | :------: | :---: |
| <img width="205" height="350" alt="splash-screen" src="https://github.com/user-attachments/assets/468e4100-f9bb-4df9-9457-4e487c098c0d" /> | <img width="205" height="350" alt="login" src="https://github.com/user-attachments/assets/9fe151fa-eedf-43e0-b30d-fc971fba5a7f" /> | <img width="205" height="350" alt="programs" src="https://github.com/user-attachments/assets/f0ff49e0-f0cc-4682-aaf2-1bbc6f9dbe1a" /> | <img width="205" height="350" alt="chats" src="https://github.com/user-attachments/assets/df6cadc3-396f-48fa-9b41-f96538ece7e2" /> 

| 1:1 Chat Room | Find | More | Window Size |
| :-----------: | :--: | :--: | :---------: |
| <img width="205" height="350" alt="chat-room" src="https://github.com/user-attachments/assets/341ce28e-61d9-4058-a79d-852b953cd194" /> | <img width="205" height="350" alt="find" src="https://github.com/user-attachments/assets/6cbf14bf-f60f-4252-aa3c-2c64faddfc8d" /> | <img width="205" height="350" alt="more" src="https://github.com/user-attachments/assets/bd1c66c3-b2d7-4cdd-9ad7-7f02f8e3626f" /> | <img width="205" height="350" alt="window" src="https://github.com/user-attachments/assets/7cd03a00-b92b-4c6d-9948-d73ad579483a" />

<br>

- 브라우저 너비가 650px 초과하면, '화면 크기를 줄여주세요' 안내 메시지 표시
- 내용 초과될 경우 스크롤 자동 생성
- CSS 애니메이션 구현을 통해 UI에 동적 요소 추가

<br>

## 이미지 정보(Image Info)
- 드라마 포스터: Figma에서 배경색과 텍스트를 활용하여 간단히 제작
- 스플래시 화면 로고: Figma에서 직접 제작하여 활용
- 사용자 프로필 & 넷플릭스 로고: Unsplash에서 제공하는 무료 이미지 사용
