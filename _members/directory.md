---
title: "Member Directory"
layout: single
---

The list of Theta Psi alumni chapter members.

{% for member in site.data.member_bios %}
* {{ member.name }} - {{ member.initiation_number }} - { {member.linkedin_url }}
{% endfor %}
