---
layout: page
title: About
---


## Our Hope

 <blockquote class="italic">He has showed you, O man, what is good. And what does the Lord require of you? To act justly and to love mercy and to walk humbly with your God.
 <p class="txt--right">- Micah 6:8</p>
 </blockquote>
 
 
 To act justly, to love mercy and to walk humbly summarizes our hopes we have for our students and leaders as we all seek a relationship and partnership with God in bringing his Kingdom to Earth.
 
 
### The Orange Strategy 

![Orange Explanation]({{ site.baseurl }}/assets/orange.jpg)
 
 If you've been around Newsong for awhile, you've probably heard us talk about <span class="italics">Orange</span>. The Orange Vision is this:
 
 - <span class="fnt--yellow bold">The church as the light of the world is represented by yellow</span>
 - <span class="fnt--red bold">The family is represented by the color red for its love of its children</span>
   
 <span class="fnt--orange bold">The idea is that we partner with you to raise a future generation of Christ-loving world-changers.</span>
 
---

## Details

We meet on <span class="bold">Sunday evenings from 6-7:30pm in the Fellowship Hall</span>. A typical Sunday evening includes plenty of games, discussions about God, faith and life, and building relationships with one another in small groups.

---

## Contact

<div class="pastor-bio">
  <div class="media center">
  {% for person in site.data.epic.people %}
    {% if person.pastor %}  
        {% comment %}<img class="media-figure image-round" src="{{ site.baseurl }}/assets/images/{{person.photo}}" alt="{{person.name}}" width="150" />{% endcomment %}
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


{% comment %}{% include people-list.html ministry="epic" %}{% endcomment %}

---
