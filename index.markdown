---
layout: default
---

This project documents experiments conducted using FreeBSD. It introduces commonly used commands and configuration examples.

{% for category in  site.categories %}
## {{ forloop.index }} {{ category[0] }}
{% for post in site.posts reversed %}{% if post.category == category[0] %}1. [{{ index }} {{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endif %}{% endfor %}{% endfor %}

## Appendix

- [Commands](https://yumayx.github.io/docs/)
- [Project Repository - YS14](https://github.com/YumaYX/YS14/)
