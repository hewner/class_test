This is source for rendered version of the class materials found
in [the github repository]({{ site.github.repository_url }}).

# List of all rendered files

{% for item in site.mypages %}
* [{{item.sourcepath}}]({{item.url}})
{% endfor %}

