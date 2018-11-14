---
layout: default
title: Contact
hero: /images/uploads/badders.jpg
---
 
<form name="contact" method="POST" netlify>
  <p>
    <label>Email: <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <div data-netlify-recaptcha></div>
  <p>
    <button type=”submit”>Send</button>
  </p>
</form>
