{% if include.links %}
  <li>
    {{ include.label }}{% if include.show_count %} ({{ include.links.size }}){% endif %}:
    {% include links-commas.md links=include.links disabled=include.disabled %}
  </li>
{% endif %}
