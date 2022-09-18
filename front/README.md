# 포트폴리오 공유 서비스 프론트엔드 코드

## 실행 방법

```bash
cd front
yarn install
yarn start
```
## 폴더 구조

```shell
.
└── front
    ├── public
    │   └── image
    └── src
        ├── components
        │   ├── award
        │   ├── certificate
        │   ├── education
        │   ├── project
        │   └── user
        ├── Header.js
        ├── Porfolio.js
        ├── api.js
        ├── App.js
        ├── index.js
        └── reducer.js

```

## 폴더&파일 설명

1. src폴더는 아래와 같이 구성됩니다.

- components 폴더:

  - Header.js: 네비게이션 바
  - Porfolio.js: 메인 화면을 구성하는, 5개 MVP를 모두 포함하는 컴포넌트
  - award 폴더: 포트폴리오 중 수상이력 관련 컴포넌트들
  - certificate 폴더: 포트폴리오 중 자격증 관련 컴포넌트들 
  - education 폴더: 포트폴리오 중 학력 관련 컴포넌트들 
  - project 폴더: 포트폴리오 중 프로젝트 관련 컴포넌트들 
  - user 폴더: 포트폴리오 중 사용자 관련 컴포넌트들

- api.js:
  - axios를 사용하는 코드가 있습니다.
- App.js:
  - SPA 라우팅 코드가 있습니다.
- reducer.js:
  - 로그인, 로그아웃은 useReducer 훅으로 구현되는데, 이 때 사용되는 reducer 함수입니다.


