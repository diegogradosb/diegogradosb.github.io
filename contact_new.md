---
layout: page
title: Contact
---
<form action="https://formspree.io/diegogradosb@gmail.com" method="POST" class="form" id="contact-form">
  <div class="form-group">
    <label for="name" class="col-sm-2 control-label">Name:</label>
    <div class="col-sm-10">
      <input type="text" name="name" class="form-control input-lg" placeholder="First & Last Name" title="Name">
    </div>
  </div>
  <div class="form-group">
    <label for="email" class="col-sm-2 control-label">Email:</label>
    <div class="col-sm-10">
      <input type="email" name="_replyto" class="form-control input-lg" placeholder="example@domain.com" title="Email">
    </div>
  </div>
    <div class="form-group">
    <label for="department" class="col-sm-2 control-label">Subject:</label>
    <div class="col-sm-10">
      <input type="text" name="subject" class="form-control input-lg" title="Name">
    </div>
  </div>

	<input type="hidden" name="_subject" value="New submission from diegogradosb.github.io">

  <div class="form-group">
    <label for="message" class="col-sm-2 control-label">Message:</label>
    <div class="col-sm-10">
 	<textarea type="text" name="message" class="form-control input-lg" title="Message" required="required" rows="4"></textarea>
    </div>
  </div>

 <input type="text" name="_gotcha" style="display:none">


<input type="hidden" name="_next" value="https://diegogradosb.github.io/thanks/" />

  <div class="form-group">
    <div class="col-sm-10 col-sm-offset-2">
 	<button type="submit" class="btn btn-lg btn-primary">Send</button>
    </div>
  </div>
</form>
