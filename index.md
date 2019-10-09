# eecsg
Here, I post things that I'm working or thinking about. You can contact me over Keybase (eecsg on Keybase).

## Posts
  {% for post in site.posts %}
  <article>
    <p>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
      :: <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
    </p>
  </article>
  {% endfor %}
