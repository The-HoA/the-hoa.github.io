---
layout: default # Or a specific event layout
title: "Demo Title"
date: "1999-02-32"
image: /pages/events/demo/cover.webp
event_page: true # Flag to identify this as an event
permalink: /events/demo/ # Ensure a permalink is set
---

{% include event_data.html
    venue       ="India"
    description ="description"
    games       ="games"
%}

<div style="column-width: 350px; column-gap: 10px; column-fill: balance;">
{% include instagram.html url="" %}
{% include instagram.html url="" %}
{% include instagram.html url="" %}
</div>
<script src="//www.instagram.com/embed.js"></script>
