## Git Training

### Description of Git
> Version Control System
- 파일의 이름을 변경하지 않고 파일의 버전을 관리할 수 있다는 것이  git 의 맹점
- Backup : 내 코드 백업 가능
- Recovery : 코드를 이전으로 돌릴 수 있음
- Collaboration : 협업 하는데 편리
- example) CVS, SVN, GIT

> Git is incredibly **complex**

### Make a repository
~~~
> pwd : 현재 위치를 알려줌

> mkdir : 폴더 생성

> ls -al : 현재 디렉토리의 파일명을 보여줌

> git init : 현재 디렉토리를 git의 (버전) 저장소로 만듦
~~~~

### git add
~~~
> vim file_name.txt : file_name.txt 파일 생성과 동시에 vim 에디터로 편집

> cat file_name.txt : file_name.txt 파일 내용을 콘솔에 출력

> git status : 현재 git으로 관리되는 디렉토리의 버전관리 현황 출력

> git add file_name.txt : file_name 파일을 git 버전관리 목록에 추가
~~~
- vim 명령어
~~~
> i : insert mode

> h,j,k,l : 방향키

> o : 개행 후 insert mode 진입

> shift + o : 이전 행에서 개행 후 insert mode 진입

> shift + h : 문서의 처음으로 커서 이동

> shift + l : 문서의 마지막 라인의 처음으로 커서 이동
~~~

### Commit
- 버전에 포함될 버전을 만든 사람에 대한 정보를 설정
- 이 설정은 ~/.gitconfig 파일에 저장되고 1번만 설정하면 됨
~~~
> git config --global user.name "자신의 닉네임"
> git config --global user.email "자신의 이메일"
~~~
