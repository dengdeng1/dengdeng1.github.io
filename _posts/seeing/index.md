---
layout: default
---

 <h1 class="page-heading">Posts</h1>

  <br>
<ul>
  {% for post in site.categories.seeing %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
  <p class="rss-subscribe">简书：<a href="http://www.jianshu.com/users/a1885eca3c20/latest_articles"> 慢而不息</a></p>
