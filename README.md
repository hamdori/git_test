# DSC 웹세션 저장소 입니다 // html h1
DSC 세션에서 작성하였습니다

# git init : 초기화
# git config --global user.name "user name"// 로그인
# git config --global user.email "email" // 로그인
# git remote add origin <git remote repository>

연결된 것 보기
# git remote -v

파일 추가

staging area에 변경된 내용을 올려주자
# git add . // 전체 파일 올리기
# git add README.md // 리드미 파일만 올려주세요

# git commit -m "변경된 내용"

원격 저장소에 프로젝트 발행
# git push -u origin master

# git checkout -b <브랜치명> // 브랜치 추가
# git branch -d <브랜치명> // 브랜치 삭제
# git merge <브랜치명> // 브랜치 합치기
# git pull // 변경내용 갱신(원격 저장소에서 로컬로)
# git clone <url 주소> // 저장소 복제
# git fork // 저장소 요청(내 저장소에 새로 생기고 거기서 수정)
# git set -url <변경된 원격 저장소 주소> // 원격 저장소 변경
# git reset --hard <commit 해시> // commit 해시는 github에 있는 코드
(git clone 으로 새 프로젝트 생성 후 진행 권장, commit reset)

# .gitignore // 검색 결과를 .gitignore 파일 안에 붙여넣기 (저장소에 올리기 싫은 내용) 