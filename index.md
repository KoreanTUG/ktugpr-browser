---
layout: page
title: KTUG PR browser
description: 한국텍학회 사설저장소 브라우저
---

## <a id="packages">List of available packages</a>

{% for page in site.pages %}
{% if page.layout == 'package' %}
- <a href="{{ page.path | replace: '.md', '' }}">{{ page.pkg_name }}</a> : {{ page.pkg_summary }}
{% endif %}
{% endfor %}

## <a id="authors">List of authors</a>

{% for page in site.pages %}
{% if page.layout == 'author' %}
- <a href="{{ page.path | replace: '.md', '' }}">{{ page.authorname }}</a>
{% endif %}
{% endfor %}
