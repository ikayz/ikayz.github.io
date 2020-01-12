# My Projects

A list of projects I am working on:

# My Interests

I am interested in contributing to open source and teaching others about coding.

# My Blog

I want to share my coding journey on GitHub with the World.

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

# Get in Touch

<ul>
  <i><a href="https://twitter.com/{{site.twitter_username}}">Twitter</a></li>
  <i><a href="https://github.com/{{site.github_username}}">GitHub</a></li>
</ul>
