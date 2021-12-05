# devlog

## client 
client repo: https://github.com/SpicyKimChoi/devlog-client

## server
server repo: https://github.com/SpicyKimChoi/devlog-server


## 컨벤션

### Git branch 

* 기본 정책
  * main 브랜치: publish되고 있는 브랜치, dev 병합 가능
  * dev 브랜치: 개발되고 있는 브랜치, feature 브랜치로부터 병합 가능
  * feature 브랜치: 개발되고 있는 기능별 브랜치

* Git Commit Message
  * 기본 양식
    `[유형] [깃헙이슈번호] 제목`
    본문
  * 괄호와 제목사이에 한 칸 띄우기
  * 개조식 문장으로 간단하게 작성
  * [유형] 종류
    * [기능]: 기능 구현
    * [추가]: 기존 기능에서 구현된 기능이 있을 때
    * [수정]: 기존 기능 수정, 삭제 등
    * [리팩토링]: 코드 리펙토링 (기능 변경이 없는 경우)
    * [테스트]: 테스트 코드
    * [버그]: 버그 수정
    * [형식]: 주석, 수정 코드 정렬 등(코드상의 변경이 없는 경우)
    * [기타]: 파일 추가 등 분류하기 애매한 것 (코드상의 변경이 없는 경우)  
