---
title: CSSE000
permalink: /
---

Welcome to the CSSE000!  All the materials are available from [the
course github repository]({{ site.github.repository_url }}).

# List of all rendered files

If you'd like to view a particular page in the repo full-page, without
all the associated Github history and info, here's a list of the
rendered versions.

{% for item in site.pages %}
* [{{item.path}}]({{item.url}})
{% endfor %}

