---
layout: default
title: Contact
hero: /images/uploads/badminton_2.jpg
---

<form name="contact" method="POST" netlify>
  <div class="form-input">
    <label for="email">Email</label>
    <input type="email" id="email" name="email" autocomplete="email" onkeyup="this.setAttribute('value', this.value);" required />
  </div>
  <div class="form-input">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" autocomplete="name" onkeyup="this.setAttribute('value', this.value);" required />
  </div>
  <div class="form-input">
    <label for="message">Message</label>
    <textarea type="text" id="message" name="message" onkeyup="this.setAttribute('value', this.value);" required></textarea>
  </div>
  <div data-netlify-recaptcha></div>
  <button type=”submit”>Send</button>
</form>
