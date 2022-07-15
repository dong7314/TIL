# TIL
# 0715



## Git Bash(명령어)

- ls : 목록을 본다

- ls -al : 숨김 등 목록의 전체를 본다

- mkdir : 디렉토리 생성 명령어 ex) mkdir cli-test

- pwd : 현재 위치보기

- cd 경로 : 경로 위치로 이동하기 ex) cd cli-test

-  touch : 파일 생성하기 ex) touch test1.txt

- cd ~ : 현재 홈 디렉토리로 이동

- cd .. : 상위 디렉토리로 이동

- cd 절대경로 : 절대경로로 바로 이동 ex) cd /c/이동엽/00_StartCamp/0715

- start : 파일을 실행시킨다 ex) start test1.txt

- rm : 파일 제거 ex) rm test2.txt

- rm -r : 폴더 제거 ex) rm -r folder1

  

## 절대 경로

- 루트 디렉토리부터 목적 지점까지 거치는 모든 경로를 전부 작성한 것
- 윈도우 바탕 화면의 절대 경로 -C:/Users/ssafy/Desktop

## 상대 경로

- 현재 작업하고 있는 디렉토리를 기준으로 계산된 상대적 위치를 작성한 것
- 현재 작업하고 있는 디렉토리가 C:/Users일 때 윈도우 바탕 화면으로의 상대 경로는 ssafy/Desktopp
- ./ : 현재 작업하고 있는 폴더                             ../ : 현재 작업하고 있는 폴더의 부모 폴더



## Markdown

- 텍스트 기반의 *가벼운 마크업*  언어
- 문서의 구조와 내용을 같이 쉽고 빠르게 적고자 탄생
  - 마크업 : 태크를 이용하여 문서의 구조를 나타내는 것

### github

- 깃헙 또한 README.md로 파일이 구성되어 있다.
- 개인 프로젝트의 소개 문서 작성
- 매일 학습한 내용 정리
- 마크다운을 이용한 블로그 운영





## typora

- 실시간 마크다운 변환 제공
- 이미지 또는 표 삽입시 매우 편함



### 단축키

 - `#` : 제목(h1 ~ h6)
- `*` : 기울기
- `**` : 굵게
- `~~` : 취소선
- `>` : 주석 달기

- `1. 2. 3. or - ` : 리스트이며 목록을 생성한다.
- `[string](url)` : 링크를 다는 명령으로 string이 실제 보여지는 문장 url이 연결할 곳을 나타낸다.
- `![string](img_url)` : 이미지를 삽입한다.
- `---` : 수평선 생성하기
- ````python` : 코드 블럭
- '`' : 인라인 코드 블럭
- ctrl + t : 표 생성



https://www.markdownguide.org/cheat-sheet/



## Git 기본기

- **특정 버전**으로 남긴다 = "**커밋(commit)** 한다"

- Working Directory(실제 작업 디렉토리) -> Staging Area -> Repository(커밋들이 저장되는 곳)

  ​															-> git add				-> git commit

  

### repository

- 특정 디렉토리를 버전 관리하는 저장소
- git init 명령어로 로컬 저장소를 생성
- .git 디렉토리에 버전 관리에 필요한 모든 것이 들어 있음



![image-20220715141622656](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715141622656.png)

![image-20220715141710081](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715141710081.png)

![image-20220715142010081](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715142010081.png)

​																	git add .  :  현 디렉토리의 전체 파일

![image-20220715142110828](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715142110828.png)

![image-20220715142238843](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715142238843.png)

​												    	커밋 시  ->  git commit -m "커밋 메세지"

![image-20220715142511421](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715142511421.png)

![image-20220715142601834](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715142601834.png)

![image-20220715142611203](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715142611203.png)

![image-20220715142741171](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715142741171.png)

![image-20220715142953243](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715142953243.png)

​														554977c 가 각 아이디를 나타내는 해쉬 값이다.

​																		readme.md **업데이트** 후

![image-20220715143402854](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715143402854.png)

![image-20220715143430275](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715143430275.png)

![image-20220715143445142](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715143445142.png)

![image-20220715151548672](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715151548672.png)



## github

- git remote add origin {remote_repo} -> remote_repo에는 url을 넣는다.
- git push -u origin master

![image-20220715154633185](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715154633185.png)

![image-20220715154903060](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715154903060.png)

- git clone {remote_repo} remote repo를 local롤 복사합니다
- git push origin master

![image-20220715160936671](C:\Users\multicampus\AppData\Roaming\Typora\typora-user-images\image-20220715160936671.png)

윈도우 자격 증명 에서 정보를 지우고 이동해야 한다.



## TIL

#### Today I Learned

- 매일 내가 배운 것을 마크다운으로 정리해서 문서화
- 신입 개발자에게 요구되는 가장 큰 능력, 꾸준히 학습?
- Github 관리 능력

