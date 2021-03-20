---
layout: template_generalFiles
title: XMART Locale Listings
---

# {{page.title}}

Following table lists the supported XMART locales:


<table>
<tr>
<th>XMART Language</th><th>XMART Locale</th><th>Locale Attribute</th>
</tr>
{% for item in site.data.locales %}
<tr><td>{{ item.language }}</td><td>{{ item.locale }}</td><td>{{ item.attribute }}</td></tr>
{% endfor %}
</table>


## Related Links

- [Time and distance](time_distance.md)
- [Planets and stars](planet_stars.md)


