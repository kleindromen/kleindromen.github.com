---
layout: content
name:  "캐릭터 시트"
achieves:
---
# 캐릭터 시트
---
>

이름 | `name`
나이 |
국적 |
코드 |
소속 |
직업 | ****
재능 | ******
제한 |

## 1. 성격


## 2. 특징


## 3. 로그

{% for post in site.corp %}
{% if post.url contains 'name' %}
{% unless post.url contains 'name/index'%}
- [{{post.name}}{{post.num}}]({{ site.baseurl }}{{ post.url }})
{% endunless %}
{% endif %}
{% endfor %}


## 4. 기타
