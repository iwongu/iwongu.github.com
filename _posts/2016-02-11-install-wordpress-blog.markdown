---
layout: post
title:  "워드프레스 블로그 설치"
date:   2016-02-11 21:46:16 -0800
---

2-3년마다 도지는 블로그 설치 병에 걸려 워드프레스를 설치했다. 마지막 같은 병에 걸렸을 땐 Google Appengine에 [코드](https://github.com/iwongu/blogae) 짜서 올리기까지 했으나 역시 결론은 워드프레스.

wordpress.com에 백업을 받아 하루 놀아 봤는데 역시 설치형이 아니라 답답하다. 도메인 연결 비용도 그리 싸지 않고.

호스팅 업체를 찾다가 ehost.com으로 결정. 재밌는건 ehost.com에 50% 할인 링크를 타고 들어갔다가 결정을 못하고 나오려니 60% 할인해준다고 뜬다. 한번 더 나오려니 70% 할인해 준다고 해서 $60로 3년 약정. 혹시나 해서 한번 더 나가려 해봤는데 70%가 마지막이었다. 3년 정도면 어차피 다시 병이 도져 호스팅 업체 바꾸고 싶어 할 듯.

무기한 무료 도메인 한 개를 지원하는 곳인데 난 이미 도메인을 가지고 있어서 더 할인을 해준걸 수도 있다.

워드프레스 설치는 버튼 클릭 한번으로 끝나고 nameserver 설정도 30분 정도만에 모두 완료. 반나절동안 고민한 결과 테마는 [Sparkling](https://colorlib.com/wp/themes/sparkling/)으로 결정. 사진이 많은 가족 블로그에 잘 어울린다.

사진들이 워드프레스 미디어가 아니라 Google Photos 링크들이어서 테마에 사진들이 안나오는 문제가 있었는데 [Nelio External Featured Image](https://wordpress.org/plugins/external-featured-image/) 플러그인으로 해결했다.[^1]

특히 Sparkling 테마는 이 플러그인만 설치하면 별다른 문제 없이 잘 동작했다.

![](https://lh3.googleusercontent.com/-zy1DtPYV-G8/Vr2Iym7a5oI/AAAAAAAGK7E/Yvmzmk8bmpg/s2048/screenshot.png)

다음 목표는 워드프레스에서 글 쓸 때 [Google Picker](https://developers.google.com/picker/)로 사진 선택할 수 있는 플러그인. 플러그인 만든다고 php 뒤져볼 때가 10년도 더 전인데 얼마나 헤맬지 걱정이다.

[^1]: 테마들이 글마다 설정된 featured image를 사용하는데 이 플러그인을 사용하면 외부에 있는 이미지 링크들도 featured image로 설정할 수 있게 해준다. 그리고 글에 나오는 제일 첫 이미지를 featured image로 사용하는게 기본 설정이다.
