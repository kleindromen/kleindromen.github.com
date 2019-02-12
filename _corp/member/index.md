---
layout: content
name:  "전체 캐릭터 목록"
achieves:
---
# 전체 캐릭터 목록

{% for post in site.corp %}
{% if post.url contains 'member' and post.url contains 'index'%}
{% unless post.url contains 'member/index'%}
- [{{post.name}}{{post.num}}]({{ site.baseurl }}{{ post.url }})
{% endunless %}
{% endif %}
{% endfor %}

---
