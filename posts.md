# Posts

<Header>
  {% for post in site.posts %}
      <h1 href="{{ post.url }}">{{ post.title }}</h1>
  {% endfor %}
</Header>
