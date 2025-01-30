---
layout: home
---

I'm hosted with GitHub Pages.

## Latest Posts
{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}
