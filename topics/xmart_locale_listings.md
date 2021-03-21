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
<tr class="w3-hover-green"><td>{{ item.Language }}</td><td>{{ item.Locale }}</td><td>{{ item.Attribute }}</td></tr>
{% endfor %}
</table>


## Related Links

- [About XMART User's Guide](about_xmart_ug.md)
- [Terms and Definitions](terms_and_definitions.md)


