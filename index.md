---
layout: default
---
<h1>{{ site.title }}</h1>
<p>{{ site.description }}</p>

<ul>
{% for file in site.markdown_files %}
<!-- <li> -->
    {{ forloop.index }}. <a href="{{ file.url | relative_url }}">{{ file.title | file.path }}</a>
<!-- </li> -->
{% endfor %}
</ul>
