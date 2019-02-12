---
layout: content
name:  "전체 진영 목록"
achieves:
---
# 전체 진영 목록

{% for post in site.corp %}
{% if post.url contains 'influence' and post.url contains 'index'%}
{% unless post.url contains 'influence/index'%}
- [{{post.name}}{{post.num}}]({{ site.baseurl }}{{ post.url }})
{% endunless %}
{% endif %}
{% endfor %}

---
