---
layout: contact
title: Contact
---
<script src="https://s.pageclip.co/v1/pageclip.js" charset="utf-8"></script>

<link rel="stylesheet" href="https://s.pageclip.co/v1/pageclip.css" media="screen">

<form class="form-horizontal" action="https://formsubmit.co/diegogradosb@gmail.com" method="POST">
  
  <div class="form-group">
    <label for="name" class="col-sm-2 control-label">Name:</label>
    <div class="col-sm-10">
      <input type="text" class="form-control" id="name" name="name" placeholder="First & Last Name" value="" required />
    </div>
  </div>
  <div class="form-group">
    <label for="email" class="col-sm-2 control-label">Email:</label>
    <div class="col-sm-10">
      <input type="email" class="form-control" id="email" name="email" placeholder="example@domain.com" value="" required />
    </div>
  </div>
    <div class="form-group">
    <label for="department" class="col-sm-2 control-label">Subject:</label>
    <div class="col-sm-10">
      <input type="text" class="form-control" id="subject" name="subject" value="" required />
    </div>
  </div>
  <div class="form-group">
    <label for="message" class="col-sm-2 control-label">Message:</label>
    <div class="col-sm-10">
      <textarea class="form-control" rows="4" name="message" required></textarea>
    </div>
  </div>
  <div class="form-group">
    <div class="col-sm-10 col-sm-offset-2">
      <input id="submit" name="submit" type="submit" value="Send" class="btn btn-primary btn-sm">
    </div>
  </div>
  <input type="hidden" name="_next" value="https://diegogradosb.github.io/thanks.html">
  <input type="hidden" name="_captcha" value="false">
  
</form>


<script type="text/javascript">
let btn = document.getElementById('submit');
btn.onclick = function () {
    window.location.href = "https://diegogradosb.github.io/thanks.html";
    console.log("submit clicked")
}
</script>