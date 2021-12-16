---
layout: post
title:  "git&github"
date:   2021-12-16 19:10:20 +0900
categories: jekyll update
comments: true
---

Explain about git
---
git이란 소스코드 관리를 위해 나온 시스템으로 모든 코드작업의 대해 기록, 추적이 가능한 정보들을 가지고있다. 또한 다양한 명령어를 이용하여 git서버와 컴퓨터를 연동한다.

Explain about github
---
github란 소스코드를 자유롭게 열람할 수 있고 버그관리와 같은 기능이 있는 소프트웨어 소스코드 관리 서비스이다.

git 명령어
---
#git clone
아래 명령어를 이용하여 local repository를 git과 연동한다.
```bash
$ git clone {git_url}
```
#git add, commit
add 명령어를 이용하여 stage 상태로 추가하고 commit 명령어를 이용하여 해당 파일에 대한 메세지를 기록한다.
```bash
$ git add {filename}
$ git commit -m "message"
```
#git pull
아래 명령어를 이용하여 git에 업데이트된 내용을 가져온다.
```bash
$ git pull
```
#git push
아래 명령어를 이용하여 stage상태의 파일들을 git에 등록한다.
```bash
$ git push
```
