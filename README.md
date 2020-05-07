# LIKE LION, DSC SYU 웹세션 GIT TEXT
#붙은 텍스트=html h1<br>

# 0. TEST LIST
LIKE LION SYU, DSC SYU 세션
<br>

# 1. READY
git init <br>
초기화 <br>
git config --global user.name "user name" <br>
유저네임 로그인 <br>
git config --global user.email "email" <br>
이메일 로그인 <br>
git remote add origin <git remote repository> <br>
원격 저장소 레포지 추가 <br>
git remote -v <br>
레포지 연결 확인 <br>
<br>

# 2. Staging Area에 변경된 내용을 올려주자
<h3>1-1. git add .</h3> <br>
전체 파일 올리기 <br>
<h3>1-2. git add README.md</h3> <br>
리드미 파일만 올리기 <br>
<h3>2-1. git commit -m "변경된 내용" </h3><br>
변경된 내용 커밋 <br>
<h3>2-2. git reset HEAD^</h3> <br>
완료한 커밋 취소 <br>
<h3>3-1. git push -u origin master </h3><br>
원격 저장소에 프로젝트 발행 <br>
<h3>3-2. git push -u origin +master</h3> <br>
오류 무시하고 원격 저장소에 강제 푸쉬 <br>
<br>

# 3. 브랜치 명령어
git checkout -b <브랜치명> <br>
브랜치 추가 <br>
git branch -d <브랜치명> <br>
브랜치 삭제 <br>
git merge <브랜치명> <br>
브랜치 합치기 <br>
<br>

# 4. 기타 명령어
git pull <br>
변경내용 갱신(원격 저장소에서 로컬로) <br>
git clone <url 주소> <br>
저장소 복제 <br>
git fork <br>
저장소 요청(내 저장소에 새로 생기고 거기서 수정) <br>
git set -url <변경된 원격 저장소 주소> <br>
원격 저장소 변경 <br>
git reset --hard <commit 해시> <br>
commit 해시는 github에 있는 코드 <br>
(git clone 으로 새 프로젝트 생성 후 진행 권장, commit reset) <br>
.gitignore<br>
검색 결과를 .gitignore 파일 안에 붙여넣기 (저장소에 올리기 싫은 내용) 