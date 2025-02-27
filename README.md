# <p align="center"><img src="https://velog.velcdn.com/images/kby0908/post/586a2140-fbd5-48af-b6bb-cbff376365c5/image.png" width="50" align="center"> <b>let's GIT it</b></p>

<p align="center"> 📆 2023.01.11~ 2023.03.02

<br>
<br>
<!-- ## 📼 LET'S GIT IT -->
<h2 align="center">👉 <a href="https://let-s-git-it.vercel.app/">let's GIT it 바로가기</a></h2>

<p align="center"><img src ="https://user-images.githubusercontent.com/100506719/223014450-d4b6f831-b312-482b-8797-8c80d6e649b8.gif" width="600"></p>

<br />

## Goal

<b>Github 데이터를 활용한 개발자 동기부여 랭킹 서비스입니다</b>

✔ 깃허브의 다양한 데이터들로 종합 점수를 산출하고 랭킹을 확인할 수 있습니다. <br/>

✔ 깃허브 아이디를 검색하여 원하는 유저를 일대일 비교할 수 있습니다.  <br/>

✔ 따로 회원가입 없이 간편하게 Github를 연동하여 이용할 수 있습니다. <br />

✔ 로그인을 한 후 개발자 커뮤니티를 자유롭게 사용하여 의견을 공유할 수 있습니다. <br/>

<br />

## Team let's GIT it

<b>FrontEnd</b>

- [김보윤](https://github.com/kimboyoon) (메인, Nav bar, 글 상세페이지)
- [박지영](https://github.com/zhwltlr) (랭킹페이지, 커뮤니티 글목록, footer)
- [심동섭](https://github.com/ShimDongseup) (소셜로그인, 회원가입, 글쓰기/수정, 마이페이지)
- [홍석현](https://github.com/SeokhyunHong1510) (유저 상세페이지, 비교 페이지, 유저 프로필 카드) <br>

<b>BackEnd</b>

- 오현상
- 이명석
- 지송현

## My Roll
<detail>

  ✔ 여러개의 API와 통신하여 글과 관련한 데이터를 불러온 후 재가공하여 여러 컴포넌트에 뿌려주고 각 컴포넌트에서 목적에 맞게 그려줍니다. <br />

  ✔ 커뮤니티에서 링크를 공유할 수 있도록 외부 sdk를 사용하여 카카오톡, 이메일, 페이스북 공유 기능을 구현하였습니다. <br />
  
  ✔ Recoil을 사용하여 댓글 탭 state를 전역으로 상태관리하여 모든 컴포넌트에서 다양한 기능과 함께 최신순, 인기순 정렬을 지속적으로 업데이트되도록 하였습니다. <br />
  
  ✔ 검색 기능인 Search 컴포넌트 구현하여 다른 페이지에서도 재사용이 가능하도록 하였습니다. <br />
  
  ✔ 에러 Page를 만들고, 모든 페이지에 Scroll to Top 기능을 적용하여 사용자에게 긍정적인 UI/UX를 제공하고자 하였습니다. <br />
  
</detail>

## Skills

<h3>💻 FE </h3>
<span>
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"/> 
  <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=fff"/>
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>

  - TypeScript : 자바스크립트의 타입 에러 발생을 방지하고 디버깅을 용이하게 하기 위해 사용하였습니다. 팀원 모두가 새로운 언어를 학습하기에 어려움도 있었지만 앞선 프로젝트에서 아쉬웠던 점을 보완하기 위해 타입스크립트를 도입하게 되었습니다. <br />
  - Recoil : 프로젝트가 커지면서 props drilling 문제가 발생하였습니다. 이를 해결하기 위해 상태관리 라이브러리 도입을 고민했고, 기존의 React 문법과 가장 유사하여 사용하기 어려움이 없었던 Recoil을 도입하게 되었습니다.
</span>
<br />

## Tools

<span>
  <img src="https://img.shields.io/badge/vsCode-007ACC?style=for-the-badge&logo=Visual Studio Code&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"/> 
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/>
  <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> 
  <img src="https://img.shields.io/badge/trello-0052CC?style=for-the-badge&logo=trello&logoColor=fff"/>
  <img src="https://img.shields.io/badge/gitbook-3884FF?style=for-the-badge&logo=gitbook&logoColor=white"/>
  <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
</span>

## Detail Indicator

  - 호기심(10%), 열정(20%), 명성(35%), 능력(35%)로 산출된 종합 점수
  
  - 각각의 지표는 다시 세분화된 지표로 점수 산출
    - 호기심 (10%)
      1. 유저의 이슈 수 (5점)
      2. 유저가 포크를 한 레포지토리 수 (4점)
      3. 유저가 스타를 누른 레포지토리 수 (2점)
      4. 유저가 팔로우 하는 유저의 수 (1점)
      
    - 열정 (20%)
      1. 유저의 커밋 수 (5점)
      2. 유저의 PR 수 (4점)
      3. 유저가 PR에 남긴 리뷰의 갯수 (2점)
      4. 유저가 생성한 레포지토리 수 (1점)
      
    - 명성 (35%)
      1. 유저의 팔로워 수 (5점)
      2. 유저의 전체 레포지토리의 포크 수 (4점)
      3. 유저의 전체 레포지토리의 와치 수 (3점)
      
    - 능력 (35%)
      1. 스폰 받은 수 (5점)
      2. 유저의 전체 레포지토리의 스타 수 (4점)
      3. 유저가 기여한 저장소들의 스타 수 (3점)
      4. 유저가 공동작업에 참여한 저장소들의 스타 수 (3점)


## Detail Function

1. 메인페이지 Top5 랭커 표시, 클릭시 상세페이지로 이동
2. Github 소셜 로그인시 추가정보 입력 페이지로 이동
3. Top100 랭킹페이지 세부 목록에 따른 오름차순 / 내림차순 정렬
4. 14가지 지표를 그래프 데이터로 나타낸 유저 상세 페이지
5. 유저 vs 유저 서로의 지표를 확인할 수 있는 비교 페이지
6. 글 조회, 등록, 수정, 삭제 유기적인 소통이 가능한 커뮤니티 게시판
7. 개인정보 및 커뮤니티 활동 내역을 확인할 수 있는 마이페이지

<br>
