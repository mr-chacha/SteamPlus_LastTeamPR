# Steam Plus 🎮 
오직 스팀게임을 하는 유저들을 위한 스팀전용 실시간 소통 커뮤니티

<br/>

## 사이트주소 🖥 
https://steam-plus-theta.vercel.app/

<br/>

## 프로젝트 실행방법
`npm start`

<br/>

## 페이지소개 ❤️
![224586337-350a3cf1-abc1-464e-acbc-3fe5134789dc](https://user-images.githubusercontent.com/117566375/224879663-9061a4a1-1522-4a4e-aff3-4f965c481a73.png)
![224586342-3c373968-0385-42b4-b380-0cc4d9388ec4](https://user-images.githubusercontent.com/117566375/224879904-3ad81c8c-c964-4752-a3cc-8fa0d4888815.png)

<br/>

## 아키텍처 🤝
![224586419-ba9b63b4-f84f-4805-a45a-227aea379096](https://user-images.githubusercontent.com/117566375/224879939-09870be0-fe5f-4732-87b4-503fcfedcc26.png)

<br/>

## 기술적 의사 결정 🎲
| 사용기술 | 기술 설명 |
| --- | --- |
| recoil | 리코일은 매우 간단한 코드로 상태를 관리할 수 있습니다. 리덕스와 비교해 상태를 업데이트하기 위해 액션 타입, 액션 생성자, 리듀서를 작성할 필요가 없으며, 상태 업데이트 로직을 작성할 때도 상태 객체 자체를 직접 수정할 수 있었습니다. |
| socket.io | Socket.io는 다양한 이벤트를 지원하여 클라이언트에서 서버로 데이터를 전송하고 서버에서 클라이언트로 데이터를 전송할 수 있습니다. 이러한 특징으로 인해, Socket.io는 실시간 채팅기능을 구현하는 데 매우 유용합니다. |
| WebRTC | WebRTC는 브라우저에서 P2P(peer-to-peer) 통신을 가능하게 하는 기술입니다. 이 기술은 별도 플러그인 없 브라우저 내장 기능으로 제공되며, 브라우저 간에 영상 및 음성 데이터를 실시간으로 전송할 수 있습니다. |
| json-server, glitch | db.json 파일을 사용하면 데이터베이스 서버를 구축하지 않아도 되고 Glitch에서는 개발자가 손쉽게 프로젝트를 공유하고, 팀원과 함께 작업할 수 있기 때문에 개발 프로세스가 편리해집니다. |

<br/>

# 역할 및 기능 😃
## 메인페이지  
- Steam API를 이용하여 게임의 정보(게임동영상, 게임이미지, 게임타이틀 등)를 메인페이지에 출력
<img width="1440" alt="메인1" src="https://user-images.githubusercontent.com/117566375/224887543-dac3340d-5bf8-4197-a77c-4c21b11cd87e.png">

<br/>

## 로그인
- Steam API를 이용하여 스팀아이디와 연동하여 별도의 회원가입 없이 서비스 로그인기능 구현
- Steam API를 이용하여 프로필 정보(프로필닉네임, 프로필이미지, 최근활동게임)를 출력
- 사용자의 상태(온라인 ,오프라인)조절 및 로그아웃 기능 구현
 <img width="1440" alt="로그인3" src="https://user-images.githubusercontent.com/117566375/224887573-cb126b53-d575-4d92-b7d6-9269f0174088.png">

<br/>

## 커뮤니티
- 게시글 작성
- 게시글 수정
- 게시글 삭제
- 게시글 검색
- 페이지네이션
- 카테고리 설정 및 실시간 조회수 및 작성시간 등 기능 구현
 <img width="1440" alt="커뮤니티 5" src="https://user-images.githubusercontent.com/117566375/224887607-31298859-9f8f-460d-863a-eb153445e223.png">

<br/>
## 트러블 슈팅 🔧 

<br/>
