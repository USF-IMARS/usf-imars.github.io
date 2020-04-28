
  <!-- these are generated from the members collection -->
# Staff
{% for member in site.staff %}
    * [{{member.title}}]({{member.url}}
{% endfor %}
-------------------------------------------------
# Students
{% for member in site.students %}
    [{{member.title}}]({{member.url}})
{% endfor %}
------------------------------------------------
# Alumni
{% for member in site.alumni %}
        [{{member.url}}]({{ member.title }})
{% endfor %}
