# 오늘 공부한 내용들!

원형보기 : ctrl + /

- 목록
  - 목록
    - 순서가 없는목록

1. 순서가 있는 목록
2. 아래에는 자동 목록 생성
   1. 수준 낮추어서 진행

기울임:*글자*

굵게:**글자**

취소선:~~취소선~~

코드: ```

`인라인코드`

```python
a = 5
```

```bash
git init
```

```java
public void Java01(){}
```

[표시글자][https://github.com/]

![자바](https://blog.kakaocdn.net/dn/cZsyTw/btq0u5VBWge/F7xmauYA6r8nnbXSz2vJhK/img.png)

인용

> 인용문을 작성한다.
>
> > 겹쳐서도 사용가능

표: ctrl+t

| 파충류 | 조류 | 어류 |
| :----- | ---- | ---- |
|        |      |      |

구분선: ---

글을 구3분할때,

---

구분합니다.

##  GIT
    1.    초기설정    
   ```bash
   git config --global user.name "유저명"
   git config --global user.email "깃허브 메일"
   ```

2. 설정확인

``` bash
git config --global --list
```

3. 폴더를 저장소로 만들기

```bash
git init
```

4. 파일 만들기

```bash
touch README.md
```

5. 무대위로 올리기

```bash
git add README.md
```

6. 파일의 상태를 파악

```bash
git status
```

7. 변경 사항을 기록

```bash
git commit -m "메시지"
```

8. 변경 사항의 내역보기

```bash
git log --oneline
```

---

##	GITHUB에서

1. new repository 만들기
2. url 복사

---

##	연결

1. 연결 하기

```bash
git remote add origin 주소
```

2. 연결 확인

```bash
git remote -v
```

3. 오타난 경우

```bash
git remote rm origin
```

4. 변경사항 백업하기

```bash
git push origin master
```

