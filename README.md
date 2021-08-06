# mac-setup
Personal Mac OS SetUp

#### 맥 초기화 및 기본 세팅
[애플 제공](https://support.apple.com/ko-kr/HT204904)

- command-R : 이후 버전으로 업그레이드하지 않고 Mac에 설치되어 있던 최신 macOS를 설치합니다.
- option-command-R : Mac과 호환되는 최신 macOS로 업그레이드합니다
- shift-option-command-R: Mac과 함께 제공되는 macOS 또는 현재 사용할 수 있는 macOS 중 최신 버전을 설치합니다.

[맥 기본 설정](https://macclub.tistory.com/228)

- 소프트웨어 업데이트
- Finder 윈도우 정렬
- 게이트키퍼 끄기
- 트랙패드 설정
- Finder 환경설정

[한영전환키 caps lock으로 변경](https://extrememanual.net/12068)

- Dock 크기 - Small, Medium 사이
- 디스플레이 크기 - default

#### Homebrew를 이용한 프로그램 설치
```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ git clone https://github.com/taevel02/mac-setup.git
$ cd mac-setup
$ brew bundle
```

## 폰트
- [FiraCode](https://github.com/tonsky/FiraCode)
- [Noto Sans](https://www.google.com/get/noto/#sans-lgc)
- [Noto Sans CJK KR](https://www.google.com/get/noto/#sans-kore)
- [Spoqa Han Sans Neo](https://spoqa.github.io/spoqa-han-sans)
- [Nanum](https://hangeul.naver.com/2017/nanum)
- [Pretendard](https://cactus.tistory.com/306)

## 터미널
- [iTerm2](https://www.iterm2.com/)
- iTerm2 Color Scheme - [Snazzy](https://github.com/mbadolato/iTerm2-Color-Schemes/blob/master/schemes/Snazzy.itermcolors)
- oh-my-zsh
```bash
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
- [개발 환경 기초 세팅](https://subicura.com/2017/11/22/mac-os-development-environment-setup.html)

## SSH 설정
```bash
$ ssh-keygen -t rsa -C "git" -b 4096
$ cat ~/.ssh/id_rsa.pub
```
ssh값 확인하여 github, gitlab ssh 

## 프로그램
- VSCode, Xcode, iTerm, Postman, Robo 3T
- Notion, Keynote, Pages, Numbers, PowerPoint, Docs, Excel, HancomViewer
- KaKaoTalk, Slack, Spark
- AppCleaner, Keka, Magnet, IINA, HiddenBar, eul, Unicorn Blocker, Grammarly in Safari
- Chrome

## Visual Studio Code Setting
- [setting-sync](https://gist.github.com/taevel02/565a51aaf3ed1820faaa25e6cfc11518)
