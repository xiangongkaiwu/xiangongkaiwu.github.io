---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
# Tset

{% for page in site.pages %}
{{ page.title }}
{% endfor %}

## Party Time

{% for chapter in site.chapters %}
{{ chapter.title }}
{% endfor %}