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
    <div class="four wide column">
        <!-- 
            using include_relative here for the render markdown side-effect.
            ref: https://stackoverflow.com/a/41966993/1483986
        -->
        {% include_relative ../../_includes/cariaco_left_nav.md %}
    </div>
    <div class="twelve wide column">
        {{ content }}
    </div>
    <br/>
</div>
