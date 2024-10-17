## 브랜치 네이밍 규칙

### ` main ` 
사용자에게 배포 가능한 상태만을 관리한다. 여기서는 배포(release) 이력을 관리하기 위해 사용한다. <br>
### ` develop `
다음 출시 버전을 개발하는 브랜치
기능 개발을 위해 브랜치들을 병합하기 위해 사용, 즉 모든 기능이 추가되고 버그가 수정되어 배포 가능한 안정적인 상태라면 develop 을 main 으로 병합한다. 평소에는 이 브랜치 기반으로 개발을 진행한다 <br>
### ` feature branch `
feature - 새로운 기능 개발 및 버그 수정이 필요할 때마다 develop 브랜치로부터 분기한다.
개발이 완료되면 develop 브랜치로 merge 하여 다른 사람들과 공유한다.
<i> feature/front/기능요약 </i> <br> 
ex) feature/front/login, feature/back/login-api
feature/front/{issue-number}-기능요약 <br>
ex) feature/front/#77-login, feature/back/#77-login-api

<b> 기능목록 <b>
|name| description|
|:--:|:--:|
|green-talk|리워드 기반 사용자 채팅|
|green-guide|다회용기 포장가능한 매장 정보 제공| 
|green-elite|어플 사용 장려 환경관련 퀴즈|
|green-club|마감기한 임박 음식 판매 동네 커뮤니티|
|green-commit|환경관련 활동 기록|
|green-auth|인공지능 기반 다회용기 사용인증|
|green-heroes|리워드 기반 명예의 전당|
|green-track|최소탄소거리 측정|
<!--
4) hotfix branch
hotfix - 출시 버전에서 발생한 버그를 수정하는 브랜치
ex) hotfix-1.2.1-->
<br></br>
### 🔥 checkList 🔥
주의사항
feature/기능요약 에서 기능요약 부분을 작성할때 띄어쓰기는 - 를 이용하여 작성 <br>
ex) loginApi (X) login-api (O)


## 커밋 규칙

### ` main ` 
사용자에게 배포 가능한 상태만을 관리한다. 여기서는 배포(release) 이력을 관리하기 위해 사용한다. <br>
### ` develop `
다음 출시 버전을 개발하는 브랜치
기능 개발을 위해 브랜치들을 병합하기 위해 사용, 즉 모든 기능이 추가되고 버그가 수정되어 배포 가능한 안정적인 상태라면 develop 을 main 으로 병합한다. 평소에는 이 브랜치 기반으로 개발을 진행한다 <br>
### ` feature branch `
feature - 새로운 기능 개발 및 버그 수정이 필요할 때마다 develop 브랜치로부터 분기한다.
개발이 완료되면 develop 브랜치로 merge 하여 다른 사람들과 공유한다.
<i> feature/front/기능요약 </i> <br> 
ex) feature/front/login, feature/back/login-api
feature/front/{issue-number}-기능요약 <br>
ex) feature/front/#77-login, feature/back/#77-login-api

<b> 기능목록 <b>
|name| description|
|:--:|:--:|
|green-talk|리워드 기반 사용자 채팅|
|green-guide|다회용기 포장가능한 매장 정보 제공| 
|green-elite|어플 사용 장려 환경관련 퀴즈|
|green-club|마감기한 임박 음식 판매 동네 커뮤니티|
|green-commit|환경관련 활동 기록|
|green-auth|인공지능 기반 다회용기 사용인증|
|green-heroes|리워드 기반 명예의 전당|
|green-track|최소탄소거리 측정|
<!--
4) hotfix branch
hotfix - 출시 버전에서 발생한 버그를 수정하는 브랜치
ex) hotfix-1.2.1-->
<br></br>
### 🔥 checkList 🔥
주의사항
feature/기능요약 에서 기능요약 부분을 작성할때 띄어쓰기는 - 를 이용하여 작성 <br>
ex) loginApi (X) login-api (O)


## 커밋 규칙

- feat : 새로운 기능에 대한 커밋
- fix : build 빌드 관련 파일 수정에 대한 커밋
- build : 빌드 관련 파일 수정에 대한 커밋
- chore : 그 외 자잘한 수정에 대한 커밋(rlxk qusrud)
- ci : CI 관련 설정 수정에 대한 커밋
- docs : 문서 수정에 대한 커밋
- style : 코드 스타일 혹은 포맷 등에 관한 커밋
- refactor : 코드 리팩토링에 대한 커밋
- test : 테스트 코드 수정에 대한 커밋

### 🔥 checkList 🔥

`feat : 예시 메세지입니다.` (O) <br>
`feat:예시 메세지입니다.` (X) <br>
`[feat]:예시 메세지입니다.` (X) <br>

`:` 기준으로 양옆 띄어쓰기


