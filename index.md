---
layout: default
---

# Open source at IPGP

{% for repository in site.github.public_repositories %}
  * {{ repository.name }}
{% endfor %}
