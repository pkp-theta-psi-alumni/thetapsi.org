| Name | Initiation Number | LinkedIn |
| ---- | ----------------- | -------- |
{% for member in site.data.member_bios %}
{% if member.linkedin_url != null %}
| {{ member.name }} | {{ member.initiation_number }} | <i class='fab fa-linkedin'></i> [Connect]({{ member.linkedin_url }}) |
{% else %}
| {{ member.name }} | {{ member.initiation_number }} | |
{% endif %}
{% endfor %}
