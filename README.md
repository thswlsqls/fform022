# FTCLONE README.md

# Domain -> [fform022.link](https://fform022.link/)

http://3.38.235.90/ 

## Facebook & Typeform clone MERN stack webapp

---

**1. 프로젝트 개요**

---

[ 구현 기능 ]

1. 게시판에 이미지 및 동영상 단다중 파일을 업로드
2. 댓글과 답글, 좋아요 등록, 제작한 설문조사를 배포
3. 설문조사를 생성하고 수정, 삭제, 배포하여 응답 결과를 확인
4. 캘린더보기 및 특일정보 조회, 소켓 통신하여 간단한 다대다 실시간 채팅

[ 활용 기술 ]

1. Front - Javascript(ES6), HTML, CSS, React(JSX, Babel, Hot reload, CSR), React Hooks, Redux, Redux-devtools, Chrome-devtools
2. Back - Nginx, Javascript(ES6), Node.js, NPM(Node Package manager), Express.js, MongoDB Atlas
3. Infra - AWS EC2, Route53, S3, Cloud front, ALB(Application Loadbalancer), ACM(Amazon Certification Manager), letsencrypt

---

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184572971-1b493571-7434-4c01-9f02-0c1366a3f0ec.png">


**2. 국내외 관련분야 현황**

---

1. 게시판 기능 - 네이버 밴드, 페이스북 등, 글과 사진 및 동영상을 업로드함, 댓글과 답글, 좋아요를 등록함
2. 설문조사 폼 기능 - 구글폼, 네이버 폼 등, 다양한 폼 생성과 배포, 분석결과를 제공함  
   !! 기존 폼 서비스의 개선점? 직관적이지 않은 UI, 사용하기에 어려움, UX가 특화될 여지가 있음, 프리미엄 서비스로 수익화 할수 있음

---

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573003-bc759712-4db7-4dd4-af05-7067e0adbcac.png">


**3. 참고 웹사이트**

---

**Typeform**  
장점과특징

1. 사용자 중심의 인터랙티브하고 직관적인 UI
2. 1화면 1질문 구조와 반응적 요소로 향상된 UX
3. LOGIC JUMP(분기처리)를 활용한 설계로 특정 답변을 유도하는 등 다양한 기능을 제공

---

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573035-8278dd2f-8ada-4f94-959a-94dfcd68e688.png">

**4. 개발 배경 및 필요성**

---

** 기본 웹 기술과 프로젝트 제작 기술들을 습득하여 실습했습니다.  
학습한 리액트 라이브러리 활용법을 적용했습니다.  
데이터베이스를 설계하고 프로젝트에 적용했습니다. **

1. 비대문 문화 확산에 따른 폼 서비스 사용율 증가 - 학교의 온라인 과제와 기업의 고객관리 등
2. 기존 폼 서비스의 개선 가능성 - UI/UX 특화 및 수익화, 직관적이고 쉬운 사용법 제공 등

---

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573055-aef4e80c-6e45-4f02-9821-6a21de5920f3.png">


**5. 프로젝트 설계**

---

1. 시스템 구조도
   ![image](https://user-images.githubusercontent.com/58901024/143247771-feb43aad-51c5-447e-8f38-9aa2cff0389c.png)

2. 개발환경  
   ![image](https://user-images.githubusercontent.com/58901024/143248017-7fef707d-cd05-4ba3-8c4a-6a500093a1be.png)

3. 유스케이스 다이어그램과 명세서
   <img width="100%" alt="유스케이스 다이어그램과 명세서, 웹사이트 구성도, 테이블 설계 초안" src="https://user-images.githubusercontent.com/58901024/148745988-aad0e1fc-c4aa-4a8e-8218-e4b9efc41afd.png">

4. 데이터베이스 설계  
   ![image](https://user-images.githubusercontent.com/58901024/143248158-deef4b2f-cfd2-47f7-bf73-32106e20f05d.png)

---

**6. 추진 일정**

---

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573155-c524648f-4ddf-449a-9d4d-a98e4107b36f.png">

![image](https://user-images.githubusercontent.com/58901024/143248417-862c5b53-461a-4b88-8390-8ab429581c1c.png)  
_개발기간 : 202102 ~ 202106_

---

## **7. 구현 화면과 실행 영상**

[2022-FTClone-PORTFOLIO_20220110.pdf](https://github.com/thswlsqls/ftclone/blob/main/2022-FTClone-PORTFOLIO_20220110.pdf)

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573196-fa0557dc-f5fa-4896-840c-39c66c608ebc.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573212-7bf2f0a4-b025-4dcc-acd0-25aecb550b64.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573247-1cd99b46-fe3c-4715-b7ff-3449edad1de8.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573271-025eb44b-cdc4-41eb-848c-56c27d239b06.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573290-aa8533ef-796b-4696-ad3d-a9808d35ff01.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573313-619b74c9-994f-421f-8379-c27d5dfb35c8.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573330-af1fd3af-f953-43d2-aa2d-33a2c8bdc490.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573362-8b0f6aa6-89e4-4999-8839-a7100a0ce27f.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573375-f661d2bb-8fef-464e-b8d3-5145063e5f25.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573411-14ca5dbc-0862-4da1-ba74-54d41fcbc0b0.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573423-f2304368-ba86-452a-af9c-0e2bb117a940.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573431-1ae05a7f-819c-4142-92e3-3c589601a0d2.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573438-1c2cf815-7099-48a6-8d8d-bea304e3d2b7.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573452-214e4acb-1550-4e75-ac01-c60442ff4888.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573466-69e73753-1a02-41ea-a508-b3e1550371ce.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573478-9a7e2d8a-bb58-43b2-88c8-20fb2b70f094.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/58901024/184573496-21967333-c582-4909-af1b-0be6949cb883.png">



https://user-images.githubusercontent.com/58901024/143205041-1c280c81-de88-42b5-a0ff-c05e7e61ebaa.mp4

mern web project made by oneself, deployed by amazon web service

you can simply check the _.pdf, _\_execution.mp4 files

◻ website domain ◻

## [fform022.link](https://fform022.link/)

http://3.38.235.90/ 

◾ guest account ◾

## email: ftclone@naver.com

## password: ftclone12345

#비대면문화 #재택근무 #온라인수업 #폼서비스활용증가
