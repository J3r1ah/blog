  # Chef Riah's Dev Blog 

Yo Choom! wassup this is my first dev blog!!
ima post on it somtimes

<img src="/blog/images/rudo.png" alt="rudo" height="300x" width="300px">


# Posts

posts below 

<hr>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
