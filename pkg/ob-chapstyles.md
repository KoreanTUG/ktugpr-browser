---
layout: package

# Name of package - **.sty
pkg_name: ob-chapstyles

# Short summary of package
pkg_summary: A few chapter styles for oblivoir class

# Version of package
version: 2012-09-02

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
doc: ob-chapstyles.pdf
---

이 문서의 배후에 깔린 생각은 Lars Madsen의 “Various chapter styles for the memoir class”라는 훌륭한 예제를 oblivoir에서 동일하거나 유사하게 활용하고자 하는 것이다.
자신의 chapter style을 디자인한 것이 있으면 저자에게 보내달라. 이 문서를 더욱 풍부하게 하겠다.
이 예제를 더 폭넓게 활용하려면 oblivoir 클래스의 chapter style 관련 사항을 이해하여야 한다. 자세한 것은 memucs-manual에 나와 있으므로 여기서는 다음 사항을 환기해두려 한다.
1. memoir의 `\printchaptername` 매크로는 oblivoir에서 효력이 없다.
2. 한글 장 표제를 위한 두 개의 매크로 `\prechapternum`과 `\postchapternum`에 유의해야 한다. 대부분의 경우 `\prechapternum`은 ‘제’ 이고 `\postchapternum`은 ‘장’ 이다.
3. ToC와 난외표제에 chapternum을 식자하기 위한 매크로 `\hchaptertitlehead`에 유의한다. 대부분의 경우 이것은 “제 `\thechapter` 장” 이다.
이 점에만 유의하면 대부분의 memoir chapter style을 oblivoir에서 거의 똑같이 활용하는
데 아무런 문제가 없다.
그 첫 작업으로, memoir 클래스에 기본 포함되어 있는 chapter style들을 oblivoir화하였다. default, section, article, companion 등의 스타일은 이미 oblivoir에 구현되어 있으므로
그것을 제외하고, memoir patch 4.6 이후 버전에 포함된 스타일들만을 보였다.
이후 시간이 허락하는 대로, Madsen의 다른 예들도 이 문서에 포함할 수 있기를 희망한다.
