---
layout: archive
author_profile: true
---

<h1>blog</h1>
<hr>
{% assign posts = site.categories["blog"] %}
{% for post in posts %}
    {% include my-archive-single.html type=page.entries_layout %}
{% endfor %}
<div>
</div>