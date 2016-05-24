---
layout: page
title: About
---


## Our Mission

 <blockquote class="italic">Kingdom City provides an authentic community for children to follow in the footsteps of Jesus for the good of the world.</blockquote>

---

## Our Strategy

<div class="video sixteen-nine">
<iframe src="https://player.vimeo.com/video/46033480?color=c9ff23&title=0&byline=0&portrait=0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div>

---

## Contact

<div class="pastor-bio">
  <div class="media center">
  {% for person in site.data.kc.people %}
    {% if person.pastor %}  
        <img class="media-figure image-round" src="{{ site.baseurl }}/assets/images/{{person.photo}}" alt="{{person.name}}" width="150" />
        <div class="media-body">
          <h4>
            <a href="mailto:{{person.email}}">{{ person.name }}</a>
          </h4>
          <p>{{person.role}}</p>
        </div> 
    {% endif %}
  {% endfor %}
  </div>
</div>


{% comment %}{% include people-list.html ministry="kc" %}{% endcomment %}

---
