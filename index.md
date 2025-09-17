# Chef Riah's Dev Blog 



<img src="/blog/images/rudo.png" alt="rudo" height="300x" width="300px">


# Posts
<hr>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
