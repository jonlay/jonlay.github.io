---
layout: default
title: Homepage
---

<div class="row">
  <div class="col-sm-4">
    <img style="margin: 22px 25px 0 0; width: 200px; max-width: 100%; border-radius: 5px;" class="right" src="{{ site.baseurl }}/assets/img/avatar.jpg" alt="Profile Picture" title="wow, very face, such photograph, wow">
  </div>
  <div class="col-sm-8">
    <h1>Designer. Developer. Founder. Noodle aficionado. Overzealous emoji user. Appreciator of awful puns.</h1>

    <p class="lead">I started out training to be a lawyer in London but luckily, ended up as a designer in Kuala Lumpur.</p>

    <p class="lead">I spend most of my time helping to build social startups and digital products over at <a href="https://hanno.co">Hanno</a>.</p>
  </div>
</div>

<hr>

<div class="row">
  <div class="col-sm-4">
    <h3>Find me on</h3>
  </div>
  <div class="col-sm-8">
    <h3><a href="https://twitter.com/jon_lay" title="">Twitter</a>, <a href="https://www.linkedin.com/in/jonlay" title="LinkedIn">LinkedIn</a>, <a href="https://github.com/jonlay" title="GitHub">GitHub</a>, <a href="https://medium.com/@jon_lay" title="Medium">Medium</a> and <a href="https://www.goodreads.com/user/show/24302318-jon-lay">Goodreads</a>.</h3>
  </div>
</div>

<hr>

<div class="row">
  <div class="col-lg-4">
    <h3>Recent scribblings</h3>
  </div>
  <div class="col-lg-8">
    <div id="ajax-container"></div>
    <div class="post-index" class="container">
      <ul class="posts post-list list-unstyled" id="container">
      </ul>
    </div>
  </div>
</div>

<script type="text/html" id="exampleTemplate">
  <li class="post-stub" >
    <p class="lead"><a title="<!=title!>" href="<!=link!>"><!=title!></a></p>
  </li>
</script>
