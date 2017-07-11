---
layout: page
title: KTUG PR browser
description: 한국텍학회 사설저장소 브라우저
---

## List of available packages

{% for page in site.pages %}
{% if page.layout == 'package' and page.path != 'pkg/pkg-template.md' %}
- <a href="pkg/{{ page.pkg_name }}">{{ page.pkg_name }}</a> : {{ page.pkg_summary }}
{% endif %}
{% endfor %}
