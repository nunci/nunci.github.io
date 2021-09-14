---
layout: blog
title: Blog
include_in_header: true
---

{%- assign date_format = "%b %-d, %Y" -%}
{% for post in site.posts %}

### <a href="{{ post.url | relative_url }}" target="_self">{{ post.title }}</a>
{{ post.description }}
<br><br>
{% endfor %}
