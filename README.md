# 🐶 Friendog

## Friendog is a web service that matches you and your dog 
## a friend to take a daily walk together. 

<img src="https://user-images.githubusercontent.com/88166362/144694893-52789e67-866c-4ead-b9a0-f63069c7dfbf.png" width="772" height="400">

[Website of Friendog](https://togaether.shop/) [Service Terminated] </br>
[Video of Friendog](https://www.youtube.com/watch?v=lQUo4EbUrQU)  

<br>

# :family_man_woman_boy_boy: Team Members
- Front-end : [Dawon Kim](https://github.com/DawonEllaKim), [Hyojin Kim](https://github.com/hyojin-k),[Suchang Lee](https://github.com/eternalclash) 
- Back-end : [Eu Jeong Hwang](https://github.com/eujeong-hwang), [Jyung-gyu Tak](https://github.com/tak-codes),[SunHee Heo](https://github.com/SunHeeHeo) 
- Designer : Yeonsu Seo, Sungwon Lee 

<br>

# :bookmark_tabs: Duration
October 25, 2021 - December 3, 2021 (6 weeks)

<br>

# :sparkles: Architecture of the Project
<img width="772" alt="KakaoTalk_Photo_2021-12-04-12-08-16" src="https://user-images.githubusercontent.com/88166362/144694918-ab86d1e8-c61d-461a-92ca-e77a10ffc9cf.png">

<br>

# :hammer_and_wrench: Technologies Used
Technologies|Description
:---|:---:
Node.js | JS Runtime
MySQL | MySQL
Express | Web Framework
Nginx | Proxy Server

<br>

# : : Library Used
|Library|Description|
---|:---:
<img src='https://img.shields.io/badge/express-1.7.9-lightgrey'> | Web Framework
<img src='https://img.shields.io/badge/bcrypt-5.0.1-lightgrey'> | Password-hashing function
<img src='https://img.shields.io/badge/cors-2.8.5-lightgrey'> | Cross-Origin Resource Sharing
<img src='https://img.shields.io/badge/dotenv-10.0.0-lightgrey'>  | Load environment variables
<img src='https://img.shields.io/badge/jsonwebtoken-8.5.1-lightgrey'>  | Verification using Token
<img src='https://img.shields.io/badge/mysql-2.3.2-lightgrey'> | MySQL
<img src='https://img.shields.io/badge/swagger--ui--express-4.1.6-lightgrey'> | API Documentation
<img src='https://img.shields.io/badge/sharp-0.29.3-lightgrey'> | Process Image
<img src='https://img.shields.io/badge/multer-1.4.3-lightgrey'> | File Upload

- 로그인 / 회원가입 / 강아지 정보 등록 
  - 로그인 할 시 JWT 토큰을 발급
  - 회원가입 시 비밀번호의 보안을 위해 bcrypt 모듈 사용

- 메인페이지

  - 현재 날씨 조회
  - 최신 개스타그램 조회
  - 카테고리별 산책 목록 조회

- 산책등록

  - 카카오맵 api를 사용해 제공하는 산책로 선택
  - 날짜, 시간 선택

- 산책가자 (산책목록 조회 페이지)

  - 장소별 산책목록 확인
  - 원하는 산책 신청 및 쪽지하기 기능

- 개스타그램 (강아지 일상 공유 페이지)

  - 최신순, 좋아요 순 정렬
  - 일상 공유하는 페이지 등록
  - 좋아요, 댓글, 쪽지 보내기 기능

- 마이페이지

  - 유저가 등록한 개스타그램, 산책목록 조회
  - 유저 데이터, 강아지 데이터 조회 및 수정
  - 다른 유저 페이지 방문 가능

- 쪽지

  - 받은 쪽지, 산책 신청 알람 기능
  - 받은 산책 신청 수락/거절
  - 쪽지 보내기, 답장하기

<br>

# :writing_hand: Documentation
- [Team Notion](https://togaether.shop/)
- [Front-end github](https://github.com/O-K-O-K-O-K/Front-end)
- [Back-end github](https://github.com/O-K-O-K-O-K/Back_End)
