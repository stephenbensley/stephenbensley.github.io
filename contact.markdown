---
layout: page
title: Contact
---
Please contact me with any bug reports, feature requests, or other feedback.

<form
  action="https://getform.io/f/6e28767f-1f9e-4467-afcc-80d6a96fc8ef"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="email" />
  </label>

  <label>
    Your message:
    <textarea name="message" rows="10"></textarea>
  </label>

  <button type="submit">Send</button>
</form>

<style>
  /* Some nice boilerplate CSS to tidy up your form */
  form {
    display: grid;
    grid-template-columns: max-content 1fr;
    grid-gap: 1rem;
    text-align: left;
    padding: 2rem 0;
    margin: 0;
  }
  form label {
    display: contents;
  }
  form input[type="email"],
  form textarea,
  form button {
    font-family: inherit;
    font-size: inherit;
    border: 1px solid currentColor;
    background: none;
    padding: 0.4rem 0.5rem;
  }
  form textarea {
    resize: vertical;
  }
  form button {
    justify-self: start;
  }
</style>
