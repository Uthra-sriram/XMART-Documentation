---
layout: template_generalFiles
title: Terms and Definitions
---

# {{page.title}}

There are many terms used when beginning to author XML content in the XMART system. This list is not meant to be exhaustive but rather a helpful start to your knowledge of authoring XML content in the XMART
system.


{% for item in site.data.terms %}

-  {{ item.term }}: {{ item.description }}

{% endfor %}


## Related Links

- [About XMART User's Guide](about_xmart_ug.md)
- [XMART Locale Listings](xmart_locale_listings.md)


