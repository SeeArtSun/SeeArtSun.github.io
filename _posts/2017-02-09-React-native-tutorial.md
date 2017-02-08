---
layout: post
title: React-native Tutorial
---

# What is React-native?
* iOS 와 Android App.을 JavaScript환경에서 Native로 개발할 수 있게 하는 Framework
* Facebook의 React를 모바일로

# Install React-native
##개발 환경 구성
* Node.js, iOS, Android를 위한 기본 설정 필요

{% highlight js %}
// install [Homebrew](http://brew.sh/)(OS X 패키지 관리 )
$/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

/*
  만약 Homebrew 설치하기 전에 Node.js가 이미 설치되어 있다면 아래 명령어 추가

  $ brew uninstall --force node
  $ git clone git://github.com/creationix/nvm.git ~/.nvm
 printf "\n\n# NVM\nif [ -s ~/.nvm/nvm.sh ]; then\n\tNVM_DIR=~/.nvm\n\tsource ~/.nvm/nvm.sh\nfi" >> ~/.bashrc
 NVM_DIR=~/.nvm
 source ~/.nvm/nvm.sh
*/

//install watchman(변경추적)
$ brew install watchman
// install flow(JavaScript 정적분석)
$ brew install flow
{% endhighlight %}

* Node.js-4.0 이상의 버전 필요.

{% highlight js %}
// install [nvm](https://github.com/creationix/nvm)
//(Node.js 버전관리자로 개발 환경을 독립적으로 관리하기에 편리)
$ brew install nvm
$ nvm install Node
// to set default Node version
$ nvm alias default node
{% endhighlight %}

### iOS 개발환경 설정
* [Xcode](https://developer.apple.com/xcode/) 설치
* 끝.

### Android 개발환경 설정
* [JDK(Java SE development Kit) 설치](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* Android SDK 설치
{% highlight js %}
// Android SDK 설치
$ brew install android-sdk

// 환경 변수 ANDROID_HOME 설정
// export ANDROID_HOME=경로
// ex)
$ export ANDROID_HOME=/usr/local/opt/android-sdk
{% endhighlight %}


오늘은 여기까지 헤헤
