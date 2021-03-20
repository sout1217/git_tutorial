# 📌 읽기전
1. {xxx} 는 argument 입니다
2. [xxx] 는 생략 가능 argument 입니다

<br>

##  📌 깃 버전
`working directory > stage > local repository > remote repository`

`작업 디렉토리 > 스테이지 > 로컬 저장소 > 원격 저장소`

<br>  

##  📌 깃 버전
`git --version`

<br>

##  📌 깃 Bash 창 내용 지우기
`clear` or `ctrl + l`  

<br>

##  📌 깃 콘픽 설정
`git config --global user.name "이름"`  
`git config --global user.email "이메일"`  
`git config --global color.ui auto`

<br>

##  📌 깃 콘픽 설정 보기
`git config -l`

<br>

##  📌 디렉토리 생성
`mkdir 파일명`

<br>

##  📌 디렉토리 보기
`ls` : 파일 보기 (.git 디렉토리 안보임)

`ls -a` : 모든 파일 보기

<br>

##  📌 깃 시작
`git init`

<br>

##  📌 깃 제거
`rm -rf .git`

`rm -rf {파일 또는 디렉토리}` : 묻지 않고 바로 제거

<br>

##  📌 파일 생성
`touch {파일명}`

 ex) `touch index.html`


<br>

##  📌 깃 현재 상태 보기
`git status` : branch, untracked,  new file, modified, deleted 등 정보를 알 수 있다


`branch` : 브랜치 정보  
`untracked` : `working directory` 에 있는 파일 (한 번도 `add` 가 되지 않은 파일)  
`new file` : `working directory` 에서 `add` 를 통행 `stage` 로 넘어온 파일  
`modified` : 한 번 `commit` 되고 나서 수정 된 경우  
`deleted` : `stage` 또는 `local repository` 에서 삭제된 경우


<br>

##  📌 깃 add
`git add {파일명}` : `working directory` 의 해당 파일을 `stage` 에 이동

`git add .` : 현재 디렉토리의 `working directory` 의 파일을 모두 `stage` 에 이동

`git add -A` or `git add --all` : `working directory` 의 파일을 모두 `stage` 에 이동

<br>

##  📌 깃 commit
`git commit -m {메시지}`






