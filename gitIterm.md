# git 터미널 명령어
git --version : 깃 버전 확인<br>
git config --global init.defaultBranch main : 깃 설치 후 최초 1회만 실행(대충 오류 방지)<br>
git config --global user.name "이름" : 유저네임 세팅<br>
git config --global user.email "이메일" : 유저이메일 세팅<br>
git config --list : 제대로 되었는지 확인<br>
<br>
ls : 폴더 조회<br>
cd 폴더명 : 폴더로 들어가기<br>
cd .. : 상위폴더로 나가기<br>
mkdir 폴더명 : 폴더 만들기<br>
<br>
git init : .git.폴더 생성 (깃 관리의 시작)<br>
git status : 현재 깃 상태를 보여줌<br>
git add (.) : 파일 추적 (.은 모두를 의미)<br>
git commit -m "메세지" : 커밋 "커밋내용작성"<br>
git log : 커밋로그 확인<br>
git reset --hard : 수정전 커밋으로 롤백<br>
git reset --hard 커밋해쉬코드(번호) : 해당하는 번호 커밋으로 롤백<br>
<br>
git remote add origin 리포지토리 주소 : 리포지토리 연결<br>
git push origin main : 리포지토리에 커밋들을 넣는다<br>
git clone 리포지토리 주소 : 리포지토리에서 모든 커밋들을 내 로컬로 가져옴.<br>
git pull origin main : 서버 변동사항을 로컬로 동기화<br>
<br>
.gitignore : 원하지 않는 파일을 안 올릴 수 있는 방법 (확장자를 없앤 파일에 .txt 등 쓰고 저장하면 무시됨)<br>
<br>
git branch : 생성된 브랜치의 목록<br>
git branch 이름: 브랜치 만들기<br>
git checkout 이름 : 이름이라는 브랜치로 이동<br>
