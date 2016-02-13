---
layout: post
title:  "맥에 워드프레스 설치하기"
date:   2016-02-12 09:46:16 -0800
---

워드프레스 플러그인 개발을 위해 맥에 워드프레스를 설치했다. 간만에 하는거라 걱정했는데 툴들이 잘 되어 있어 많이 고생 안하고 완료했다. 솔직히 전엔 얼마나 어려웠었는지 기억이 나질 않는다.

### 준비물

* [XAMPP](https://www.apachefriends.org/download.html)
* [Wordpress](https://wordpress.org/download/)

### 설치 방법

1. XAMPP application manager에서 MySQL Database 시작 (Apache Web Server는 이미 시작되어 있다)
2. <http://localhost/phpmyadmin>에 접속해서 원하는 이름으로 database 생성
3. [Famous_5-Minute_Install](http://codex.wordpress.org/Installing_WordPress#Famous_5-Minute_Install)
  * /Applications/XAMPP/htdocs 디렉토리에 있는 디렉토리와 파일들 삭제하고 wordpress-x.y.z.zip 파일을 unzip
5. <http://localhost/wp-admin/> 접속해서 Hello world! 포스트가 보이면 성공
