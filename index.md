---
layout: default
title: Homepage
---

<div class="row">
  <div class="col-sm-4">
    <img style="margin: 22px 25px 0 0; width: 200px; max-width: 100%; border-radius: 5px;" class="right" src="{{ site.baseurl }}/assets/img/avatar.jpg" alt="Profile Picture" title="wow, very face, such photograph, wow">
  </div>
  <div class="col-sm-8">
    <h1>I'm a designer, developer, founder, culture hacker &amp; noodle aficionado.</h1>
    <p class="lead">I started out as a lawyer and then quit to start a design firm called <a href="http://hanno.co">Hanno</a>, where we help startups to do great UX design.</p>
    <p class="lead">On the way, I moved from London to Asia and I now spend my time trying to figure out how to turn that company into a <a href="https://en.wikipedia.org/wiki/Social_business" title="social business">social business</a> and have a positive impact on the world. I'm also a wildly overzealous emoji user.</p>
  </div>
</div>

<hr>

<div class="row">
  <div class="col-sm-4">
    <h3>Find me on</h3>
  </div>
  <div class="col-sm-8">
    <h3><a href="https://twitter.com/jon_lay" title="">Twitter</a>, <a href="https://www.linkedin.com/in/jonlay" title="LinkedIn">LinkedIn</a>, <a href="https://github.com/jonlay" title="GitHub">GitHub</a> and <a href="https://medium.com/@jon_lay" title="Medium">Medium</a>.</h3>
  </div>
</div>

<hr>

<div class="row">
  <div class="col-lg-4">
    <h3>Recent writing</h3>
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