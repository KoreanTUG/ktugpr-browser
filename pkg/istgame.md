---
layout: package

# Name of package - **.sty
pkg_name: istgame

# Short summary of package
pkg_summary: Drawing Game Trees with TikZ

# Version of package
version: 0.9

# License of package
license: 

# Maintainer of package (can be listed if many)
maintainer: 
  - ischo

# Repository of package
repo_url: 

# Thumbnail image of package
# File extension should be included, and image should be placed at /img/pkg.
thumbnail: istgame.png

# Filename of documentation at <pkg_name>/doc/latex/<pkg_name>/
# File extension(.pdf) should be included.
doc: istgame-doc.pdf
---

This package provides macros based on TikZ to draw a game tree. The main idea underlying the core macros here is the completion of a whole tree using a sequence of simple 'parent-child' tree structures, with no longer nested relations involved like down to grandchildren or to great-grandchildren.
