---
layout: layouts/post.njk
title: Contact Me
templateClass: col-md-10
eleventyNavigation: 
  key: Contact Me
  order: 5 
---


<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>First Name* <input type="text" name="name" required /></label>   
  </p>
  <p>
    <label>Surname* <input type="text" name="name" required /></label>   
  </p>
  <p>
    <label>Email* <input type="email" name="email" required /></label>
  </p>
  <p>
    <label>Cooking Experience: <select name="role[]" multiple>
      <option value="leader">Zero</option>
      <option value="follower">Amateur</option>
      <option value="follower">Novice</option>
      <option value="follower">Pro</option>
    </select></label>
  </p>
  <p>
    <label>Message* <textarea name="message" required ></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
  Agree to terms and conditions<input type="checkbox"/>  
  Subscribe to our newsletter<input type="checkbox"/> 
</form>

