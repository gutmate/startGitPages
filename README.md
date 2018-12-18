# git 블로그 시작하기

#### 목차

1. [git 설치](#git-설치)
1. [git 명령어](#git-명령어)
1. [github에서 간단하게 사이트 만들기](#github에서-간단하게-사이트-만들기)
1. [jekyll을 사용하여 블로그 만들기](#jekyll을-사용하여-블로그-만들기)

## git 설치

> [Git](https://git-scm.com/)

## git 명령어

#### 최초 설정(필수)

	$ git config --global user.name "user name"
	$ git config --global user.email user.email@example.com

#### 기본 명령어

|  | command |
|-|-|
| 전체 설정 확인 |  `git config --global -l` |
| 저장소 url 변경 |  `git remote set-url <name> <url>` <br> `git remote set-url origin https://github.com/theUBERuid/theUBERuid.git` |
| 상태 확인 |  `git status` |
| 파일을 추적 대상에 등록 |  `git add <file name>` <br> `git add index.html`|
| 파일을 추적 대상에 등록(전체) |  `git add .` |
| 커밋 |  `git commit -m '<commit message>'` <br> `git commit -m 'first commit'`|
| 서버에 업로드 |  `git push <repogitory> <branch>` <br> `git push origin master` |
| 서버에서 다운로드 |  `git clone <repository> <directory>` <br> `git clone https://github.com/theUBERuid/theUBERuid.git theUBERuid`|
| 변경 이력 보기 |  `git log` |


> [누구나 쉽게 이해할 수 있는 Git](https://backlog.com/git-tutorial/kr/)

## github에서 간단하게 사이트 만들기

- 1

## jekyll을 사용하여 블로그 만들기

- 기본 문법 MARKDOWN(*.md)

> [jekyll themes](http://jekyllthemes.org/)

