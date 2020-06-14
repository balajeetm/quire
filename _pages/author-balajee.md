---
title: "Balajee"
layout: default
permalink: "/author-balajee"
---
<section class="recent-posts">

    <div class="section-title pt-2">

        <h2><span>Balajee™ Stories</span></h2>

    </div>

    <div class="row listrecent">

        {% assign posts = site.posts | where:"author","bala" %}
        {% for post in posts %}
        {% include funstorybox.html %}
        {% endfor %}

    </div>

</section>