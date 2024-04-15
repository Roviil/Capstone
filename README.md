# 목차

[0. 개요 및 목적](https://github.com/malgumi/capstone_all?tab=readme-ov-file#1-%EA%B0%9C%EB%B0%9C%ED%99%98%EA%B2%BD-%EC%84%A4%EC%B9%98-%EA%B0%80%EC%9D%B4%EB%93%9C%EB%9D%BC%EC%9D%B8)

[1. 개발환경 설치 가이드라인](https://github.com/malgumi/capstone_all?tab=readme-ov-file#1-%EA%B0%9C%EB%B0%9C%ED%99%98%EA%B2%BD-%EC%84%A4%EC%B9%98-%EA%B0%80%EC%9D%B4%EB%93%9C%EB%9D%BC%EC%9D%B8
)

[2. 개발환경](https://github.com/malgumi/capstone_all?tab=readme-ov-file#2-%EA%B0%9C%EB%B0%9C%ED%99%98%EA%B2%BD)

[3. 설계](https://github.com/malgumi/capstone_all?tab=readme-ov-file#3-%EC%84%A4%EA%B3%84)

[4. 주요 기능](https://github.com/malgumi/capstone_all?tab=readme-ov-file#4-%EC%A3%BC%EC%9A%94-%EA%B8%B0%EB%8A%A5)

[5. TEST용 APK파일](https://github.com/malgumi/capstone_all?tab=readme-ov-file#5-test%EC%9A%A9-apk-%ED%8C%8C%EC%9D%BC)


## 0. 개요 및 목적
2023년도 캡스톤 디자인 과목 수강


## 1. 개발환경 설치 가이드라인
[노션](https://www.notion.so/b15dccdb33784994ac92bbee145567cd)


## 2. 개발환경
프론트 엔드:<br>
  플러터-다트<br><br>
백엔드:<br>
  Node.js / Express<br><br>
서버:<br>
  AWS(API서버) / oracle cloud(데이터베이스)<br><br>
개발툴:<br>
  인텔리제이 / VSCode / FileZilla / DataGrip / Postman<br> <br>
협업툴:<br>
  슬랙 / 메터모스트 / Git<br><br>

## 3. 설계<br>

### 간트차트<br>
![image](https://github.com/malgumi/capstone_all/assets/26024730/e654d11a-4958-47b5-be7d-e2a0b41497ad)
<br>

### Usecase<br>
![image](https://github.com/malgumi/capstone_all/assets/26024730/4b7fccd7-37b1-4cfe-96f5-b59d1e86ab29)
<br><br><br>

### 화면 구조 설계<br>
![image](https://github.com/malgumi/capstone_all/assets/26024730/4181a35c-d564-43cb-afff-d4b997ffac9e)
<br><br><br>
### 메뉴 구조 설계<br>
![image](https://github.com/malgumi/capstone_all/assets/26024730/77ce4fb9-3bc5-4ea7-a52e-e48fc4be946c)
<br><br><br>
### DB설계<br>
![image](https://github.com/malgumi/capstone_all/assets/26024730/9138818c-0086-4744-809a-b25667995501)
<br><br><br>
## 4. 주요 기능
### 회원 관리
- 회원가입
- 로그인, 로그아웃
- 이메일 인증을 통한 개인정보 변경
- 개인 프로필 기능
- 개인정보 암호화
### 공지사항
- 공지 등록 알림 기능
- 학년 별 공지사항 열람
- 등급에 따른 글 작성 권한
### 관리자
- 관리자 접속 시 전용 페이지 표시
- 게시판 관리 권한
- 신고 글 처리 기능
- 교수 회원 정보 추가
### 게시판
- 글 작성, 조회, 수정, 삭제
- 댓글 작성, 조회, 수정, 삭제
- 구인구직 게시판 -> 개인프로필 표시
- 자유 게시판 -> 익명, 신고기능
- 공지글 상단 고정
- 자신의 글 댓글 시 알림
- 게시판 검색
### API
![image](https://github.com/malgumi/capstone_all/assets/26024730/85a19187-abbc-42c9-9778-2d7123af683c)




## 5. TEST용 APK 파일
테스트용 파일입니다. 각자 휴대폰에 다운 받아서 직접 해보시면 됩니다.<br>
ios유저는,, 앱스토어에 등록을 하는 방법밖에 없어서 현재 테스트 해 볼 길이 없습니다.<br>
테스트 도중 찾으신 버그는 각 기능 담당 팀에게 알려주시면 감사하겠습니다.<br>

https://drive.google.com/file/d/1v-Qp42VVZw5EBWJ5T2DA-5dtDfDcBIfm/view?usp=sharing
현재 서버 운용하지 않으므로 사용 불가
