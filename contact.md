---
layout: default
title: Contact Us
permalink: /contact/
---

<h2 style="text-align: center;">Contact Us</h2>

<form 
  action="https://formspree.io/f/xeoeqlwk" 
  method="POST" 
  class="contact-form"
>
    <label for="name">Your Name</label>
    <input type="text" id="name" name="name" placeholder="Enter your name" required>

    <label for="email">Your Email</label>
    <input type="email" id="email" name="email" placeholder="Enter your email" required>

    <label for="message">Your Message</label>
    <textarea id="message" name="message" placeholder="Write your message here" rows="5" required></textarea>

    <button type="submit" class="button-primary">Send Message</button>
</form>
