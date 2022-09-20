# **2022년 2학기 졸업작품(캡스톤 디자인)**
팀명 : I들<br>
팀원 : 김동호(FE, 팀장), 진승범(FE), 강준모(BE)<br>
졸업작품 소개 사이트 : <b><a href="https://github.com/kimdongho321/capstone22">미완</a></b><br>
졸업작품 소개 사이트 : <b><a href="https://github.com/reidlo5135/capstone22">미완</a></b><br>
<a href="https://github.com/reidlo5135/CAPSTONE2022-HanShake-v2.0.0.git">GitHub 주소</a>

## <b>졸업 작품 소개</b>
작품명 : <b>HANDSHAKE(핸드쉐이크)</b><br>
작품 소개 : <b>HANDSHAKE</b>란 AI(Artificial-Intelligence)를 활용하여 청각장애인을 위한 대림대학교 정보 소개 Web Application<br>
작품 특징 : <b>HANDSHAKE</b>는 사용자가 취하는 모습을 촬영 후 AI로 인식하여 원하는 기능을 맞추어 제공하는 Web Service<br>

## <b>개발환경</b>
<span><img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white">
<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white">
<img src="https://img.shields.io/badge/Swagger-6DB33F?style=for-the-badge&logo=Swagger&logoColor=white"></span>
<img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=JUnit5&logoColor=white">
<img src="https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"><br>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
<img src="https://img.shields.io/badge/express.js-000000?style=for-the-badge&logo=express&logoColor=white">
<img src="https://img.shields.io/badge/NodeMon-76D04B?style=for-the-badge&logo=NodeMon&logoColor=white">
<img src="https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=Npm&logoColor=white">
<img src="https://img.shields.io/badge/Typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"><br>
<img src="https://img.shields.io/badge/react-0769AD?style=for-the-badge&logo=react&logoColor=White">
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/git kraken-179287?style=for-the-badge&logo=gitkraken&logoColor=white">
<img src="https://img.shields.io/badge/GRADLE-efefef?style=for-the-badge&logo=gradle&logoColor=white">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
<img src="https://img.shields.io/badge/AMAZON AWS-232F3E?style=for-the-badge&logo=amazon AWS&logoColor=white"><br>
<img src="https://img.shields.io/badge/AMAZON rds-527FFF?style=for-the-badge&logo=amazon rds&logoColor=white">
<img src="https://img.shields.io/badge/AMAZON s3-569A31?style=for-the-badge&logo=amazon s3&logoColor=white">
<img src="https://img.shields.io/badge/AMAZON ec2-FF9900?style=for-the-badge&logo=amazon ec2&logoColor=white">
<img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">
<img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"><br>
<img src="https://img.shields.io/badge/Adobe XD-FF61F6?style=for-the-badge&logo=Adobe XD&logoColor=white">
<img src="https://img.shields.io/badge/Intellij IDEA-000000?style=for-the-badge&logo=IntelliJ Idea&logoColor=white">
<img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=for-the-badge&logo=Visual Studio Code&logoColor=white"></span>

- Design - Figma, Adobe Xd
- Frontend - React.js, HTML5, CSS3, JavaScript, MediaPipe, TensorFlow
- Backend - Spring Boot, REST API, Swagger, Java(11), Node-Express, TypeScript
- Database - MySQL8.0, Spring Data JPA, AWS RDS, AWS S3
- WAS - Apache Tomcat, AWS EC2
- Version Control - Git, GitHub, Git Kraken
- IDE - IntelliJ IDEA Ultimate, Visual Studio Code

## <b>개발일지</b>
### [2022-09-07]
- <a href="https://github.com/reidlo5135/CAPSTONE2022-HanShake-v2.0.0.git ">GitHub Repository 개설</a>
- Spring Boot 서버 개설(DataBase 작업용)
- Node-Express.ts 서버 개설(Crawling 작업용)
- puppeteer-core 모듈을 통한 Crawling 1차 성공

### [2022-09-14]
<strong>Node-Express.ts - Only Crawling Server</strong>
<ul>
<li>Custom Error Class 생성 후 Custom Error Handling 적용</li>
<li>금주의밥상(Diet) Crawling 후 REST API 개설(요청 / 응답 테스트 성공)</li>
<li>공지사항(Notice) Crawling 후 REST API 개설(요청 / 응답 테스트 성공)</li>
</ul>

<strong>Spring Boot - Only DataBase Server</strong>
<ul>
<li>Node-Express.ts 서버 URL(http://localhost:5000/v2/api/diet/**)로 금주의밥상(Diet) 요청 후 응답받은 Data를 토대로 Modeling & DataBase 저장 성공</li>
<li>Node-Express.ts 서버 URL(http://localhost:5000/v2/api/notice/**)로 공지사항(Notice) 요청 후 응답받은 Data를 토대로 Modeling & DataBase 저장 성공</li>
</ul>

