# Projects

Can we see the [example post]({{site.baseurl}}{% post_url 2022-02-19-example-post %})?

## All posts
Trying to mix `HTML` with `.md`...?
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>