---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
# Mysteries of Immortal Puppet Master

<h2>
    Latest Chapter: <a href="{{ site.chapters.last.url | relative_url }}">{{ site.chapters.last.title }}</a>
</h2>

{% for chapter in site.chapters %}
[{{ chapter.title }}]({{ chapter.url | relative_url }})
{% endfor %}