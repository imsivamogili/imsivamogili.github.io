---
layout: home
title: Home
---

# Hi, I am **sivamogili** 👋

I like doing various things related to hacking.  
I do full-time bug bounty hunting, research web security, and automate vulnerabilities.

---

## Latest posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <div class="meta">{{ post.author | default: site.title }} — {{ post.date | date: "%b %d, %Y" }}</div>
      <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
    </li>
  {% endfor %}
</ul>
