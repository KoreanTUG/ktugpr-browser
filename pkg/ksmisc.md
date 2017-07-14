---
layout: package

# Name of package - **.sty
pkg_name: ksmisc

# Short summary of package
pkg_summary: ksjosaref, kslinematters, ksmisc, kstextks, preparefont

# Version of package
version: 2015-07-26

# License of package
license: 

# Maintainer of package (can be listed if many)
maintainer: 
  - novadehi
  - nanim

# Repository of package
repo_url: 

# Thumbnail image of package
# File extension should be included, and image should be placed at /img/pkg.
thumbnail: 

# Filename of documentation at <pkg_name>/doc/latex/<pkg_name>/
doc: ksmiscdoc.pdf
---

## ksjosaref
- [doc](https://github.com/KoreanTUG/KTUGPrivateRepo/raw/master/archive/ksmisc.doc/doc/latex/ksmisc/ksjosaref-doc.pdf)
- v0.2(2015-08-08, nanim)
ko.TEX을 사용하지 아니하는 상황에서 간이 자동조사가 동작하는 `\ref`-류 명령을 정의한다.


## kslinematters
space, carriage return, tab 문자의 catcode를 조작하여 “보이는 대로” 출력하도록 하는 명령과 환경을 제공한다.

## kstextks
- [doc](https://github.com/KoreanTUG/KTUGPrivateRepo/raw/master/archive/ksmisc.doc/doc/latex/ksmisc/kstextks-doc.pdf)
- (2015-08-05, nanim)
[KS X 1001:2004](https://ko.wikipedia.org/wiki/KS_X_1001)에서 정하는 기호문자와 특수문자의 매크로를 제공하고 이 기호문자를 식자할 폰트를 지정할 수 있게 한다.

## preparefont
```tex
\preparefontfile{Font_File_Name}{url}[local_saved_file_name]
```

## ksmisc
```tex
\ks_pop_left:NN <tlvar1> <tlvar2>
\ks_pop_right:NN <tlvar1> <tlvar2>
\ks_clist_set_from_tl:NN <clistvar> <tlvar>
\ks_seq_set_from_tl:NN <seqvar> <tlvar>
```