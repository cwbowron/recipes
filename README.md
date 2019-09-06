# Recipes

## Rice Cooker
* [Jambalaya](Jambalaya.md)

## Slow Cooker
* [Cajun Pork Loin](Cajun_Pork_Loin.md)
* [Pulled Park](Pulled_Pork.md)
* [Shrimp Jambalaya](Shrimp_Jambalaya.md)
* [Spicy Beef Roast](Spicy_Beef_Roast.md)
* [Buffalo Chicken Dip](Buffalo_Chicken_Dip.md)

## Grill
* [Bratwurst](Grilled_Bratwurst.md)
* [Italian Sausage](Grilled_Italian_Sausage.md)

## Etc.

* [Zesty Chicken with Rice](Zesty_Chicken_with_Rice.md)

## Sweets

* [Cinnamon Rolls](Cinnamon_Rolls.md)
* [Fudge Krispies](Fudge_Krispies.md)


<div class="tags">

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}  

</div>
