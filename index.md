---
layout: page
title: Welcome
tagline: Wenzhao Xu
---
{% include JB/setup %}

Hi, I am Wenzhao Xu, welcome to my github blog. I like the word "storm" so this github site is called "Storm's pages". Currently I am a Ph.D. candidate and research assistant in Dept. of Civil and Environmental Engineering at University of Illinois at Urbana-Champaign. My research areas are environmental system analysis. For more information about my ***research and education background***, please check [my intro](me.html) and [my repos](https://github.com/stormxuwz?tab=repositories)


    
## Recent Posts



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

