# Git-GitHub (업데이트중)

## 1. Git (공식사이트 : http://git-scm.com)
1. 사용자 정보 지정하기
    - Git 설치 후 초기 사용자 정보를 지정한다.
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
3. 커밋하기
    - 파일을 깃의 관리대상으로 추가한다.
     ``` 
     $ git add 파일명
    ```
    - 지금까지 작업내용을 깃 저장소에 저장한다.(commit)
     ``` 
     $ git commit -m "first commit"
    ```
    - 파일 수정하면 수정한 파일 다시 저장소에 등록해야 한다.
     ``` 
     $ git add 파일명
    ```
    - 커밋한다.
     ``` 
     $ git commit -m "edit 파일명"
    ```
4. 작업내역 조회하기
    - 작업내역 조회
     ``` 
     $ git log
    ```
    - 상세내역 조회
     ``` 
     $ git log -p
     
     @@ 코드 변경이 있었던 행 표시 @@
     - 코드가 삭제된 부분
     + 코드가 추가된 부분
    ```


## 2. GitHub (공식사이트 : https://github.com)
1. GitHub
    - GitHub 사이트 가입 및 저장소(repository) 생성 한다.
    - 내려받을때는 공개된어 있으면 누구나 내려 받을수 있으나 올릴때는 가입한 아이디(이메일) 비밀번호가 필요함.
2. Git에 GitHub 저장소와 연결하기
    - Git을 사용할 때 특정 디렉터리에 Git 저장소를 만든 뒤 이를 기반으로 Git을 사용하였듯 GitHub도 GitHub 저장소(repository)를 만들어 연동한다.
    ```
    $ git remote add origin 리모트_저장소_URL
    ```
3. Git 저장소에서 작업한 내용을 GitHub 저장소로 푸시하기
    ```
   $ git push -u origin master
   ```
4. GitHub 저장소에 갱신된 내용을 내 Git 저장소로 동기화하기
    ```
   $ git pull
   ```
5. GitHub 저장소의 내용 내려받기
    ```
   $ git clone 저장소url
   ```
    

## 참고
1. http://fielder.tistory.com/215
2. http://blog.naver.com/won2gonzo/220741696746
3. http://blog.naver.com/dnfkrl/220069366546
4. http://blog.naver.com/tkdldjs35/221031262869
5. http://lee-mandu.tistory.com/300

