---
layout: page
title: Resources
---

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

<div class="video sixteen-nine">
<iframe src="https://player.vimeo.com/video/110595675?color=c9ff23&title=0&byline=0&portrait=0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div>

<div class="grd">
  <div class="grd-row">
    <div class="grd-row-col-3-6">
      <a href="https://itunes.apple.com/us/app/parent-cue/id433066482?mt=8"><img alt="Download on the App Store" src="{{ site.baseurl }}/assets/Download_on_the_App_Store_Badge_US-UK_135x40.svg" class="btn-download--apple center" /></a>
    </div>
    <div class="grd-row-col-3-6">
      <a href="https://play.google.com/store/apps/details?id=org.rethinkgroup.parentcuepaid&hl=en&utm_source=global_co&utm_medium=prtnr&utm_content=Mar2515&utm_campaign=PartBadge&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1"><img alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" class="btn-download--google center" /></a>
    </div>
  </div>
</div>

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
