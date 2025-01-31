---
layout: page
nav: true
nav_order: 7
permalink: /contact/
---
<h1 style="text-align: center;">Contact</h1>
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
    /* Form Container */
    form {
        max-width: 500px;
        margin: 20px auto; /* Center the form */
        padding: 20px;
        background: #f9f9f9; /* Light gray background */
        border-radius: 10px;
        box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
    }

    /* Form Labels */
    label {
        font-weight: bold; /* Make labels bold */
        display: block;
        margin: 10px 0 5px;
        color: #333; /* Darker text for contrast */
    }

    /* Input and Textarea Fields */
    input, textarea {
        width: 100%;
        padding: 12px;
        margin-bottom: 15px;
        border: 1px solid #ccc;
        border-radius: 6px;
        font-size: 14px;
        transition: all 0.3s ease-in-out;
    }

    /* Input Focus Effect */
    input:focus, textarea:focus {
        border-color: #28a745; /* Green outline on focus */
        box-shadow: 0 0 5px rgba(40, 167, 69, 0.5);
        outline: none;
    }

    /* Submit Button */
    button {
        background-color: #28a745; /* Bootstrap Green */
        color: white;
        border: none;
        cursor: pointer;
        padding: 12px;
        font-size: 16px;
        width: 100%;
        border-radius: 6px;
        transition: background 0.3s ease-in-out;
    }

    button:hover {
        background-color: #218838; /* Slightly darker green */
    }

    /* Responsive Fixes for Smaller Screens */
    @media (max-width: 768px) {
        form {
            width: 90%; /* Make form take more width on mobile */
            padding: 15px;
        }
        input, textarea {
            font-size: 14px;
            padding: 10px;
        }
        button {
            font-size: 14px;
            padding: 10px;
        }
    }
</style>