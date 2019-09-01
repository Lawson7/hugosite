---
type: "static"
title: "Contact me"
type: "contact"
layout: "contact"
--- 
Drop me a line...


<form name="contact" method="POST" data-netlify="true" class="submit-form">
  <p>
    <label><input type="text" name="name"class="feedback-input" placeholder="Name" /></label>   
  </p>
  <p>
    <label><input type="email" name="email" class="feedback-input" placeholder="Email"/></label>
  </p>

  <p>
    <label><textarea name="message" class="feedback-input" placeholder="Comment"></textarea></label>
  </p>
  </p>
  <div data-netlify-recaptcha="true"></div>
  <p>
  <p>
    <button type="submit" value="SUBMIT">SUBMIT</button>
  </p>
</form>
