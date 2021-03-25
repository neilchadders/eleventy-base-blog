---
layout: layouts/home.njk
title: Contact
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 9
---




<form name="contact" method="POST" data-netlify="true">
  <div class="form-group">
  	 <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
  </div>
  
  </div>
  <div class="form-group">
    <label for="exampleFormControlTextarea1">Message</label>
    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>






 
