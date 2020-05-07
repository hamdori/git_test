# LIKE LION, nDSC 웹세션 GIT TEXT
#붙은 텍스트=html h1<br>

# TEST LIST
LIKE LION SYU, DSC SYU 세션
<br>

# git init
초기화
# git config --global user.name "user name"
유저네임 로그인
# git config --global user.email "email"
이메일 로그인
# git remote add origin <git remote repository>
원격 저장소 레포지 추가
# git remote -v
레포지 연결 확인

# Staging Area에 변경된 내용을 올려주자
# git add . 
전체 파일 올리기
# git add README.md
리드미 파일만 올리기
# git commit -m "변경된 내용"
변경된 내용 커밋
# git push -u origin master
원격 저장소에 프로젝트 발행
<br>

# git checkout -b <브랜치명>
브랜치 추가
# git branch -d <브랜치명>
브랜치 삭제
# git merge <브랜치명>
브랜치 합치기
<br>

# git pull
변경내용 갱신(원격 저장소에서 로컬로)
# git clone <url 주소>
저장소 복제
# git fork
저장소 요청(내 저장소에 새로 생기고 거기서 수정)
# git set -url <변경된 원격 저장소 주소>
원격 저장소 변경
# git reset --hard <commit 해시>
commit 해시는 github에 있는 코드
(git clone 으로 새 프로젝트 생성 후 진행 권장, commit reset)

# .gitignore
검색 결과를 .gitignore 파일 안에 붙여넣기 (저장소에 올리기 싫은 내용) 