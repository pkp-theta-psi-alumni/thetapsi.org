---
title: "Member Directory"
layout: single
---

The list of Theta Psi alumni chapter members.

| Name | Initiation Number | LinkedIn |
| ---- | ----------------- | ------- |

{% for member in site.data.member_bios %}
| {{ member.name }} | {{ member.initiation_number }} | <i class='fab fa-linkedin'></i> [Connect]({{ member.linkedin_url }}) |
{% endfor %}
