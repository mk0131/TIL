# 오늘 공부한 내용들

##  GIT branch
1.  브랜치 목록 확인
```bash 
git branch
```
2.  브랜치 생성
   ```bash
   git branch 브랜치명
   ```
3.  브랜치 이동
   ```bash
   git switch 브랜치명
   ```
4.  이동과 동시에 브랜치 생성
   ```bash
   git switch -c hotfix
   ```
   5. 브랜치 병합
   ```bash
   git merge 브랜치명
   ```
   6. 브랜치 삭제
   ```bash
   git branch -d (삭제)
   git branch -D (강제삭제)
   ```
   7. 그래프로 로그 확인
   ```bash
   git log --oneline --all --araph
   ```
   
## fork 하는 방법
-  repo 를 fork 한다
-  git clone url 해서 로컬로 가지고온다.
-  git remote add upstream 원본url 해서 연결한다.
-  vscode를 열고 git branch 를 만든다.
-  git switch로 branch 이동후 작업
-  add -> commit -> push
-  git push origin branch
-  github 가서 pull requset
