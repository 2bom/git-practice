[Git practice] 잘 모르는 깃 명령어 모아두기
=======

# 1. branch
  0. 다른 브랜치를 만들기 전에 master branch로 initial commit을 push 해줘야한다.
	안 그러면 default branch가 master가 아닌 다른 branch가 됨.

1. make branch

  ```console
  $ git branch branch-name
  ```
2. make branch and checkout immediately.

  ```console
  $ git checkout -b branch-name
  ```
  
# 2. merge
  0. master 브랜치에 test 브랜치의 사항들을 합치고 싶으면,
  1. master branch로 checkout부터 한다.
  2. merge 한다.
  ```console
  $ git merge test
  ```

  3. 만약 conflict가 난다면 어떤 파일에 conflict가 났는지 알아보고, conflict를 해결한다.
  4. conflict를 해결했으면 add, commit, push 끝

# 3. log
  0. 로그 보기
  ```console
  $ git log
  ```
  1. 로그 한 줄로 보기
  ```console
  $ git log --oneline
  ```
  2. 로그 그림으로 보기
  ```console
  $ git log --oneline --graph
  ```

#4 . tag
  0. tag 달아놓기
  ```console

  ```
    $ git tag -a tag-name
		태그설명 좀 쓰고
  1. tag 달린 것 확인하기
		$ git log --oneline --decorate --graph
    ```console

    ```
