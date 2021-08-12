---
layout: page
title: IMaRS Team
---

  <!-- these are generated from the members collection -->
{% capture my_markdown_output %}
    # Staff
    {% for member in site.staff %}
        * [{{member.title}}]({{member.url}})
    {% endfor %}
    -------------------------------------------------
    # Students
    {% for member in site.students %}
        [{{member.title}}]({{member.url}})
    {% endfor %}
    ------------------------------------------------
    # Alumni
    {% for member in site.alumni %}
            [{{member.title}}]({{ member.url }})
    {% endfor %}
{% endcapture %}
{{ my_markdown_output | markdownify }}
