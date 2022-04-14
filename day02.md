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
3. 1  이동과 동시에 브랜치 생성
   ```bash
   git switch -c hotfix
   ```
   
4. 브랜치 병합
   ```bash
   git merge 브랜치명
   ```
5. 브랜치 삭제
   ```bash
   git branch -d (삭제)
   git branch -D (강제삭제)
   ```
6. 그래프로 로그 확인
   ```bash
   git log --oneline --all --araph
   ```