---
layout: page
title: About
permalink: /about/
---

You can reach out to me using the form below:

<style>
form {
  display: flex;
  flex-direction: column;
  width: 300px;
  margin: auto;
}

label {
  margin-bottom: 10px;
}

input, textarea {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

button {
  padding: 10px 20px;
  background-color: #4CAF50;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

button:hover {
  background-color: #45a049;
}
</style>

<form
  action="https://formspree.io/f/meqywlnk"
  method="POST"
>
  <label>
    Your name:
    <input type="name" name="name" required>
  </label>
  <label>
    Your email:
    <input type="email" name="email" required>
  </label>
  <label>
    Your message:
    <textarea name="message" required maxlength="200"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>