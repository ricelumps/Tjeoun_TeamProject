# Spring - Company Homepage

JSP -> Spring 마이그레이션

사내 내부 홈페이지



    

## 💻 프로젝트 소개 Introduce
사내 인트라넷에서 사용되는 내부 홈페이지

Company Internal HomePage

## 🕙 개발 기간 Period
* 1차 ( Vanila JSP ) : 2023.07.03 ~ 2023.07.14
* 2차 ( JSP -> Spring Migration ) : 2023.08.04 ~ 2023.08.11
* 최종 ( Few Updates & Bug Fix )  : 2023.08.25 ~ 2023.09.21 


## ⚽ 기능 Features

- 로그인 [ Login ] 
- 마이 페이지 [ My Page or Profile ]
- 출 / 퇴근 기록 [ Commute Check ] 
- CRUD 자유 / 공지 / 결재 / 식단표 게시판 [ CRUD Board ]
- 사내 일정 [ Company Schedule ]


## ⚙️ 개발환경 Development Environment

- Language : Java 11
- IDE : STS 3.9.7
- Framework : Spring 3.1.1
- DB : OracleDB 11g xe
- ORM : MyBatis



## 📌 자료 Docs

#### 로그인 Login <a href="https://github.com/ricelumps/Tjeoun_TeamProject/wiki/%F0%9F%93%83-%EB%A1%9C%EA%B7%B8%EC%9D%B8"> 상세보기 </a>
- DB값 검증
- 로그인 성공 시 쿠키( Cookie ) 및 세션 ( Session ) 생성

#### 마이페이지 My Page
- 회원정보 변경

#### 출 / 퇴근 기록
- 오늘 날짜의 출/퇴근 기록 DB값 조회
- 기록 없을 시에만 DB INSERT

#### 자유 / 공지 / 결재 / 식단표 게시판 
- 원하는 게시판 조회
- 게시판 권한에 따른 생성 / 읽기 / 수정 / 삭제 기능 
- 식단표, 결재 게시판의 경우 파일 업로드 및 다운로드 기능

#### 사내 일정
- 원하는 달의 일정 조회
- 권한에 따른 일정 생성 및 삭제 기능