---
title: SIBR APIs
excerpt: The API directory for SIBR
---

{% for api in site.apis %}

## {{ api.name }}

{{ api.content }}

{% if api.base_url %}
**Base URL**: [{{ api.base_url }}]({{ api.base_url }})
{% endif %}

{% if api.docs %}
**Docs Link**: [{{ api.docs }}]({{ api.docs }})
{% endif %}

{% endfor %}
