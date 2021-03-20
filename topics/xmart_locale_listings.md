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

- [About XMART User's Guide](about_xmart_ug.md)
- [Terms and Definitions](terms_and_definitions.md)


