---
title: "Github 블로그 만들기 2편_Ruby와 Jekyll 설치하기"
date: 2023-11-26 04:16:00 +0900
categories: [blog]
tags: [github Pages, github Blog, blog, velog, github]
---

**"깃허브 블로그를 보다 멋지고 구조화된 형태로 만들기 위해 Jekyll을 활용하고자 합니다. Jekyll을 사용하기 위해서는 Ruby를 설치해야 하는데, 먼저 Jekyll과 Ruby가 무엇인지 알아보고, 설치 및 활용하는 방법을 살펴보겠습니다. "**

---

![JekyllImg](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/4cfd40be-e789-4f3b-884c-94c74a421d12)

# **Jekyll(지킬)이란?**

Jekyll은 Ruby 언어를 통해 개발한 프레임 워크입니다. GitHub 자체적으로 Jekyll CMS(Contents Management System)을 내장하고 있어서 Jekyll 호스팅에 매우 적합합니다. 여기서 중요한건 Jekyll은 Ruby 언어를 기반으로 만들어진 정적(Static) 웹 환경을 위한 프레임 워크라는 것입니다.

Jekyll을 설치하고 사용하기 위해선 루비 명령어와 구조에 대한 기본적인 이해가 필요합니다. Jekyll을 사용하는데 깊은 Ruby 지식이 요구되지는 않지만, 관리하거나 깃허브 블로그를 만들는데 루비환경이 필요합니다.

\*\* 여기서 정적 웹이란?

1. 요청에 따라 미리 저장된 페이지를 응답합니다.

2. 웹 서버가 필요하지 않으므로, 서버 사양에 대한 영향이 적습니다.

3. Back-end 코드가 없어서 제작이 매우 간편하고 속도가 매우 빠릅니다.

4. 복작한 로직이 필요 없는 소규모 사이트에 적합합니다. (예: Github 블로그 등 )

정적 웹 사이트를 만들 때, Jekyll은 콘텐츠를 관리하고 페이지를 생성하는데 매우 유용한 도구입니다.

---

![RubyImg](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/6dbdee8d-d6e7-4fa0-9359-d85d5ee64414)

# **Ruby(루비)란?**

Ruby는 객체 지향적이고 사용하기 쉬운 문법을 가진 스크립트 언어로, 많은 개발자들이 다양한 분야에서 사용하고 있습니다. Jekyll은 Ruby 언어를 활용하여 웹사이트를 생성하고 관리하는데 도움을 주는 도구입니다. 마크다운(Markdown)이나 HTML과 같은 텍스트 파일들로 구성된 컨텐츠를 가지고 정적인 웹사이트를 생성할 수 있게 해주는데, 이런 기능들은 루비 언어의 특성을 활용하여 구현되었습니다.

따라서 Jekyll을 사용하기 위해서는 루비(Ruby) 프로그래밍 언어가 먼저 설치되어 있어야 하며,
Jekyll을 통해 웹사이트를 만들거나 관리하는 데에는 기본적인 루비 언어의 이해가 필요합니다.

---

# **Ruby(루비) 설치 따라하기**

1. Jekyll을 사용하기 위해 Ruby 홈페이지에 접속하여 다운로드 후 실행시켜 설치 합니다.
   ( Ruby+Devkit Installers에서 3.1.3-1(x86) 다운) 3.1.X 버전 아무거나 상관 없습니다.

---

[![RubyInstall1](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/c367f811-a795-4ae1-99db-1da10f748488)](https://rubyinstaller.org/downloads/archives/)

---

![RubyInstall2](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/e7729f7a-1565-455d-be2a-0518b2155b0e)

---

![RubyInstall3](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/71b5c5b5-634b-46c6-a41c-b52727197041)

---

![RubyInstall4](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/5cb9c9e2-d4c4-48d8-8d68-e5e37c9e0885)

---

![RubyInstall5](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/48995c55-b5b5-4d34-96af-d4ede9fa6795)

---

2. 설정하는 모든 체크박스를 체크하여 설치를 진행해줍니다.
   (설치가 끝날 때, Run ‘ridk install’ to setup 체크 후 Finish 버튼을 눌러 커맨드 창으로 넘어갑니다.)

![RubyInstall6](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/c91b1a6e-b8b8-47e8-b037-70655d87f47c)

---

![RubyInstall7](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/ac413295-895f-43db-b2f8-26382249a778)

---

![RubyInstall8](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/9e5a10b9-91be-4727-9e84-e752502a006c)

---

![RubyInstall9](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/f27fa97e-31e0-45e4-a335-67baa540b80f)

---

![RubyInstall10](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/ed149bb9-c956-4a88-9370-e0b7056d9ad6)

---

![RubyInstall11](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/4cd8b524-ac6a-42c0-8a6a-c8889a2a7cd0)

---

3. 커맨드 창에서 Enter를 누르라고 안내할 겁니다. Enter를 눌러서 자동으로 셋업 진행을 합니다.
   (모든 설치가 끝난 후 ruby -v 커맨드를 입력했을 때, 아래와 같이 현재 버전이 출력되면 설치 성공입니다.)

```ruby
 ruby -v
```

---

![RubyInstall12](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/6eed6f99-a15d-4a9d-ba6b-c3030d94b587)

---

![RubyInstall13](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/8f0a8942-f303-4479-9565-71a54a2fecb4)

---

PowerShell에서 ruby -v 검색 후 밑에처럼 뜨면 성공입니다!
ruby 3.1.3p185 (2022-11-24 revision 1a6b16756e)[i386-mingw32]

![RubyInstall14](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/0e0c4715-760f-4003-adbf-8bab7860958b)

다음으로 Jekyll을 설치해보겠습니다. Ruby가 성공적으로 설치되었다면 Jekyll 설치는 매우 쉽습니다.

---

# **Jekyll(지킬) 설치 따라하기**

1. CMD || PowerShell || Git Bash 등의 커맨드 창을 열어서 밑에 커맨드를 입력해줍니다.

```
gem install jekyll // 순서 1
gem install bundler // 순서 2
```

+++ Jekyll을 설치하면서 bundler도 함께 설치해줍니다. bundler는 Ruby 프로젝트에서 gem 파일의 종속성을 관리하는 도구입니다.

![JekyllInstall1](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/1f1fba5b-1e4b-45c0-a4be-bb686e14122e)

---

![JekyllInstall2](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/6c070c42-63c4-421f-a74d-42ff030b51a7)

---

2. 설치가 완료되면 Jekyll, bundler 버전 확인 커맨드를 입력해서 설치가 잘 되었는지 확인해야합니다.

```
jekyll -v
// jekyll 4.3.2 출력

bundler -v
// Bundler version "현재버전" 출력

```

![Confirm Installation](https://github.com/kozneokhan/kozneokhan.github.io/assets/149942572/e33bd1c9-430a-434f-9a26-505e6b597567)

---

# **Github Blog 만들기 2편을 마치며**

이번 포스팅에선 Jekyll과 Ruby에 대해서 알아보았고, 두 가지를 성공적으로 설치하였습니다. 여러분은 이제 Github 블로그 개설을 위한 준비 단계가 끝난 상태입니다. 시작이 반이라는 속담처럼, 이미 5부 능선을 넘으셨습니다! 축하드리며, 다음 포스팅에서 다시 만나뵙겠습니다.
