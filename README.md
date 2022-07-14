## README.md 파일 만들기입니다.

### 오늘의 TIL입니다.

레포는 무엇을 할 지 정해지지 않은 관계로 오늘은 마크다운 문법 복습을 해보겠습니다.

# 제목 1입니다#

## 제목 2입니다##



### 리스트

#### 순서가 있는 리스트

1. 순서가 있는 리스트1.
   1. 탭을 누르면 하위 리스트로 갈 수 있다

#### 순서가 없는 리스트



* 순서가 없는 리스트 *
  * 탭을 누르면 하위 리스트로 갈 수 있다.



#### 코드리스트

백틱 3번(```)을 누른다. 원하는 언어를 고른 후 백틱을 다시 세 번 하면 코드블럭 완성 

```python
print('hi')
a = 'a'
sdsada
```



백틱 1번은 코드 삽입

우리는 파이썬에서 콘솔화면에 글자를 출력하기위해 `print()`함수를 사용합니다.

#### 링크url

대괄호 [스트링(안에 표시명)] 대괄호  소괄호 (주소)소괄호 식으로



ex) 

[google](http://www.google.com)









![img](C:\Users\multicampus\Pictures\8.jpg)









#### 별표나 언더바로 볼드 이태릭 취소선등

별표하나 (\*str*)

*sdasdad*

별표 둘 (\**ㅇㅈㅁㅇ**)

**ㅇㄴㅁㅇㅈㅉ**

별표 셋 (\*\*\* *str***)

***wdwad***

[Google](http://www.google.co.kr)

물결표 둘 ( ~~~~ㅇㅈㅁㅇ~~~~)



~~ㅇㅈㅁ~~





~~~ㅇㅈㅁ~~~



~~~

## TIL 

## Remote Repository 연결하기

### Remote Repo 생성하기

1. 기본 브랜치 이름 master로 변경하기
2. new Repo 생성 버튼 눌러서
   1. 이름 설정
   2. 만들기

### Local



1. 새로운 디렉토리 생성:

   

   1. mkdir
   2. cd(경로)
   3. git init
   4. git remote add origin (원격 레포 주소url)
   5. git remote: origin 이름으로 remote 추가된 것 확인
   6. touch README.md

2. 버전 남기기(remote repo로 push하기 전에 반드시 commit이 있어야 한다)

   1. git add( 파일명.확장자)
      1. git.add . (현재 위치 wd 모든 변경사항 추가)
   2. git commit -m 'first commit'

3. git push origin master


이 밑으로는 깃허브 웹상에서 원격레포를 직접 수정한 내용입니다.
원격 레포를 직접 수정할 경우 바로 커밋됨. 이 떄 로컬 레포들이 업데이트 되지 않을 경우 로컬 레포들과 차이가 생김, 나중에 충돌 가능성 높음, 충돌시 vim으로 통합 작업해야함.

