{% if include.links %}
  {% for link in include.links %}
    {% if include.disabled %}
      {{ link.title }}{% unless forloop.last %},{% endunless %}
    {% else %}
      <a href="{{ link.url }}">{{ link.title }}</a>{% unless forloop.last %},{% endunless %}
    {% endif %}
  {% endfor %}
{% endif %}
