# Git을 활용한 Team_Project_Flow
깃헙과 깃을 활용하여 팀 프로젝트 코드를 관리해보자

## 전체 흐름
팀 단위 (팀장이 담당)
1. Orangization 생성 : 팀 oranization 생성 및 팀원 초대
2. Repository 생성 : 프로젝트 Repo 생성
3. 환경 설정 : .gitignore 등 기본 환경 설정
4. Issue 생성 : 해야하는 작업들을 이슈로 정리  
    추가적으로 팀장은 _**wiki, Projects**_ 들도 관리해주어야 함

개인 단위 (이슈에서 각자 할 것을 담당)
1. Fork : 각 조원들은 팀 저장소를 포크하여 개인 리포지터리 생성
2. 개인 Branch 생성 : 개인 리포지터리에서 브랜치를 만들어서 작업, 브랜치 이름은 작업을 명시하면 좋음   
ex. feature/fizzbuzz -> fizzbuzz 기능을 생성하는 브랜치
3. push -u origin 브랜치 : 본인이 작업한 브랜치를 개인 저장소에 push
4. pull request : 작업한 브랜치를 팀 저장소 main branch에 pull request  
_**resolve #{이슈 넘버}**_ 를 통해 issue 관리도 동시에 하기

팀 단위 (팀장이 담당)
1. merge : pull request를 확인하고 문제가 없다면 main branch에 병합

개인 단위 (업데이트 된 팀 main branch 가져오기)
1. 브랜치 삭제 : merge가 완료되면 작업에 사용된 브랜치는 삭제
2. remote add upstream {주소} : upstream 이라는 이름으로 팀 원격 저장소 가져오기 (한 번만 해주면 됨)
3. fetch upstream main : 팀 원격 저장소의 main 브랜치 가져오기
4. merge FETCH_HEAD : 나의 main 브랜치에 팀 main 브랜치 병합하기

## 블로그 정리

명령어들을 [medium 블로그](https://medium.com/@dlstj1506/git-3bb137153028)에 정리하였다.