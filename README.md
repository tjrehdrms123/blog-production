# donggeun's blog (2022.01.21 ~ ing)

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
- [릴리즈 노트](#-Blog-릴리즈-노트)
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
![Nest](https://img.shields.io/badge/nestjs-%23336791.svg?&style=flat&logo=nestjs&logoColor=red)
![React](https://img.shields.io/badge/react-%2361DAFB.svg?&style=flat&logo=react&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-%23336791.svg?&style=flat&logo=MongoDB&logoColor=white)

**웹서버**

- Nginx

**백엔드**

- NVM
- Node 16.18.0
- Nest

**프론트엔드**

- React

**빌드 툴**

- Webpack

**데이터베이스**

- MongoDB

**인프라**

- AWS EC2
- AWS RDS
- Docker
- Docker Compose

## 🛠 Blog 릴리즈 노트

<details>
<summary> 2023-01-22 MP v1.1.0 릴리즈 보기</summary>
<div markdown="1">   
  <h3>SEO 개선</h3>
  <ul>
    <li>react-helmet 적용</li>
    <li>동적 경로 sitemap 등록</li>
  </ul>
  <h3>버그 fix</h3>
  <ul>
    <li>쿼리스트링 없이 /home으로 접속했을때 꺠지는 이슈 수정</li>
  </ul>
</div>
</details>
<details>
<summary> 2022-01-29 MP v1.2.0 릴리즈 보기</summary>
<div markdown="1">       
  <h3>기능 fix</h3>
  <ul>
    <li>쿼리스트링 대신 react-router-dom 활용</li>
    <li>API 호출했을때 에러 및 예외 메세지가 정확히 오지 않는 부분 수정</li>
    <li>sitemap, rss 자동 업데이트 Shell Crontab등록</li>
  </ul>
</div>
</details>
<br><br>

## 💻화면 구성

| ![로그인](./images/page/login.png) | ![회원가입](./images/page/register.png) |
| :--------------------------------: | :-------------------------------------: |
|               로그인               |                회원가입                 |

| ![About me](./images/page/aboutme.png) | ![Home](./images/page/home.png) |
| :------------------------------------: | :-----------------------------: |
|                About me                |              Home               |

| ![글 상세](./images/page/view.png) | ![글 작성](./images/page/write.png) |
| :--------------------------------: | :---------------------------------: |
|              글 상세               |               글 작성               |

| ![글 업데이트](./images/page/update.png) | ![블로그 문의하기](./images/page/contact.png) |
| :--------------------------------------: | :-------------------------------------------: |
|               글 업데이트                |                블로그 문의하기                |

| ![포트폴리오](./images/page/portfolio.png) | ![문의하기](./images/page/contact_update.png) |
| :----------------------------------------: | :-------------------------------------------: |
|                 포트폴리오                 |                   문의하기                    |

| ![이력서](./images/page/resume.png) | ![업데이트된 나에 대해서](./images/page/aboutme_update.png) |
| :---------------------------------: | :---------------------------------------------------------: |
|               이력서                |                   업데이트된 나에 대해서                    |
