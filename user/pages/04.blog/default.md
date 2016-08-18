---
content:
    items: @self.children
    order:
        by: date
        dir: asc
    limit: 10
    pagination: true
process:
  twig: true
---

# Blog listing

{% for i in page.collection %}
  <h3><a href="/blog/{{ i.slug }}">{{ i.title }}</a></h3>
  {{ i.summary }}
{% endfor %}
