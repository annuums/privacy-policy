---
title: 개인정보처리방침 목록
---

# 개인정보처리방침

{% assign policies = site.policies | sort: "title" %}
{% if policies.size > 0 %}
<ul class="policy-list">
{% for p in policies %}
  <li><a href="{{ p.url | relative_url }}">{{ p.title }}</a>{% if p.effective_date %} <span class="meta">시행일 {{ p.effective_date }}</span>{% endif %}</li>
{% endfor %}
</ul>
{% else %}
<p>등록된 개인정보처리방침이 없습니다.</p>
{% endif %}
