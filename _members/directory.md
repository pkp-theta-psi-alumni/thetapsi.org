---
title: "Member Directory"
layout: single
---

The list of Theta Psi alumni chapter members.

{% for member in site.data.member_bios %}
    {% if member != null %}
     * {{member.name}} - {{member.initiation_number}} - {{member.linkedin_url}}
    {% endif %}
{% endfor %}
