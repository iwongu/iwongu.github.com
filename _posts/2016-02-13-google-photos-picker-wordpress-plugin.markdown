---
layout: post
title:  "Google Photos Picker 워드프레스 플러그인"
date:   2016-02-13 20:46:16 -0800
---

맥에 워드프레스 설치하고 Google Photos에서 사진을 고를 수 있는 플러그인을 만들기 시작했는데 하루만에 완성되어 버렸다. 역시 코딩은 구글링으로 해야.

아직 wordpress.org 플러그인 페이지에 등록하진 않았고 [github](https://github.com/iwongu/photos-picker)에 올려놨다.

포스트 에디터에 있는 *google photos picker* 버튼을 누르면 Google Picker 창이 뜨고 사진들을 선택하면 포스트에 img 태그로 삽입된다.

![](https://lh3.googleusercontent.com/-16uUMQhiZAQ/VsAKaAwmNzI/AAAAAAAGLpk/KcJIqqj36a0/s2048/screenshot-2.png)

사용하려면 Google Developers Console에서 API 키와 OAuth 2.0 client ID를 받아야 한다.

* [Google Developers Console](https://console.developers.google.com)에서 *Project* 생성한다.
* *Google Picker API* 활성화한다.
* *API key* (Browser key) 생성한다.
* *OAuth 2.0 client ID* 생성한다.
  * 설정에서 *Authorized JavaScript origins*에 블로그 hostname을 등록한다.
* 10분 정도 기다린다.
* 생성한 키들을 워드프레스 관리자 화면 *Settings* -> *Media* -> *Google Photos Picker plugin settings*에 등록한다.


# Update

wordpress.org에서 플러그인 이름에 트레이드마크가 들어갔다는 이유로 거부 메일을 받았다. 이름을 Google Photos Picker에서 Photos Picker로 바꿔서 다시 신청.

# Update #2

등록 완료 [https://wordpress.org/plugins/photos-picker/        ](https://wordpress.org/plugins/photos-picker/)