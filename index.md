---
layout: splash
title: "Welcome to My Portfolio"
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/coffee.jpg
 
---
    
Welcome! This is my porfolio of my academic projects at the University of West Georgia.

<p style="font-size:0.9rem">DEBUG: feature_row count = {{ site.data.feature_row.feature_row | size }}</p>
<p style="font-size:0.9rem">DEBUG: remote_theme = {{ site.remote_theme }}</p>
{% include feature_row id="feature_row" %}
