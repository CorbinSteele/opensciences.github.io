---
title: other
layout: repo
---

{% for post in site.categories.other do %}
    <div class="box">
        <h2>{{post.title}}</h2>
        <div class="block">
            {{post.content}}
        </div>
    </div>
{% endfor %}