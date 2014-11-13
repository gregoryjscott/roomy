{% if include.resource.links %}
<ul>
  {% include link-li.md label='work' links=include.resource.links.work %}
  {% include link-li.md label='skills' links=include.resource.links.skills %}
  {% include link-li.md label='contact' links=include.resource.links.contact %}
  {% include link-li.md label='projects' links=include.resource.links.projects %}
  {% include link-li.md label='languages' links=include.resource.links.languages %}
  {% include link-li.md label='db' links=include.resource.links.db %}
  {% include link-li.md label='os' links=include.resource.links.os %}
</ul>
{% endif %}
