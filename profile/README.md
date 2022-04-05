⌨️ Tying (타잉)
=============
## 🙌 Introduce Tying
>“영어타자, 빠르지 않아도 괜찮아.”
<br>타잉은 컴퓨터 기반 영어 시험 준비를 위한 영타 연습 서비스입니다.
* * *

## 📣 Project
### 📆 Project Timeline
- 총 기간: 2022/02/25 ~ 2022/04/08
- 배포: 2022/03/29

### 👨‍💻👩‍💻 The Team
|Name|GitHub/Contact|Position|
|:---:|:---:|:---:|
|정현수🔰|https://github.com/ricky0813|Frontend|
|윤혜진|https://github.com/hyejin4169|Frontend|
|김기덕|https://github.com/nikemaniaa1987|Frontend|
|용주성🔰|https://github.com/Tacocat3|Backend|
|김민정|https://github.com/minkimhere|Backend|
|이노규|https://github.com/nklee6300|Backend|
|전소연|soy990417@naver.com|Design|
|임승현|dkch7@naver.com|Design|

### 📌 Links
- [Website](https://ty-ing.com/)
- 발표영상: 준비 중..
- [Organization GitHub](https://github.com/ty-ing)
- [Backend Repository](https://github.com/ty-ing/ty-ing_BE)
- [Frontend Repository](https://github.com/ty-ing/ty-ing_FE)
- [Notion Page](https://bit.ly/3K9RDgh)

* * *

## 💎 Core Features
- `1`
  - 1
- `2`
  - 2
- `3`
  - 3

* * *

## 🛠 Tech Stack & Platform
### **Frontend**
<p>
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/redux-764ABC?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/axios-007CE2?style=for-the-badge&logo=axios&logoColor=white">
<img src="https://img.shields.io/badge/reactrouterdom-CA4245?style=for-the-badge&logo=reactrouterdom&logoColor=white">
</br>
<img src="https://img.shields.io/badge/styledcomponents-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white">
<img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
<img src="https://img.shields.io/badge/amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"> 
<img src="https://img.shields.io/badge/route53-F7A81B?style=for-the-badge&logo=route53&logoColor=white">
<img src="https://img.shields.io/badge/cloudfront-04ACE6?style=for-the-badge&logo=cloudfront&logoColor=white">
<br>
</p>

### **Backend**
<p>
<img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/mongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white">  
<img src="https://img.shields.io/badge/AWS Ec2-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"> 
<img src="https://img.shields.io/badge/passport-33D875?style=for-the-badge&logo=passport&logoColor=white">
<br>
</p>

### **Design**
<p>
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white"/>
<img src="https://img.shields.io/badge/Adobe Photoshop-31A8FF?style=for-the-badge&logo=Adobe Photoshop&logoColor=white"/>
</p>

### **Tools**
<p>
<img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=Visual Studio Code&logoColor=white"/>
<img src="https://img.shields.io/badge/googleanalytics-E37400?style=for-the-badge&logo=googleanalytics&logoColor=white">
<img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"/>
<img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=github&logoColor=white">
<br>
</p>

* * *

## 📖 More info
<details>
<summary>서비스 아키텍쳐</summary>
- 준비 중..
</details>
<details>
<summary>API 명세서</summary>
<div markdown="1">

|Fuction|Method|URL|
|:---:|:---:|:---:|
|회원가입|POST|/api/signup|
|아이디 중복검사|POST|/api/signup/idCheck|
|닉네임 중복검사|POST|/api/signup/nicknameCheck|
|로그인|POST|/api/login|
|카카오 로그인 서버 인증|GET|/auth/kakao|
|카카오 로그인 토큰 발급|GET|/api/kakao/callback?code=${code}|
|로그인 여부 확인|GET|/api/auth|
|회원정보 변경(일반로그인&카카오)|PUT|/api/info|
|마이페이지(통계)|GET|/api/mypage/statistic|
|마이페이지(인증서)|GET|/api/mypage/certificate|
|마이페이지(인증서 상세보기)|GET|/api/mypage/certificate/:certificateId/:scriptId|
|키워드 검색|GET|/api/script/search?page=${number}&targetWord=${word}|
|스크립트 필터로 불러오기|GET|api/script/list?scriptCategory=${category}&scriptTopic=${topic}&page=${number}&myscript=ok|
|카테고리 선택 후 랜덤 타이핑 시작|GET|/api/script/:scriptType/:scriptCategory/|
|스크립트|GET|/api/detail/:scriptId|
|나만의 스크립트 등록 여부 조회|GET|/api/myScript/:scriptId|
|나만의 스크립트 등록|POST|/api/myScript/:scriptId|
|나만의 스크립트 삭제|DELETE|/api/myScript/:scriptId|
|결과 저장하기|POST|/api/studyrecord|
|단어 뜻 작성하기|POST|/opendict/:scriptId/:word|
|단어 뜻 불러오기(게스트용)|GET|/opendict/guest/:scriptId/:word|
|단어 뜻 불러오기(로그인사용자)|GET|/opendict/user/:scriptId/:word|
|단어 뜻 수정하기(본인이 작성한 것만 수정가능)|PUT|/opendict/:scriptId/:word/:wordId|
|단어 뜻 삭제하기(본인이 작성한 것만 삭제가능)|DELETE|/opendict/:scriptId/:wordId|
|좋아요 누르기|PUT|/likeDislike/likeUp/:scriptId/:wordId|
|좋아요 취소|PUT|/likeDislike/likeDown/:scriptId/:wordId|
|좋아요 조회|GET|/likeDislike/like/:scriptId/:wordId|
|싫어요 누르기|PUT|/likeDislike/dislikeUp/:scriptId/:wordId|
|싫어요 취소|PUT|/likeDislike/dislikeDown/:scriptId/:wordId|
|싫어요 조회|GET|/likeDislike/dislike/:scriptId/:wordId|
|단어 저장하기|POST|/mydict/:scriptId/:word|
|단어 조회하기(최신순 4개만)|GET|/mydict/some|
|단어 조회하기(전체 조회)|GET|/mydict/all|
|단어 삭제하기|DELETE|/mydict/:scriptId/:word|
|스크립트 저장하기|POST|/api/script|
  
</div>
</details>

* * *

## 🔥 Trouble Shooting
<details>
<summary>Frontend</summary>
- 준비 중..
</details>
<details>
<summary>Backend</summary>
- 준비 중..
</details>
