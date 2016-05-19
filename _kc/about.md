---
layout: post
title: About
---


### Our Mission

 <blockquote class="italic">Kingdom City provides an authentic community for children to follow in the footsteps of Jesus for the good of the world.</blockquote>

---

### Our Strategy

<div class="video sixteen-nine">
<iframe src="https://player.vimeo.com/video/46033480?color=c9ff23&title=0&byline=0&portrait=0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div>

---

### Our Crew

<div class="pastor-bio">
  <div class="media center">
  {% for person in site.data.kc.people %}
    {% if person.pastor %}  
        <img class="media-figure image-round" src="{{person.photo}}" alt="{{person.name}}" />
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

{% comment %}
<div class="people-list">
  {% for person in site.data.kc.people %}
    {% unless person.pastor %}
    <div class="media person">
      <img class="media-figure image-round" src="{{person.photo}}" alt="{{person.name}}" width="100" />
         <div class="media-body">
           <h6 class="m0 p0">{{ person.name }}</h6>
           <p class="m0 p0">{{person.role}}</p>
         </div>
    </div>
    {% endunless %}
  {% endfor %}
</div>
{% endcomment %}