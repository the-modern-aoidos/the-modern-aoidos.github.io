# the-modern-aoidos.github.io

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<!-- <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul> -->