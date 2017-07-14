---
layout: page
title: KTUG PR browser
description: 한국텍학회 사설저장소 브라우저
---

## <a id="packages"></a>List of available packages

{% for page in site.pages %}
{% if page.layout == 'package' %}
- <a href="{{ page.path | replace: '.md', '' }}">{{ page.pkg_name }}</a> : {{ page.pkg_summary }}
{% endif %}
{% endfor %}

## <a id="authors"></a>List of authors

{% assign items = site.pages | sort: 'authorname' %}
{% for page in items %}
{% if page.layout == 'author' %}
- <a href="{{ page.path | replace: '.md', '' }}">{{ page.authorname }}</a>
{% endif %}
{% endfor %}
