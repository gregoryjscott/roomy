{% if include.data._links %}
<ul>
  {% include link-li.md label='work' links=include.data._links.work %}
  {% include link-li.md label='skills' links=include.data._links.skills %}
  {% include link-li.md label='contact' links=include.data._links.contact %}
  {% include link-li.md label='projects' links=include.data._links.projects %}
  {% include link-li.md label='languages' links=include.data._links.languages %}
  {% include link-li.md label='db' links=include.data._links.db %}
  {% include link-li.md label='os' links=include.data._links.os %}
</ul>
{% endif %}
