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


## Find me on bug bounty platforms

<p>
  <a href="https://hackerone.com/imsivamogili" target="_blank" rel="noopener noreferrer" style="text-decoration:none;margin-right:18px;">
    <!-- simple HackerOne icon -->
    <svg width="18" height="18" viewBox="0 0 24 24" style="vertical-align:middle;margin-right:8px">
      <circle cx="12" cy="12" r="10" fill="#222"/>
      <text x="12" y="16" font-size="10" text-anchor="middle" fill="#fff" font-family="Arial">H</text>
    </svg>
    HackerOne
  </a>

  <a href="https://bugcrowd.com/h/imsivamogili" target="_blank" rel="noopener noreferrer" style="text-decoration:none;">
    <!-- simple Bugcrowd icon -->
    <svg width="18" height="18" viewBox="0 0 24 24" style="vertical-align:middle;margin-right:8px">
      <rect x="2" y="2" width="20" height="20" rx="3" fill="#222"/>
      <text x="12" y="16" font-size="10" text-anchor="middle" fill="#fff" font-family="Arial">B</text>
    </svg>
    Bugcrowd
  </a>
</p>
