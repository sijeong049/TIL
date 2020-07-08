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

   ​