---
layout: package

# Name of package - **.sty
pkg_name: kotex-sections

# Short summary of package
pkg_summary: 옛날 HLaTeX 절표제

# Version of package
version: 2014-06-09

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
doc: kotex-sections-doc.pdf
---

ko.TEX-utf와 LuaTEX-ko, XƎTEX-ko의 다른 점 중 하나가 절표제입니다. ko.TEX-utf에서 `[hangul]` 옵션을 주면 \section에 대하여 “제 1 절”로 식자됩니다. LuaTEX-ko와 XƎTEX-ko는 그냥 “1”이지요.
저 자신은 절에 대하여 굳이 “제”와 “절”을 붙일 필요가 없다고 생각합니다만 이걸 원하는 경우도 없지 않을 터라, HLATEX 이래 유구한 역사와 전통을 지닌 이 기능을 추가해봤습니다.
