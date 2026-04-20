---
title: Welcome to my blog!
---

Hi — thanks for stopping by. This site is a small corner of the internet where I write about things I am learning, projects I am tinkering with, and whatever else feels worth sharing.

Browse recent posts below.

## Recent posts

{% if site.posts and site.posts.size > 0 %}
{% for post in site.posts limit:10 %}
- [{{ post.title }}]({{ post.url | relative_url }}){% if post.date %} - {{ post.date | date: "%b %-d, %Y" }}{% endif %}
{% endfor %}
{% else %}
No posts yet — check back soon.
{% endif %}
