---
layout: page
title: Philip Bredehoeft
subtitle: 3G Generalist, cinematic artist, storyteller.
bigimg: /img/Back-Ground.gif
---

I am a result driven professional with over 18 years of experience in the Movie, Television and Game industries. Extensive experience as a 3D animator with a strong knowledge and commitment to 2D animation and its practical theories and application. Proficiency in implementing and overseeing the creative development and integration while maintaining clarity under schedule. I look forward to the opportunity to join your team.

<ul class="list-inline text-center footer-links">
    {%- for link in site.social-network-links -%}
    {%- assign curkey = link[0] -%}
    {%- assign element = site.data.SocialNetworks[curkey] -%}
    <li>
    {%- if curkey == 'rss' -%}
        <a href="{{ '/feed.xml' | prepend: site.baseurl }}" title="{{ element.name }}">
    {%- elsif curkey == 'yelp' -%}
        <a href="https://{{ site.social-network-links[curkey] }}.yelp.com" title="{{ element.name }}">
    {%- else -%}
        <a href="{{element.baseURL}}{{ site.social-network-links[curkey] }}" title="{{ element.name }}">
    {%- endif -%}
        <span class="fa-stack fa-lg" aria-hidden="true">
            <i class="fa fa-circle fa-stack-2x"></i>
            <i class="fa {{ element.icon }} fa-stack-1x fa-inverse"></i>
        </span>
        <span class="sr-only">{{ element.name }}</span>
        {{ element.name }}
        </a>
    </li>
    {%- endfor -%}
</ul>