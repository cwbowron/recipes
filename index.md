# Recipes

<div class="tags">

{% assign sorted_tags = (site.tags | sort:0) %}
{% for tag in sorted_tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}  

</div>
