---
layout: package

# Name of package - **.sty
pkg_name: ksruby

# Short summary of package
pkg_summary: Using ruby characters with xelatex

# Version of package
version: 0.0.1

# License of package
license:

# Maintainer of package (can be listed if many)
maintainer: 
  - novadehi

# Repository of package
repo_url: 

# Thumbnail image of package
# File extension should be included, and image should be placed at /img/pkg.
thumbnail: ksruby.png

# Filename of documentation at <pkg_name>/doc/latex/<pkg_name>/
# File extension(.pdf) should be included.
doc: ksruby-doc.pdf
---

XeLaTeX에서, 한글 문서에 루비 문자(또는 그 아류)를 쓰려 할 적에 현재까지 CJK의 ruby 패키지에 의존해왔다. 몇 가지 마음에 들지 않는 것이 있어서 새로 만들기로 하고 이를 테스트한다. luatexko에는 이미 `\ruby` 명령이 따로 존재하므로 주로 xetexko와 함께 쓰기 위함이다.