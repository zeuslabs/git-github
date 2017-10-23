# Git-GitHub

## 1. Git (공식사이트 : http://git-scm.com)
1. 사용자 정보 지정하기
    * Git 설치 후 초기 사용자 정보를 지정한다.
     ``` 
     $ git config --global user.name "사용자이름"
     $ git config --global user.email 이메일주소
    ```
2. 새 git 저장소 만들기
    - 홈디렉터리에 새 디렉터리 생성한다.
     ``` 
     $ mkdir ~/디렉터리명명
    ```
    - 생성한 디렉터리로 이동한다.
     ``` 
     $ cd 디렉터리명
    ```
    - 해당 디렉터리를 Git 저장소(디렉터리 안에서 이루어지는 모든 작업과정을 Git에서 감지, 추적, 관리하는 것)로 지정한다.
     ``` 
     $ git init
    ```
    - 지정이 제대로 되었는지 확인한다.
     ``` 
     $ git status
    ```


