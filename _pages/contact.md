---
layout: default
title: Contact
permalink: /contact/
---

<!-- ![alt text](/images/DSC_6872.jpg){:class="img-responsive"} -->
<!-- <img src="/images/DSC_6872.jpg" width="20%"> -->

<div class="home">
  <div class="about">
    <h2 class="tagline">Contact me using one of following methods</h2>

    <div class="contact-contaiver">
      <ul class="contact-list">

        {% if site.email %}
          <li class="email"><a href="mailto:{{site.email}}"><i class="fa fa-envelope-o"></i> {{site.email}}</a></li>
        {% endif %}

        {% if site.phone %}
          <li class="phone"><a href="tel:{{site.phone}}"><i class="fa fa-phone"></i> {{site.phone}}</a></li>
        {% endif %}

        {% if site.website %}
          <li class="website"><a href="http://{{site.website}}" target="_blank"><i class="fa fa-globe"></i> {{site.website}}</a></li>
        {% else %}
        {% endif %}

        {% if site.linkedin %}
          <li class="linkedin"><a href="https://in.linkedin.com/in/{{site.linkedin}}" target="_blank"><i class="fa fa-linkedin"></i> linkedin.com/in/{{site.linkedin}}</a></li>
        {% else %}
        <li class="linkedin"><a href="https://in.linkedin.com/" target="_blank"><i class="fa fa-linkedin" aria-hidden="true"></i> linkedin.com</a></li>
        {% endif %}

        {% if site.github %}
          <li class="github"><a href="http://github.com/{{site.github}}" target="_blank"><i class="fa fa-github"></i> github.com/{{site.github}}</a></li>
        {% endif %}

        {% if site.xing %}
          <li class="xing"><a href="https://www.xing.com/profile/{{site.xing}}" target="_blank"><i class="fa fa-xing"></i> {{site.xing}}</a></li>
        {% endif %}

      </ul>
    </div>
  </div>
</div>

<!-- ## Office

<i class="fas fa-phone"></i>


| Address:      | TUM-EI-ESI |
|| Arcisstr. 21|
|| D-80333 Munich|
||Germany| -->