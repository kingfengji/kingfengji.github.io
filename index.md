---
layout: default
---

# Fine, 

let's use github pages

# Blogs

{% for post in site.posts %}
* *{{ post.date | date_to_string }}* » [{{ post.title }}]({{ post.url }})
{% endfor %}