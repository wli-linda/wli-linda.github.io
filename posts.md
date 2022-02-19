[About]({{site.baseurl}}/about.html) \| 
[Experiences]({{site.baseurl}}/experiences.html) \| 
[Projects]({{site.baseurl}}/projects.html) \| 
[Posts]({{site.baseurl}}/posts.html)
-----------

# Posts
Here is a list of my posts.
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>