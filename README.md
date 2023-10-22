# TIL

브랜치 정의
    A branch in Git is simply a lightweight movable pointer to one of these commits.

## 브랜치 합치기
 - 이슈에 해당하는 작업을 수행할 때, 별도의 브랜치를 만들고 작업한다.
 - 작업이 끝난 후에는, PULL REQUEST를 사용해 내가 작업한 브랜치를 중요 브랜치에(`master`, `developement`, `devel`)로 병합 시켜야 한다.

 ### 명령어
  - `git merge`
  - 주의할점 : A브랜치를 B브랜치로 합치려고 할 때는 `A`브랜치를 체크아웃 한뒤 `git merge B`를 입력한다.