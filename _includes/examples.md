### Example Layouts

{% for page in site.pages %}
  {% if page.path contains '_pages/example' %}
- [{{ page.title }}]({{ page.url }})
  {% endif %}
{% endfor %}
