# git intro

1. 초기화  `$ git init`
   1. 실제로는 .git/ 폴더가 생성됨
   2. 버전관리가 시작됨
   3. 리포(repository)라고 부름
2. 서명 설정
   1. `$ git config --global user.name `
      "name"
   2. `$ git config --global user.email`
      "email@mail"
3. 리포의 상태보기 `$ git status`
4. ???? ` $ git add `
5. ???? `$ git commit`
6. 로그보기 `$ git log`



# github

1. 원격저장소(remote repository) 생성
2. 로컬 리포 => 리모트 리포 `$ git remote add origin <URL>`
3. 로컬 커밋들을 리모트로 보내기 `$ git push origin master`
4. `$ git push == $ git push origin master로 단축 명령하기 ` `$ git push -u origin master`
   -u : upstream
5. 다른 컴퓨터에서 원격 리포 받아오기 `$ git clone <URL>`
6. 이후 remote repo 변경사항을 local repo에서 반영하기 `$git pull`



# 집 컴퓨터 세팅

1.  git 다운로드 및 설정
2.  windows 키 누르고 => git bash 찾아서 실행(집컴의 홈폴더 ~)
3. `$ git config --global .......`
4. ` $ git clone <URL>`

# TIL 관리 시나리오

1. 멀캠에 온다.
2. ` $ git pull`
3. 열-공
4. 중간중간 `$ git add . & $ git commint`
5. 집 가기 전에 `$ git push`
6. 집 도착
7. `$ git pull`
8. 복습 및 자습 (`$ git commit`)
9. 마지막으로 `$ git push`
10. 1번으로