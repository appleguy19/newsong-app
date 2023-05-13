---
layout: page
title: Resources
---
<!-- Not currently in use -->

### What we're Learning

Our curriculum changes each month. Check out what we're learning in <span id="month" class="bold"></span>.


<div class="media-list">
  <a href="https://www.dropbox.com/s/seo76jf28wc8xom/KC-ParentCue-PreK.pdf?raw=1" target="_blank" class="media resource">
    <div class="media-figure">
      <svg class="icon--white" height="100" width="100">
        <use xlink:href="{{ site.baseurl }}/assets/icons.svg#doc" />
      </svg>
    </div>
    <div class="media-body">
       <h6 class="m0 p0">Preschool: Infant, Toddler, Pre-K</h6>
     </div>
  </a>
  <a href="https://www.dropbox.com/s/wojir5f2kqnio4y/KC-ParentCue-K5.pdf?raw=1" target="_blank" class="media resource">
    <div class="media-figure">
      <svg class="icon--white" height="100" width="100">
        <use xlink:href="{{ site.baseurl }}/assets/icons.svg#doc" />
      </svg>
    </div>
    <div class="media-body">
       <h6 class="m0 p0">Elementary: Kindergarten - 5<sup>th</sup> Grade</h6>
     </div>
  </a>
</div>

---

### Parent Cue App

The Parent Cue App provides simple <em>cues</em> throughout the week that remind you to pause and make the most of everyday moments. Check out the video below to learn more.

<a href="https://parentcue.onelink.me/Q1MD/cec99eb6" class="btn--green btn--m w100">Download the Parent Cue app now!</a>

---

### Resource Links

{% include resource-list.html ministry="kc" %}

---


<script>
var monthNames = ["January", "February", "March", "April", "May", "June",
  "July", "August", "September", "October", "November", "December"
];

var d = new Date();
    d.setDate(d.getDate() + 3);
document.getElementById("month").innerHTML = monthNames[d.getMonth()];
</script>
