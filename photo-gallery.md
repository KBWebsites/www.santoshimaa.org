---
title: Photo Gallery
layout: default
css: //cdnjs.cloudflare.com/ajax/libs/jquery-nivoslider/3.2/nivo-slider.min.css
css2: /-/css/themes/light/light.css
---
<div class="slider-wrapper theme-light">
    <div id="slider" class="nivoSlider">
        <img src="/files/photo-gallery/(1).gif" alt="" />
        {% for i in (2..57) %}<img src="/files/photo-gallery/({{i}}).jpg" alt="" />{% endfor %}
    </div>
</div>

{% include slider_js.htm %}