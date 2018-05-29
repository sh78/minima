---
layout: page
title: Components
permalink: /components/
icon: code
---

You can use all of the [CSS](https://materializecss.com/color.html),
[components](https://materializecss.com/badges.html), and [JavaScript
Plugins](https://materializecss.com/auto-init.html) available from [Materialize
CSS](https://materializecss.com/). It stands to reason that the
[form](https://materializecss.com/autocomplete.html) and
[mobile](https://materializecss.com/mobile.html) stuff will work, too.

*P.S.* [Font Awesome](https://fontawesome.com/icons?d=gallery) is awesome, so we got that too.

<a class="waves-effect waves-light btn-large modal-trigger" href="#modal1"><i class="material-icons right">sentiment_very_satisfied</i>Cheers!</a>

<!-- Modal Structure -->
<div id="modal1" class="modal" style="overflow-y: scroll;">
  <div class="modal-content">
    <h4>Awesome!</h4>
    <img class="responsive" src="https://media.giphy.com/media/itDBteCsTFSVO/giphy.gif">
    <p>I'm glad someone found this useful! Since we're friends now, you
    might want to follow me on <a href="https://github.com/sh78">github</a> or possibly
    even <a href="https://twitter.com/seanmh78">twitter</a>. </p>
    <p>Also, starring the repo will
  is a great way to stay up to date. Just sayin&rsquo;. No pressure or anything.</p>
    <a class="github-button" href="https://github.com/sh78/minimaterialize" data-size="large" data-show-count="true" aria-label="Star sh78/minimaterialize on GitHub">Star</a>
  </div>
  <div class="modal-footer">
    <a href="#!" class="modal-close waves-effect waves-green btn-flat">Done</a>
  </div>
</div>

<script async defer src="https://buttons.github.io/buttons.js"></script>

<script>
document.addEventListener('DOMContentLoaded', function() {
  var elems = document.querySelectorAll('.modal');
  var instances = M.Modal.init(elems, options);
});
</script>
