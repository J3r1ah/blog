yo yo This is my first Dev Blog 

wassupppp!!!

<img src"/blog/images/rudo.png" alt"rudo">



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>