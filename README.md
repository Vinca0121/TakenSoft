# Taken Soft
이 레파지토리는 임시로 생성되었습니다.

# 🖥️ 기본 정보

## 📍 버전

- JDK 17.0.4
- org.springframework.boot' version '3.0.6'1



# 👨‍👨‍👧‍👦 협업 규칙
## 📍 Commit Naming Convention

커밋을 작성할 때 필히 다음 태그를 이름 앞에 붙여주세요.

붙이지 않으면, pull request가 거절될 수 있습니다.

- [INITIAL] — repository를 생성하고 최초에 파일을 업로드 할 때
- [ADD] — 신규 파일 추가
- [UPDATE] — 코드 변경이 일어날때
- [REFACTOR] — 코드를 리팩토링 했을때
- [FIX] — 잘못된 링크 정보 변경, 필요한 모듈 추가 및 삭제
- [REMOVE] — 파일 제거
- [STYLE] — 디자인 관련 변경사항
  
## 📍 Branch 전략
- main 브랜치는 함부로 push 하지 마세요.(branch protection 적용은 되어있지만)

- Branch는 Git Flow를 따라 개발이 진행 됩니다. (상세 내용은 검색)

- 기본 개발은 develop 브랜치에서 진행이 되며, main 브랜치는 모든 개발이 끝난 후에만 push가 가능합니다.

- feature 브랜치의 naming은 "feature/*"와 같은 형식을 지켜주세요.

- ex) develop -> new branch -> feature/signup-api

- 협업 예시 : 우선 협업을 위해서는 develop branch를 fork하고, 자신의 레파지토리에서 브랜치를 나누어 작업 한 후 이것을 우리가 협업하는 이 원본 레파지토리의 develop branch로 pull request를 보내세요.
