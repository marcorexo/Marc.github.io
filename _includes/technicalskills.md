{% for skill in site.data.skills.technicalskills -%}
| {{ skill.title }} | {{ skill.level }} |
{% endfor %}
