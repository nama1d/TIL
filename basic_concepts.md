## CLI

- GUI 와 CLI 

  - GUI: 내가 평소에 보던 아이콘 있는 화면 
  - CLI: 터미널을 통해 사용자와 컴퓨터가 상호 작용

  --> GUI가 더 성능 소모가 심함

- Git Bash는 UNIX 계열 운영체제의 터미널 명령어를 사용



## 경로 

1.  디렉토리

   1. 루트 디렉토리 (Root Directory, /)

      :  최상위 폴더

   2. 홈 디렉토리(Home Directory, ~)

      : C:/사용자(Users)/현재 사용자 계정 



2. 절대 / 상대 경로

   1. 절대 경로

      ex) C:/Users/kyle/Desktop

   2.  상대 경로

      : 현재 작업하고 있는 디렉토리를 기준으로 계산된 상대적 위치

      ex) 현재 작업하고 있는 디렉토리가 C:/Users 라면, 윈도우 바탕 화면으로의 상대 경로는 kyle/Desktop

      \* `./ `: 현재 작업하고 있는 폴더

         `../` : 부모 폴더 





## 명령어

---

### 기본 명령어

1. mkdir 폴더명
  => make directory
  => 새로운 폴더 만들기

  

2. cd 폴더명
  => change directory
  => 폴더로 이동

  

3. touch 파일명
  => 파일 생성

  

4. ls
  => list segments
  => 디렉토리 안 파일들의 리스트

  - ls -a : 숨김파일까지 보여줌
  - ls -l : 확장자, 시간 등 모든 정보를 보여줌

  

5. rm 대상
  => remove
  => 대상 삭제

  - r : 재귀적으로 폴더 하단까지 삭제
  - rf : 강제 삭제

​	**rm으로 삭제한 것은 복구 불가! 최대한 사용 지양**



6. mv
  => move
  => mv 대상1 대상2

  case1) 대상2가 경로상에 존재할 때 
  => 대상1이 대상2 디렉토리 하단으로 이동

  case2) 대상2가 경로상에 존재하지 않을 때
  => 대상1이 대상2로 이름이 바뀜

---

### 추가 명령어

1. pwd
  => present working directory

  

2. ctrl + l
  => 스크롤 내리기 단축키

  

3. clear
  창을 깨끗하게 지우는 명령어(mac 동일)
  => 위로 올라가서 이전 코드 확인이 어렵다.

  

4. 화살표 위,아래
  => 이전 명령어 확인 가능

  

5. GUI 창 열기
  (window) start .
  (mac) open .

  

6. 경로
상대 경로 : . (현재), ..(상위)
절대경로 : /c/Users/student/test





