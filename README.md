# donggeun's blog (2022.01.24 ~ ing)

동근이의 블로그
<br><br>
## [블로그 접속하기](https://blog.donggeun.co.kr)

<br><br>
# Git Repo
## [Frontend GIT](https://github.com/tjrehdrms123/blog-client)
## [Backend GIT](https://github.com/tjrehdrms123/blog-server)
## [Server GIT](https://github.com/tjrehdrms123/blog-cloudserver)
<br><br>

# 📖 목차 
 - [소개](#소개) 
 - [개발 환경](#개발-환경)
 - [사용 기술](#사용-기술)
 - [아키텍처](#시스템-아키텍처) 
 - [E-R 다이어그램](#e-r-다이어그램)
 - [Api 명세서](#-api-명세서)
 - [릴리즈 노트](#-MP-릴리즈-노트)
 - [화면 구성](#화면-구성)

<br><br>
## 📃소개
**donggeun's blog**는 개인 블로그입니다
<br>
노션에 있는 데이터를 개인 블로그로 쓰고 싶어서 만들었습니다


## 개발 환경

![window](https://img.shields.io/badge/windows-%230078D6.svg?&style=flat&logo=windows&logoColor=white")
![vscode](https://img.shields.io/badge/vscode-blue?style=flat&logo=VisualStudioCode)
![github](https://img.shields.io/badge/github-606060?style=fat&logo=github)
![MongoCompass](https://img.shields.io/badge/-MongoCompass-green)

 - Window 
 - Visual Studio Code
 - GitHub
 - DBeaver

## 사용 기술 

![EC2](https://img.shields.io/badge/AWS-ec2-FF8C00?style=flat&logo=amazonec2)
![RDS](https://img.shields.io/badge/AWS-RDS-FF8C00?style=flat&logo=amazonrds)

![Nest](https://img.shields.io/badge/-nestjs-red)
![ParseServer](https://img.shields.io/badge/ParseServer-0078d6?style=flat)
![ParseDashboard](https://img.shields.io/badge/ParseDashboard-0078d6?style=flat)

![React](https://img.shields.io/badge/react-%2361DAFB.svg?&style=flat&logo=react&logoColor=black)
![BootStrap](https://img.shields.io/badge/BootStrap-purple?style=flat&logo=Bootstrap)
![Postgre](https://img.shields.io/badge/postgresql-%23336791.svg?&style=flat&logo=postgresql&logoColor=white)

**웹서버**
 - Nginx

**백엔드**
 - NVM 
 - Node 16.18.0
 - Express
 - ParseServer & ParseDashboard

**프론트엔드**
 -  React
 -  Bootstrap
 
**빌드 툴**
 - Webpack

**데이터베이스**
 - PostgreSQL

**인프라** 
 - AWS EC2
 - AWS RDS
 - Docker
 - Docker Compose

## 시스템 아키텍처
![시스템 아키텍처](./images/system.png)

## E-R 다이어그램
![ERD](./images/erd.png)


## 📑 Api 명세서
### [Api 명세서 보기](./api/index.html)


## 🛠 MP 릴리즈 노트

<details>
<summary> 2022-10-31 MP v1.1.0 릴리즈 보기</summary>
<div markdown="1">   
  <ul>
    <li>이메일 인증 제거</li>
    <li>폰트 변경</li>
    <li>글쓰기 유효성 검사 강화</li>
  </ul>
</div>
</details>
<details>
<summary> 2022-11-05 MP v1.2.0 릴리즈 보기</summary>
<div markdown="1">       
  <ul>
    <li>요청 Body 사이즈 기존 5M > 10M로 변경</li>
    <li>회원가입 여부에 따라 활성화 버튼 변경</li>
    <li>애드핏 광고 1개 > 4개로 변경</li>
  </ul>
</div>
</details>
<br><br>

## 💻화면 구성
![로그인](./images/page/login.png)|![회원가입](./images/page/register.png)|
| :-----------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: | 
|로그인|회원가입

![전체 추억](./images/page/allmap.png)|![내 추억](./images/page/mymap.png)|
| :-----------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: | 
|전체 추억|내 추억

![비회원](./images/page/nonuser.png)|![지도 상세](./images/page/mapdetail.png)|
| :-----------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: | 
|비회원|지도 상세

![추억 남기기](./images/page/mapwrite.png)|![지도 검색하기](./images/page/mapwrite_01.png)|
| :-----------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: | 
|추억 남기기|지도 검색하기