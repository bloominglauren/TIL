# Github 특강 - Basic



## git 이란?

`버전관리` 정도(문서, 사진등 기능적으로 모은 폴더)

#SCM #Source Code Manager #VCS

-우리사이에서 가장 쉽게 볼 수 있는 인공지능은 AI스피커.

통신 상에서 계속 연구 중이다. Why?

1.  아마존 echo dot의 Alexa : 구매용

2. 구글IO(구글자체컨퍼러스) : 

   1)온라인 부킹시스템. 일반적으론 플랫폼 회사를 만들어서 소매점이 참여하게끔이지만 AI로 할 경우 편리성

   2)핸드폰 조작 -> 음성조작 하도록(10배 빠름)

   문맹 소리(음성)-의료쪽 시각/청각 - 인공지능 머닝러신-

   quick draw, Auto draw.

   

## git 설치
1. git-scm.com에서 다운로드
2. 계속 next로 설치



# git 사용법

### 최초설정

처음 컴퓨터에 git를 설치하면, 사용자의 이메일과 이름을 적어둔다. 이는 앞으로 일어나는 커밋에 서명을 하기 위해서 필요하다.

```
$ git config --global user.name "<당신의 이름>"
$ git config --global user.email "<당신의>@<이메일>"
```

잘 설정되었나 확인하려면

```
$ git config user.name
이름 출력

$ git config user.email
이메일 출력
```



### 상태 점검



### 초기화

초기화는 `git init` 을 통해 진행한다.

```
$ git init
```



### add하기

### commit 하기

### log 보기



## Summary

| 명령어                             | 설명                                                         |
| ---------------------------------- | ------------------------------------------------------------ |
| `$ git init`                       | 빈 디렉토리(폴더)를 git 저장소(repo)로 초기화 한다.          |
| `$ git add <filename>`             | `<filename>`을 Stage 에 올린다                               |
| `$ git commit -m "commit message"` |                                                              |
|                                    | $ git add new.txt
$ git commit -m 'new.txt 추가 / 내맘대로 메시지' |

Typora 설정

파일 => 설정 => 이미지 => 드랍다운 3번(./${filename}.assets 경로로 이미지 복사 => 체크박스 3번(가능하다면 상대적 위치 사용)






git-scm.com에서 다운로드 계속 next로 설치



git사용법

