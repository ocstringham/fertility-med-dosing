---
title: "Contact"
date: 2023-08-06
layout: "default-text"
---



<!-- modify this form HTML and place wherever you want your form -->
<div class="container">
  <div class="row">
    <div class="col-xs-12 col-sm-8 col-md-6 col-sm-push-2 col-md-push-3 form__container">
      <!-- <h2>Let's work together</h2> -->
      <h5>If you have any feedback or identiy any errors please contact me using the below form.</h5>
      <form action="https://formspree.io/f/xaygenoo" role="form" method="POST" autocomplete="on">
        <div class="form-group">
          <label for="name">Your Name</label>
          <input type="text" name="name" class="form-control form-input" placeholder="Full name" required>
        </div>
        <div class="form-group">
          <label for="_replyto">Your Email</label>
          <input type="email" name="_replyto" class="form-control form-input" placeholder="Email" required>
        </div>
        <div class="form-group">
          <label for="message">Tell me about your project</label>
          <textarea id="message" name="message" class="form-control" rows="4" width="100%" placeholder="Message" required></textarea>
        </div>
        <div>
          <input type="submit" class="btn btn-primary" value="Send">
          <input type="hidden" name="_subject" value="Contact Us Form Submission: FMD" />
        </div>
      </form>
      <div class="col-sm-12 gutter"></div>
    </div>
  </div>
</div>
</div>