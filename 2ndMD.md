## 2일차 MD



## Git

~~~ Git과 Github는 다르다
Git과 Github는 다르다

~~~



### Git 기본명령어 



1. Local repo를 생성할 때 `git init`
2. Wd에 생긴 변화 사항 (파일 생성, 수정, 삭제 등) 을 버전으로 관리하고자, staging area에 올릴 때: `git add. (file.확장자)`

​		현재 경로 모든 변화 추가: `git add .`

3. 버전을 기록할 때, Commit을 남길 때: `git commit -m '커밋내용'`
4. file의 상태: 
   1. untracked: git이 아직 관리하지 않고 있다.
   2. tracked: add명령어를 통해 Staging Area에 올라간 파일
5. 현재 Local repo의 상태를 확인: `git status`



### 협업과 복구 및 백업

#### 원격 저장소 연결

1. Github에 원격 저장소를 생성합니다.
2. 로컬 저장소를 생성합니다.
3. 원격 저장소에 push하기 전, 반드시 하나 이상의 commit을 기록해야 한다. 

#### 원격 저장소 연결 명령어

1. `git remote add origin(url)` : url을 origin이란 이름으로 원격 저장소로 등록
2. `git remote -v`: 등록한 원격 저장소 정보 ㅗ학인
3. `git push -u origin master` : 로컬에서 생긴 커밋 내용을 업로드
   - `git push`
4. `git pull origin master` 원격 저장소의 변화 사항을 업데이트
5. `git clone(remote repo url)` : 원격 저장소를 복제해온다.(원격-> 로컬): 다운로드 



### Git 브랜치

브랜치 : 흐름의 분기

각각의 브랜치는 하나의 포인터다. 하나의 포인터는 하나의 버전(커밋)을 가리킨다.

마스터는 보통 상용버전을 의미한다.

병렬적이 작업을 위해 브랜치가 존재, 풀푸쉬를 서로 기다리는 것이 아니라 동시에 작업





## @@ Git ignore

로컬 레포를 만들자마자 .gitignore를 만들 것, 한 번 이상 add 한 다음에는 작동하지 않음.

~~~ㅇㅈㅁㅇ
~~~