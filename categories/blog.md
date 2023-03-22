---
layout: archive
author_profile: true
---

<h1>Blog</h1>
<hr>
{% assign posts = site.categories["Blog"] %}
{% for post in posts %}
    {% include my-archive-single.html type=page.entries_layout %}
{% endfor %}
<div>
</div>