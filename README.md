# git 블로그 시작하기

#### 목차

1. [github pages(GIT 블로그)](#github-pages)
1. [git 설치](#git-설치)
1. [git 명령어](#git-명령어)
1. [github에서 간단하게 사이트 만들기](#github에서-간단하게-사이트-만들기)
1. [jekyll을 사용하여 블로그 만들기](#jekyll을-사용하여-블로그-만들기)

## github pages 장점

|  | 구축형 (Wordpress) | 가입형 (Tistory) | GitHub Pages |
|:--:|:--:|:--:|:--:|
| 비용 | 유료(서버+네트웍) | 무료 | 무료 |
| 서버 구축 | 필요함 | 필요없음 | 필요없음 |
| 네트워크 설정 | 필요함 | 필요없음 | 필요없음 |
| Markdown | 가능 | 불가능(제한적) | 가능 |
| HTML 편집 | 가능 | 불가능(제한적) | 가능 |

> markdown이란?<br><br>
> 마크다운은 HTML 보다 더 빨리 입력할 수 있고, 배우는데 드는 시간도 적으며 일반적인 글자 서식을 적용하는데 사용할 수 있다. 기울이기, 인용문 넣기, 여러 수준의 제목 추가(h1, h2, h3...), 숫자/글 머리 기호 목록 작성, 취소선 긋기 같은 서식들. URL 링크, 이메일 링크, 이미지, 주석과 주석 링크, 간단한 표를 넣는데도 사용 가능하다.<br><br>
> 마크다운은 지원하는 환경이라면 어디서든 쓸 수 있으며 복사해서 옮겨도 서식이 깨지지 않는다.

## git 설치

>[Git](https://git-scm.com/)

## git 명령어

#### 최초 설정(필수)

	$ git config --global user.name 'user name'
	$ git config --global user.email 'user.email@example.com'

#### 기본 명령어

|  | command |
|-|-|
| 전체 설정 확인 |  `git config --global -l` |
| 저장소 url 변경 |  `git remote set-url <name> <url>` <br> `git remote set-url origin https://github.com/theUBERuid/theUBERuid.github.io.git` |
| 상태 확인 |  `git status` |
| 파일을 추적 대상에 등록 |  `git add <file name>` <br> `git add index.html`|
| 파일을 추적 대상에 등록(전체) |  `git add .` |
| 커밋 |  `git commit -m '<commit message>'` <br> `git commit -m 'first commit'`|
| 서버에 업로드 |  `git push <repogitory> <branch>` <br> `git push origin master` |
| 서버에서 다운로드 |  `git clone <repository> <directory>` <br> `git clone https://github.com/theUBERuid/theUBERuid.github.io.git theUBERuid`|
| 변경 이력 보기 |  `git log` |


>[누구나 쉽게 이해할 수 있는 Git](https://backlog.com/git-tutorial/kr/)

## github에서 간단하게 사이트 만들기

- repo

>[theUBERuid.github.io](https://github.com/theUBERuid/theUBERuid.github.io)

## jekyll을 사용하여 블로그 만들기

#### 원리



#### 포스팅

- 파일 이름 `_posts/YYYY-MM-DD-name-of-post.ext`
- 기본 문법 MARKDOWN(*.md)

>[jekyll themes](http://jekyllthemes.org/)

## github를 이용한 블로그

>[kakao 기술 블로그](http://tech.kakao.com/)

>[우아한형제들 기술 블로그](http://woowabros.github.io/)

## 참고 사이트

>[누구나 쉽게 이해할 수 있는 Git](https://backlog.com/git-tutorial/kr/)

>[윈도우에서 지킬 설치 및 블로그 생성하기](https://shryu8902.github.io/jekyll/jekyll-on-windows/)

