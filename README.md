# 글자

## 글자

### 샵으로 h1 ~ h6태그 처럼 처리 가능

일반 글을 작성하여
줄바꿈을 하려고 엔터를 치면
줄바꿈 처리가 불가능 하다
그래서 줄바꿈 처리를 위해선 <br>
br태그를 이용 하여 줄바꿈 가능

- 목록이 없는 리스트는 \*로 표기
  - 테두리만 있는 리스트는 tab으로 들여쓰기로 작성

## git 명령어

### 사용자 등록

    > git config --global user.name     "아이디명"
    > git config --global user.email    "이메일주소"

### 사용자 삭제 (방법)

    > git config --unset --global   user.name
    > git config --unset --global   user.email

### 1. 초기화

    > git init

### 2. 저장소 등록 (연동)

    > git remote add origin 저장소 주소

### 2-1. 저장소 등록 삭제 (잘못 등록시)

    > git remote rm origin

### 3. 현 시점 스테이지 저장

    > git add .

### 4. 커밋 (기록 저장)

    > git commit -m "커밋 내용"

### 5. 업로드 (push)

    > git push origin master

### 5-1. 업로드 이슈 일 때

    > git push origin main

### 6. 내려받기

    > 윈도우: cmd을 실행 후 다운 받을 경로 지정
    > Mac: 터미널 실행 후 다운 받을 경로 지정
    >git clone 저장소 주소

### 7. 저장소 (레포지토리)에 올라간 최신 커밋을 내려 받을 때

    > git pull

### 8. 깃 로그 확인

    >git log

### 9. 깃허브에서 내려 받은 폴더가 잘 연결이 되었는지 확인

    > git remote -v
    > fetch: 내려 받은 저장소
    > push: 올릴 때 저장소
