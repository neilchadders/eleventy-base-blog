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
  <div class="form-group">
    <label for="exampleInputPassword1">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
  </div>
  <div class="form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Check me out</label>
  </div>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>






 
