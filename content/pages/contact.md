---
title: "Contact Me"
template: "page"
socialImage: "/media/image-4.jpg"
---

Want to get in touch? Just fill out this form and I'll reply as soon as I can. 

<form name="contact" value="contact" method="post" netlify-honeypot="bot-field" action="/pages/thanks" enctype="application/x-www-form-urlencoded" data-netlify="true">
<input type="hidden" name="bot-field" />
<input type="hidden" name="form-name" value="contact" />
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>

  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

