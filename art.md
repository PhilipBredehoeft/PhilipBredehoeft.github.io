---
layout: page
title: Art
show-avatar: false
images:
    - image_path: /img/gallery/Arbie_Globe_1025_PRINT.jpg
      title:
    - image_path: /img/gallery/Arby_Groceries_0507a_print.jpg
      title:
    - image_path: /img/gallery/Arby_Snowboard_0124_PRINT_03_WHITE.jpg
      title:
    - image_path: /img/gallery/01a.jpg
      title:
    - image_path: /img/gallery/02a.jpg
      title:
    - image_path: /img/gallery/model_snowmobile.jpg
      title:
    - image_path: /img/gallery/nara-hero-01(1).jpg
      title:
    - image_path: /img/gallery/nara-hero-01wire.jpg
      title:
    - image_path: /img/gallery/nara-hero-standing-02.jpg
      title:
    - image_path: /img/gallery/nara-hero-standing-03.jpg
      title:
    - image_path: /img/gallery/gladiator_april 2008_textured_2.jpg
      title:
    - image_path: /img/gallery/gladiator_may2008_rotation01.jpg
      title:
    - image_path: /img/gallery/gladiator_may2008_rotation02.jpg
      title:
    - image_path: /img/gallery/3dgirl02.jpg
      title:
---

<ul class="photo-gallery" style="text-align: center; margin-right: 10%; margin-left: 10%">
        {% for image in page.images %}
            <li style="display: inline-block; list-style: none"><img src="{{ image.image_path }}" /></li>
        {% endfor %}
</ul>