---
layout: page
title: Blogi
permalink: /blogs/
---
<ul class="post-list-mini">


    <h4>Blogi</h4>
{% for blog in site.blogs  %}
  <li>
      <a class="post-link" href="{{ blog.url  }}">
          {{ blog.title }}
      </a>
  </li>
{% endfor %}
</ul>