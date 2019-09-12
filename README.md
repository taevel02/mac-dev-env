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
- 시스템 아이콘 표시
- 트랙패드 설정
- Finder 환경설정

[한영전환키 caps lock으로 변경](https://extrememanual.net/12068)

- Dock 크기 - Small, Medium 사이
- 디스플레이 크기 - 1680 * 1050

#### Homebrew를 이용한 프로그램 설치
```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ git clone git@github.com:taevel02/mac-setup.git
$ cd mac-setup
$ brew bundle
```

## 폰트
- [FiraCode](https://github.com/tonsky/FiraCode)
- [Noto Sans](https://www.google.com/get/noto/#sans-lgc)
- [Noto Sans CJK KR](https://www.google.com/get/noto/#sans-kore)
- [Spoqa Han Sans](https://spoqa.github.io/spoqa-han-sans)
- [Nanum](https://hangeul.naver.com/2017/nanum)

## 터미널
- [iTerm2](https://www.iterm2.com/)
- iTerm2 Color Scheme - [Snazzy](https://github.com/mbadolato/iTerm2-Color-Schemes/blob/master/schemes/Snazzy.itermcolors)
- oh-my-zsh
```bash
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
- zsh-theme - [Pure](https://github.com/sindresorhus/pure)
- ~/.zshrc
```
alias python=python3
alias pip=pip3
```

## 커맨드라인 인터페이스 도구
- [n](https://github.com/tj/n) - 노드 버전 관리
- git
```bash
$ git config --global user.name "taevel02"
$ git config --global user.email "taevel02@gmail.com"
```
- [zsh plugin](https://heetop.blogspot.com/2017/10/oh-my-zsh_12.html)

## 언어
- vue cli
```bash
$ yarn global add @vue/cli
$ yarn global add create-react-app
```

## 프로그램 직접 설치
- Adobe Photoshop CC, Lightroom CC, XD
- Microsoft Office - PowerPoint, Excel, Word

## 크롬 확장 프로그램
- AdBlock
- ColorPick Eyedropper
- Full Page Screen Captur
- HTTPS Everywhere
- Naver Cafe Free Pass
- Notion Web Clipper

## Visual Studio Code Setting
- [setting-sync](https://gist.github.com/taevel02/565a51aaf3ed1820faaa25e6cfc11518)
