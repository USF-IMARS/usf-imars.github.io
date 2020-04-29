---
layout: default
---
<!-- layout with cariaco navigation links -->

<div class="post-container">
    <center>
        <h1 class="post-title">{{ page.title }}</h1>
    </center>
    <div class="ui divider"></div>
    <div class="ui centered grid stackable">
    <div class="four column row">
        {% include cariaco_left_nav.md %}
    </div>
    <div class="twelve wide column">
        {{ content }}
    </div>
    <br/>
</div>
