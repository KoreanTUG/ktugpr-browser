---
layout: package

# Name of package - **.sty
pkg_name: kswrapfig

# Short summary of package
pkg_summary: 그림과 텍스트 사이의 간격과 위치를 조절하는 옵션을 제공

# Version of package
version: 0.004(2014-12-14)

# License of package
license: 

# Maintainer of package (can be listed if many)
maintainer: 
  - karnes

# Repository of package
repo_url: 

# Thumbnail image of package
# File extension should be included, and image should be placed at /img/pkg.
thumbnail: 

# Filename of documentation at <pkg_name>/doc/latex/<pkg_name>/
doc: kswrapfigdoc.pdf
---

kswrapfig 패키지는 원래 kstextflow라는 이름이었다. 이름을 바꾸고 기능을 추가한 후 2012년 한국텍학회 학술대회1에서 발표하였다. 이 패키지는 picins2, picinpar 패키지를 이용하여 문단 가운데 그림을 두고 그 주위로 텍스트가 흐르게 한다. 그림과 텍스트 사이의 간격과 위치를 조절하는 옵션을 제공하는 것이 이 패키지의 목적이다. `\kswrapfig` 명령과 `\kswrapfigline` 두 개의 명령을 사용할 수 있다.
이전 버전에서 이 패키지는 memoir/oblivoir에서만 동작하였으나 0.002.3버전 부터 일반 클래스에서도 동작하도록 수정하였다. 따라서 article 등의 클래스에서도 쓸 수 있다.
