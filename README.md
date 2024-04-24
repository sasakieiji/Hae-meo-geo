# 목차
1. [서비스 소개](#서비스-소개)
2. [팀원 소개](#팀원-소개)
3. [개발 일정](#개발-일정)
4. [개발 환경 및 기술 스택](#개발-환경-및-기술-스택)
5. [프로젝트 폴더 구조](#프로젝트-폴더-구조)
6. [협업 능력](#협업-능력)
7. [기능 소개](#기능-소개)
8. [상세 담당 업무](#상세-담당-업무)
9. [핵심 코드](#핵심-코드)
10. [소감](#소감)

---

# 🍚 서비스 소개

‘**해머거**’는 밥을 해서 먹으라는 ‘해 먹어’를 귀엽게 발음했습니다. 
무엇을 먹을지 고민하는 사람들을 위해 그 음식의 레시피를 알려주고, 음식을 추천도 해주며 먹은 음식을 올리며 소통하는 사이트 입니다. 무엇을 먹을지 고민 하는 시간을 줄여주고 북마크 해 놓은 음식을 직접 해보고 후기를 남기며 음식을 해서 먹는 즐거움을 줍니다.

---


# 👨‍👩‍👧‍👦 팀원 소개
| 이소정 | 박지성 | 서진희 | 한태희 |
| :---: | :---: | :---: | :---: |
| <img alt="이소정" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/44069187-b0c6-4f7b-bb9c-839a8d7f5295" height="100" width="100"> | <img alt="박지성" src="https://avatars.githubusercontent.com/u/63087490?v=4" height="100" width="100"> | <img alt="서진희" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/c2c4fd90-57c6-40da-93dc-5ec9242f4f70" height="100" width="100"> |<img alt="한태희" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/166af139-3d49-48b5-b666-7040bfe39c05" height="100" width="100"> | |
| [Github](https://github.com/s0zzang) | [Github](https://github.com/sasakieiji) | [Github](https://github.com/sozzi0) | [Github](https://github.com/taehee1228) |
| **팀장** | **디자인 마스터** | **노션 마스터** | **깃 마스터** |

---

# 📅 개발 일정
#### 2024. 3. 28 ~ 2024. 4. 24
|기간|내용|
| :----: | :-- |
|3/28~|기획|
|4/10~|UI 디자인|
|4/10~|마크업 및 기능 개발|
|4/23 ~|QA 기간|


---

# 🔨 개발 환경 및 기술 스택

> ### Tools
| Git | Github | Discord | Notion |
| :---: | :---: | :---: | :---: |
| <img alt="git logo" src="https://git-scm.com/images/logos/logomark-orange@2x.png" width="65" height="65" > | <img alt="github logo" src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="65" height="65"> | <img alt="Discord logo" src="https://assets-global.website-files.com/6257adef93867e50d84d30e2/62595384e89d1d54d704ece7_3437c10597c1526c3dbd98c737c2bcae.svg" height="65" width="65"> | <div style="display: flex; align-items: flex-start;"><img src="https://github.com/volunteer-community/volunteer-backend/assets/107487996/15b94d68-61bd-48d5-8931-2180b62fb9a6" alt="icon" width="65" height="65" /></div>
> ### Front-end
| Html | CSS  | React | React-<br>Router  | esLint | Prettier | React-<br>Query | 
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| <img alt="Html" src ="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/440px-HTML5_logo_and_wordmark.svg.png" width="65" height="65" /> | <img alt="css" src="https://github.com/volunteer-community/volunteer-backend/assets/107487996/cc90533f-6811-4e1b-84e9-6314c9d01da0" height="70" width="70" > | <div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/react-icon.svg" alt="icon" width="65" height="65" /></div> | <img alt="rr" src="https://github.com/volunteer-community/volunteer-backend/assets/107487996/b307f370-9cd4-4dc8-992a-914dd5f45e92" height="65" width="65" > | <div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/eslint-icon.svg" alt="icon" width="65" height="65" /></div> | <div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/prettier-icon.svg" alt="icon" width="65" height="65" /></div> | <img alt="rq" src="https://github.com/volunteer-community/volunteer-backend/assets/107487996/3f49a145-7705-4117-8198-b52fe6b062ea" height="70" width="70" > |

</br>

> ### 개발 환경
|||
| :-------- | :-- |
|FrontEnd | React, Axios, CSS module, Zustand, React-Query |
| BackEnd | [제공된 API](https://api.frontendschool.shop/apidocs/), [식품의약품안전처 조리식품의 레시피 API](https://www.foodsafetykorea.go.kr/api/openApiInfo.do?menu_grp=MENU_GRP31&menu_no=661&show_cnt=10&start_idx=1&svc_no=COOKRCP01), [날씨 API](https://openweathermap.org/)

</br>

> ### 컨벤션
#### prettier
```js
module.exports = {
  singleQuote: false,
  semi: true,
  useTabs: false,
  tabWidth: 2,
  trailingComma: "all",
  printWidth: 80,
  arrowParens: "always",
  endOfLine: "auto",
};
```

</br>

#### 커밋 컨벤션
 
|||
| :--------: | :-- |
feat | 새로운 기능을 추가할 경우
fix |	버그를 고친 경우
design |		CSS 등 사용자 UI 디자인 변경
style |		코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우
!BREAKING CHANGE |		커다란 API 변경의 경우
!HOTFIX |		급하게 치명적인 버그를 고쳐야하는 경우
refactor |		프로덕션 코드 리팩토링
comment |		필요한 주석 추가 및 변경
docs |		문서를 수정한 경우
test |		테스트 추가, 테스트 리팩토링 (프로덕션 코드 변경 X)
chore |		빌드 테스트 업데이트, 패키지 매니저를 설정하는 경우 (프로덕션 코드 변경 X)
rename |		파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우
remove |		파일을 삭제하는 작업만 수행한 경우

</br>

> ### 라이브러리 사용 이유
|||
| :--: | :-- |
React | 재사용 가능한 컴포넌트 사용하기 위해 사용
Zustand | 단순한 상태 관리와 용이한 유지 보수를 위해 사용
Axios | HTTP 통신 로직을 쉽게 관리하기 위해 사용
CSS Module | 스타일 관리의 복잡성을 줄이고 유지 보수성을 향상 시키기 위해 사용
React Query | 서버 동기화를 간편하게 사용하고 무한 스크롤 구동을 위해 사용

</br>

---

# 📂 프로젝트 폴더 구조
<details>
  <summary>해머거</summary>
  
  ```
  ├── App.css ─────────────  
├── App.jsx
├── assets
│   └── lottie
│       ├── error.json
│       ├── loading.json
│       └── noData.json
├── components
│   ├── Attach
│   ├── Button
│   │   ├── Button.jsx
│   │   └── Button.module.css
│   ├── Loading
│   │   └── Loading.jsx
│   ├── NoData
│   │   └── NoData.jsx
│   ├── Pagination
│   │   ├── Pagination.jsx
│   │   └── Pagination.module.css
│   ├── Recipe
│   │   ├── Detail
│   │   │   ├── Banner
│   │   │   │   ├── Banner.jsx
│   │   │   │   └── Banner.module.css
│   │   │   ├── Bookmark
│   │   │   │   ├── Bookmark.jsx
│   │   │   │   └── Bookmark.module.css
│   │   │   ├── Content
│   │   │   │   ├── Content.jsx
│   │   │   │   └── Content.module.css
│   │   │   ├── Ingredient
│   │   │   │   ├── Ingredient.jsx
│   │   │   │   └── Ingredient.module.css
│   │   │   ├── Reply
│   │   │   │   ├── List.jsx
│   │   │   │   ├── List.module.css
│   │   │   │   ├── Register.jsx
│   │   │   │   ├── Register.module.css
│   │   │   │   ├── Reply.jsx
│   │   │   │   └── Reply.module.css
│   │   │   ├── Share
│   │   │   │   ├── Share.jsx
│   │   │   │   └── Share.module.css
│   │   │   ├── Sidebar
│   │   │   │   ├── Sidebar.jsx
│   │   │   │   └── Sidebar.module.css
│   │   │   ├── Step
│   │   │   │   ├── Step.jsx
│   │   │   │   └── Step.module.css
│   │   │   └── SubTitle
│   │   │       ├── SubTitle.jsx
│   │   │       └── SubTitle.module.css
│   │   └── List
│   │       ├── List.jsx
│   │       └── List.module.css
│   ├── Search
│   │   ├── Search.jsx
│   │   ├── Search.module.css
│   │   ├── Type.jsx
│   │   └── Type.module.css
│   ├── Signup
│   │   ├── SignupSteps.jsx
│   │   └── SignupSteps.module.css
│   ├── Title
│   │   ├── Title.jsx
│   │   └── Title.module.css
│   ├── layout
│   │   ├── Footer.jsx
│   │   ├── Footer.module.css
│   │   ├── Header.jsx
│   │   ├── Header.module.css
│   │   ├── index.jsx
│   │   └── index.module.css
│   └── login
│       ├── LoginLayout.jsx
│       └── LoginLayout.module.css
├── hooks
│   └── useCustomAxios.mjs
├── main.jsx
├── pages
│   ├── ErrorPage.jsx
│   ├── ErrorPage.module.css
│   ├── Home.jsx
│   ├── Home.module.css
│   ├── myRecipe
│   │   ├── MyRecipeDetail.jsx
│   │   ├── MyRecipeDetail.module.css
│   │   ├── MyRecipeRegister.jsx
│   │   ├── MyRecipeRegister.module.css
│   │   └── myRecipeList
│   │       ├── MyRecipeItems.jsx
│   │       ├── MyRecipeItems.module.css
│   │       ├── MyRecipeList.jsx
│   │       ├── MyRecipeList.module.css
│   │       ├── MyRecipeSearch.jsx
│   │       ├── MyRecipeSearch.module.css
│   │       ├── MyRecipeSortButton.jsx
│   │       └── MyRecipeSortButton.module.css
│   ├── mypage
│   │   ├── BookMark.jsx
│   │   ├── BookMark.module.css
│   │   ├── InforMation.jsx
│   │   ├── InforMation.module.css
│   │   ├── MyPage.jsx
│   │   ├── MyPage.module.css
│   │   ├── PageSide.jsx
│   │   └── PageSide.module.css
│   ├── recipe
│   │   ├── RecipeDetail.jsx
│   │   ├── RecipeDetail.module.css
│   │   └── RecipeList.jsx
│   ├── todayRecipe
│   │   ├── TodayRecipeList.jsx
│   │   └── TodayRecipeList.module.css
│   └── user
│       ├── Login.jsx
│       ├── Signup.jsx
│       ├── Signup.module.css
│       ├── SignupStepOne.jsx
│       ├── SignupStepThree.jsx
│       ├── SignupStepTwo.jsx
│       └── SignupStepTwo.module.css
├── routes.jsx
├── utils
│   ├── kakaoInit.mjs
│   └── uploadImage.mjs
└── zustand
    └── userStore.mjs
  ```
  
</details>

</br>

---

# 🙏🏻 협업능력

> ### [Notion](https://www.notion.so/3d7489dd4e314f3bb52e2e3f67d05838)
  **회의록 작성, 개발 방향 등 정보 참고**
  노션 기능을 사용하여 매일 아침과 저녁에 스크럼 회의를 했습니다. 각자의 작업 현황과 어려웠던 점 등을 공유하는 시간을 가졌습니다.

> ### Discord
  **화면 공유, 음성 채널로 회의 및 원활한 커뮤니케이션**
  팀원들과 화면 공유 기능을 통해  문제 파악 및 해결을 했습니다.

> ### FIGMA
**디자인 적인 수정사항 파악**
팀원들과 피그마로 와이어 프레임 구성하고, 실시간으로 회의하며 작업 현황을 파악하며 수월하게 작업을 했습니다.

> ### GitHub
**깃허브 팀프로젝트 기능으로 개발버전 관리**
팀 저장소를 포크해서 개인 저장소에서 작업하고 팀프로젝트 dev에 PR을 보내 머지하는 방식으로 작업하여 메인버전에 실수로 머지 할수 있는 경우를 줄여 안정적으로 작업할수 있었습니다.

</br>

---
# 💡 기능 소개

> ### 메인 페이지

| 헤더 | 메인 | 푸터 |
| :--: | :--: | :--: |
| <img alt="메인페이지-헤더" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/d25b64d9-f227-4124-929c-21735336a41c" width="300px"> | <img alt="메인페이지-메인" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/1eabb515-e183-41e0-be56-49b00f0f05cd" width="300px"> |<img alt="메인페이지-푸터" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/9995fca2-38cb-4558-9d20-47cffff2b8d1" width="300px"> |

</br>

> ### 로그인

| 로그인 | 테스트 로그인 | 
| :----: |:----: |
|<img alt="로그인" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/d122464d-bd94-42b9-85b9-1d1467e44e20" width="300px"> | <img alt="테스트 로그인" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/e730fb9f-2af5-4013-95e1-0aa8728bee85" width="300px"> |

</br>

> ### 회원가입

| 회원가입 | 약관동의 | 정보입력 |
| :------: | :------: | :------: |
| <img alt="회원가입" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/292dc840-565d-4538-8203-7e0de78e789c" width="300px" > | <img alt="약관동의" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/3034421a-bcd7-4685-a0af-9a2f46919b53" width="300px" > |<img alt="정보입력" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/6076d0ca-5ba2-448f-bbc5-41cd2f3710bc" width="300px" > |

</br>

> ### 오늘뭐먹지?

| 목록 | 검색 | 무한스크롤 |
| :--: | :--: | :--------: |
| <img alt="목록" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/2fdd04b5-9110-46de-a72d-0590761cd6c7" width="300px"> | <img alt="검색" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/bae99c52-de71-45fa-9e70-cecfbe659129" width="300px"> |<img alt="무한스크롤" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/c404eb11-8ad6-4767-9ea2-d7ecee972425" width="300px"> |

</br>

> ### 해머거 레시피

| 목록 | 검색 | 페이지네이션 |
| :--: | :--: | :----------: |
| <img alt="목록" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/84554b2f-37bd-4750-b6dc-ec7b6b554d4c" width="300px"> | <img alt="검색" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/ca4f9486-b1b4-4d4e-aba3-f31cd1ae3656" width="300px"> |<img alt="페이지네이션" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/57a63fe4-7397-41d9-b66e-53943149fd98" width="300px"> |

| 상세 | 후기 작성 | 후기 삭제 |
| :--: | :-------: | :-------: |
| <img alt="상세" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/33a1ad57-c335-41a9-bf34-a1987b70c241" width="300px"> | <img alt="후기 작성" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/285a5408-0f1a-448f-aa5e-5e489534e5f6" width="300px"> |<img alt="후기 삭제" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/f995d437-ff99-4965-910b-454c298f7e16" width="300px"> |

| 북마크 등록 | 카카오톡 공유 |
| :---------: | :-----------: |
| <img alt="북마크 등록" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/c579517e-f732-400e-b488-7530de3ccce1" width="300px"> | <img alt="카카오톡 공유" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/4698ad99-a814-472f-bf7a-0dd8ec9d6354" width="300px"> |

</br>

> ### 나만의 레시피

| 목록 | 검색 |
| :--: | :--: |
| <img alt="목록" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/3d2ce388-562d-4a73-9597-8a9698cf296b" width="300px"> | <img alt="검색" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/66032b59-a5a1-4965-9eeb-43a71e961316" width="300px"> |

| 상세 | 등록 |
| :--: | :--: |
| <img alt="상세" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/bf9b4ca7-8ec4-4176-a9fe-43c1fe7b3ca9" width="300px"> | <img alt="등록" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/4a112e0e-e632-4a03-aa24-43df48a75f72" width="300px"> |

</br>

> ### 기타

| 에러 | 로딩 |
| :--: | :--: |
| <img alt="404 에러" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/db0c4203-26d7-4f29-b848-d32e9ef24515" width="300px"> | <img alt="로딩" src="https://github.com/FRONTENDSCHOOL9/Hae-meo-geo/assets/153144316/be4cab7f-4f63-4f86-b5c9-926defeaf635" width="300px"> |

</br>

---

# 💻 상세 담당 업무
### <u>👧🏻 이소정(팀장)</u>
- 🌟 메인 페이지
    - 추천 레시피
      - OpenWeather 날씨 api을 사용하여 현재 날씨를 받아옴
      - 추천 메뉴를 리스트업하여 db에 초기 세팅 후 현재 날씨와 요일에 알맞은 레시피 랜덤 노출
      - 레시피 클릭시 레시피 상세 화면으로 이동
  - 해머거 레시피
      - 북마크가 많은 순서대로 최대 6개 노출
      - 더보기 버튼 클릭시 해머거 레시피 목록으로 이동
  - 나만의 레시피
      - 최근 등록된 순서대로 최대 6개 노출
      - 더보기 버튼 클릭시 나만의 게시물 목록으로 이동
  - 레시피 검색
      - 키워드가 반영된 해머거 레시피 목록으로 이동

- 🌟 오늘 뭐먹지?
  - 레시피 추천
      - 날씨/요일별 추천 메뉴를 리스트업하여 db에 저장하여 초기 세팅

- 🌟 레시피 목록
  - 카테고리, 검색
      - 조리식품의 레시피 API에서 제공해주는 쿼리스트링 활용하여 데이터 호출
  - 페이지네이션
      - 조리식품의 레시피 API에서 제공하는 레시피의 총 개수를 활용하여 5개씩 페이지네이션이 노출되도록 구현
      
- 🌟 레시피 상세
  - 후기
      - 조리식품의 레시피 일련 번호를 상품으로 초기 등록하여 해당 상품의 일련번호에 해당하는 QnA 게시글 호출/등록/삭제
      - 게시글 POST 통신시 [파일 업로드 API](https://api.frontendschool.shop/apidocs/#/%ED%8C%8C%EC%9D%BC/post_files_)를 활용하여 업로드된 파일명을 추출하는 함수 분리(src/utils/uploadImage.mjs)
  - 북마크
      - 조리식품의 레시피 일련 번호를 상품으로 초기 등록하여 해당 상품의 일련번호에 해당하는 상품에 북마크 추가/삭제
  - 공유하기
      - [카카오톡 메시지 전송 API](https://developers.kakao.com/tool/demo/message/kakaolink?message_type=default)를 활용하여 레시피의 이름, 사진, 링크를 카카오톡 메시지로 전달
      
- 🌟 공통 컴포넌트
    - 헤더
    - 푸터
    - 로딩 페이지
    - 에러 페이지

</br>

### <u>🧒🏻 박지성</u>
- 🌟 나만의 레시피 게시판(커뮤니티)
    
    - 게시판 목록
        
      - 갤러리형 게시판
      - 검색 기능

    - 게시물 등록
      
      - 메인 이미지, 이름, 재료 설명

    - 게시물 상세
      - 메인 이미지, 이름, 재료(한 번에 보여주기), 작성자

</br>

### <u>👩🏻 서진희</u>
- 🌟 회원가입
    
  - 이메일 중복 확인
  - 비밀번호, 비밀번호 확인
  - 닉네임, 생년월일, 프로필 이미지
  - 개인 정보 활용 동의

- 🌟 로그인
  
  - 이메일, 비밀번호 로그인
  - 이메일 저장 버튼 (로컬 스토리지에 저장)
  - 로그인 완료시 이전 페이지로 이동
  - 테스트 로그인
  - 로그아웃
  
- 🌟 로그인 유지

  - 로그인 시 2시간이 지나면 자동으로 토큰 갱신하여 로그인 유지

</br>

---

# 🍳핵심 코드
### 이소정
<details>
  <summary>메인 - 날씨/요일별 추천 레시피</summary>
  
  > - 현재 날씨와 요일별로 레시피를 추천하는 기능
  > - 현재 날씨 : [날씨 API](https://api.openweathermap.org)를 활용하여 서울을 기준으로 현재 날씨 수집
  > - 현재 요일 : 자바스크립트 Date 생성자 함수 활용
  > - 레시피 추천 리스트 : 게시판 API를 활용하여 직접 리스트업
  > - 조건에 맞는 레시피 랜덤으로 추출하여 노출

</details>

<details>
  <summary>해머거 레시피 - 공공데이터 레시피 API를 상품 API로 초기 세팅하여 후기, 북마크 기능 사용</summary>
  
  > - 초기 세팅 : 초기 데이터를 세팅할 때 조리식품의 레시피 API를 호출하여 1001개의 데이터 세팅(api/dbinit/team/data.js)
  > - 초기 등록한 상품 API의 후기(목록,등록,삭제), 북마크 기능을 통해 조리식품의 레시피에 후기, 북마크 기능 사용
 
</details>

<details>
  <summary>해머거 레시피 - 페이지네이션</summary>
  
  > 조리식품의 레시피 API에서 제공하는 총 레시피 개수를 활용하여 5개씩 페이지네이션 구현

</details>

### 박지성
<details>
  <summary>나만의 레시피 페이지에 회원이 레시피를 등록할수 있게하는 기능</summary>

  
  > - 이를 구현하기 위해서는 회원이 작성한 데이터와 이를 서버에 전달하여 저장할 방법이 필요했습니다.
  > - 회원이 작성한 데이터는 form을 통해 제출 받고 서버에 전달하여 저장하는 것은 서버 api와 axios를 통해 서버에 저장할수 있도록 구현했습니다
  

</details>

### 서진희
<details>
  <summary>이메일 중복 확인</summary>


  > - 사용자가 회원 가입 시 작성하는 이메일 주소가 서버에 이미 등록되어 있는지 확인하는 기능입니다. 이 코드를 구현하기 위해 사용자가 입력한 이메일 주소를 서버에 전송하는 것과 서버에서의 이메일 주소 등록 여부를 확인 후 그 응답을 처리하는 것이 필요했습니다.
  > - 사용자가 이메일 주소를 입력하면 변경될 때마다 onChange 이벤트 핸들러로 checkEmailAvailability 함수를 호출하도록 구성하였고, checkEmailAvailability 함수 내에서 서버와 통신을 하기 위해 axios를 사용하여 이메일 중복 확인 요청을 보내고, 서버의 응답을 이메일 중복 여부에 따라 메시지를 사용자가 볼 수 있도록 구현했습니다.


</details>

</br>

---

# 💬 소감 
##### 🍚 이소정

> 소감 작성

##### 🍚 박지성

> 소감 작성

##### 🍚 서진희

> 프로젝트를 마무리하면서 지난 시간을 돌이켜보면 그동안 제대로 알지 못한 github, API 서버 통신 등을 더 자세히 알게 된 시간이었습니다. 이런 기술뿐만 아니라 팀원들과 협업하며 소통하고 문제를 해결해 나가는 것에 대해서, 어렵지만 즐거웠던 시간이었다고 느꼈습니다. 그리고 팀원들을 잘 이끌어 주신 팀장님 덕분에 프로젝트가 잘 마무리될 수 있었습니다. 많이 배울 수 있었던 첫 프로젝트였습니다. 감사합니다.


##### 🍚 한태희

> 소감 작성
