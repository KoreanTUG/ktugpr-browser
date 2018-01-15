---
layout: package

# Name of package - **.sty
pkg_name: graphicsonthefly

# Short summary of package
pkg_summary: Import and include graphics from url

# Version of package
version: 2017-11-26

# License of package
license: 

# Maintainer of package (can be listed if many)
maintainer: 
  - novadehi

# Repository of package
repo_url: 

# Thumbnail image of package
# File extension should be included, and image should be placed at /img/pkg.
thumbnail: 

# Filename of documentation at <pkg_name>/doc/latex/<pkg_name>/
doc: graphicsonthefly-doc.pdf
---

웹상의 그림에 대해 url을 주면 다운로드받아서 문서에 넣자 하는 것입니다. url로 주어진 그림을 가져와서 graphicx 패키지의 `\includegraphics` 명령으로 그림을 삽입하는 `\includegraphicsonthefly`와, url로 주어진 animated gif 그림을 가져와서 animate 패키지의 `\animategraphics` 명령으로 그림을 삽입하는 `\animatedgifonthefly` 두 개의 명령으로 이루어져 있습니다.
