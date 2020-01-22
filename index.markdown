---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<h3>Welcome to my Blog</h3>

<div>
  {% for post in site.posts %}
    <ul>
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    </ul>
  {% endfor %}
</div>