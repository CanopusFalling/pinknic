---
layout: simple
title: Contact
---

> **Important Notice:** This contact form goes to myself, [Canopy Falls](https://canopyfalls.com). I am not associated with the organisers of Pinknic. I am just holding onto the domain name as it was left to be deregistered.

<form
  action="https://formspree.io/f/mvgajdlz"
  method="POST"
  style="display: flex; flex-direction: column; gap: 12px; margin-left: auto; margin-right: auto; width: 100%;"
>
  <div style="display: flex; flex-direction: column; gap: 8px;">
    <label for="email" style="font-size: 18px; font-weight: 500;">Your Email:</label>
    <input
      type="email"
      name="email"
      id="email"
      required
      style="padding: 12px; border: 1px solid rgba(0, 0, 0, 1); border-radius: 6px; outline: none; background-color: rgba(0, 0, 0, 0.2);"
      placeholder="your.email@example.com"
    />
  </div>

  <div style="display: flex; flex-direction: column; gap: 8px;">
    <label for="message" style="font-size: 18px; font-weight: 500;">Your Message:</label>
    <textarea
      name="message"
      id="message"
      rows="6"
      required
      style="padding: 12px; border: 1px solid rgba(0, 0, 0, 1); border-radius: 6px; outline: none; background-color: rgba(0, 0, 0, 0.2);"
      placeholder="Tell us what's on your mind..."
    ></textarea>
  </div>

  <button
    type="submit"
    style="padding: 12px 24px; background-color:rgba(229, 70, 221, 0.7); color: #ffffff; font-weight: 600; border-radius: 6px; border: none; cursor: pointer; display: block; width: 100%;">
    Send Message
  </button>
</form>