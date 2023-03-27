---
layout: archive
author_profile: true
---

<h1>Linux</h1>
<hr>
{% assign posts = site.categories["Linux"] %}
{% for post in posts %}
    {% include my-archive-single.html type=page.entries_layout %}
{% endfor %}
<div>
</div>