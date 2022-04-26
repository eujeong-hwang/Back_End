# 🐶 Friendog

### Have you ever felt lonely when you were walking your dog?
### Friendog is a web service that matches you and your dog a friend to take a daily walk together. 
### Make a friend using Friendog, and share everyday moments with your new walking buddies !

<img src="https://user-images.githubusercontent.com/88166362/144694893-52789e67-866c-4ead-b9a0-f63069c7dfbf.png" width="772" height="400">

[Website of Friendog](https://togaether.shop/) [Service Terminated] </br>
[Video of Friendog](https://www.youtube.com/watch?v=lQUo4EbUrQU)  

<br>

# :family_man_woman_boy_boy: Team Members
- Front-end : [Dawon Kim](https://github.com/DawonEllaKim), [Hyojin Kim](https://github.com/hyojin-k), [Suchang Lee](https://github.com/eternalclash) 
- Back-end : [Eu Jeong Hwang](https://github.com/eujeong-hwang), [Jyung-gyu Tak](https://github.com/tak-codes), [SunHee Heo](https://github.com/SunHeeHeo) 
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

<br>

# :round_pushpin: Main Function

- LogIn / Sign Up / Dog Information

  - Issued Json Web Token whenever the users Logged In
  - Used bcrypt module to safely store the passwords when users Signed Up.

- Main Page

  - View current weather
  - View recent Dogstagram 
  - View list of available walking appointments by each cateogry

- Post walking appointments

  - Used Kakao Map API to make the user pick the trails they would like to walk their dogs to.
  - Users can pick the date and the time.

- View Full List of walking appointments Page

  - View walking appointments by its location
  - Request to go on a walk to the user
  - Send a message to the user of the post

- Dogstagram (Page where you can share your daily moments with your dog)

  - Sorted by Dogstagram's recent post
  - Sorted by Likes of the Dogstagram post
  - Post and share pictures of the daily moments with the user's dog
  - Like, Comment, Message function

- MyPage

  - View dogstagram, walking appointment posts the user posted
  - View and Update user information, dog information
  - View other user's MyPage

- Message

  - Accept/Decline the walking appointment request from other users
  - Send/Answer Messages

<br>

# :writing_hand: Documentation
- [Team Notion](https://togaether.shop/)
- [Front-end github](https://github.com/O-K-O-K-O-K/Front-end)
- [Back-end github](https://github.com/O-K-O-K-O-K/Back_End)
