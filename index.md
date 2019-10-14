Here, I post things that I'm working or thinking about. You can contact me over Keybase (**eecsg** on Keybase).

<div class="card">
<h2 class="card-header">Posts</h2>
<div class="card-body">
  {% for post in site.posts %}
  <article>
    <ul>
    <li><a href="{{ post.url }}">{{ post.title }}</a> :: <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time></li>
    </ul>
  </article>
  {% endfor %}
</div>
</div>