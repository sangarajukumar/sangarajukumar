---
layout: page
title: Contact
nav: true
nav_order: 7
permalink: /contact/
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
    <style>
        /* Form Styles */
        form {
            max-width: 500px;
            width: 100%;
            margin: 20px auto;
            padding: 0 10px;
            box-sizing: border-box;
        }
        label {
            font-weight: bold;
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

        /* Mobile Styles */
        @media (max-width: 768px) {
            form {
                margin-top: 10px;
            }
        }
    </style>
</head>
<body>
    <form action="https://formspree.io/f/movjwjbe" method="POST">
        <label for="name"><b>Name</b></label>
        <input type="text" id="name" name="name" placeholder="First and Last" required>

        <label for="email"><b>Email address</b></label>
        <input type="email" id="email" name="email" placeholder="example@gmail.com" required>

        <label for="message"><b>Message</b></label>
        <textarea id="message" name="message" rows="5" placeholder="Your message" required></textarea>

        <button type="submit">Send</button>
    </form>
</body>
</html>