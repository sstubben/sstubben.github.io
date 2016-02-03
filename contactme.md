---
title: Contact me
permalink: contact/
profile: false
---

<h1 id="contactHeader">Hit me up</h1>

<form accept-charset="UTF-8" id="contactform" action="http://pooleapp.com/stash/643aada2-81e9-422f-8de1-1568e7aed6d5/" method="POST">
  <div class="form-group">
    <label for="email">What's your email?</label>
    <input type="email" id="email" name="email" required>
    <label for="description">What can I help you with?</label>
    <textarea rows="4" cols="50" name="description" form="contactform"></textarea>
    <input type="hidden" name="redirect_to" value="/thanks" />
    <button class="cta" type="submit">Submit</button>
  </div>
</form>
