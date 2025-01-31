---
layout: page
title: Contact
nav: true
nav_order: 7
permalink: /contact/
---

<form action="https://formspree.io/f/movjwjbe" method="POST">

  <label for="name"><b>Name</b></label>
  <input type="text" id="name" name="name" placeholder="First and Last" required>

  <label for="email"><b>Email address</b></label>
  <input type="email" id="email" name="email" placeholder="example@gmail.com" required>

  <label for="message"><b>Message</b></label>
  <textarea id="message" name="message" rows="5" placeholder="Your message" required></textarea>

  <!-- Submit button -->
  <button type="submit">Send</button>
</form>

<style>
    form {
        max-width: 500px;
        margin-top: 20px;
    }
    label {
        font-weight: bold; /* Make labels bold */
        display: block;
        margin-top: 10px;
    }
    input, textarea {
        width: 100%;
        padding: 10px;
        margin: 5px 0;
        border: 1px solid #ccc;
        border-radius: 5px;
    }
    button {
        background-color: green;
        color: white;
        border: none;
        cursor: pointer;
        padding: 10px 20px;
        font-size: 16px;
        width: 100%;
        border-radius: 5px;
    }
    button:hover {
        background-color: darkgreen;
    }
</style>