---
permalink: /posts/
---

[About]({{site.baseurl}}/about) \| 
[Experiences]({{site.baseurl}}/experiences) \| 
[Projects]({{site.baseurl}}/projects) \| 
[Posts]({{site.baseurl}}/posts)

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