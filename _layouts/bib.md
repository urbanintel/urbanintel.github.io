---
---

{% if entry.url %}
<a href="{{ entry.url }}">{{ reference }}</a>
{% else %}
{{ reference }}
{% endif %}

<!-- <pre>{{ entry.bibtex }}</pre> -->