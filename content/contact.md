---
type: custom
title: Contact
showSummary: false
showReadingTime: false
showDate: false
showWordCount: false
---

<form
  action="https://formspree.io/f/mvgajdlz"
  method="POST"
  class="w-full flex flex-col gap-6 p-8 rounded-lg shadow-lg bg-neutral-50 dark:bg-neutral-800 max-w-md mx-auto"
> 
  <div class="flex flex-col gap-2">
    <label for="email" class="text-lg font-medium text-neutral-700 dark:text-neutral-300">Your Email:</label>
    <input 
      type="email" 
      name="email" 
      id="email"
      required
      class="p-3 border border-neutral-300 rounded-md focus:ring-2 focus:ring-secondary-500 focus:border-transparent transition duration-200 ease-in-out bg-white dark:bg-neutral-700 dark:text-white dark:border-neutral-600"
      placeholder="your.email@example.com"
    />
  </div>

  <div class="flex flex-col gap-2">
    <label for="message" class="text-lg font-medium text-neutral-700 dark:text-neutral-300">Your Message:</label>
    <textarea 
      name="message" 
      id="message" 
      rows="6"
      required
      class="p-3 border border-neutral-300 rounded-md focus:ring-2 focus:ring-secondary-500 focus:border-transparent transition duration-200 ease-in-out resize-y bg-white dark:bg-neutral-700 dark:text-white dark:border-neutral-600"
      placeholder="Tell us what's on your mind..."
    ></textarea>
  </div>

  <button 
    type="submit" 
    class="w-10 px-6 py-3 bg-primary-600 text-white font-semibold rounded-md hover:bg-primary-700 focus:outline-none focus:ring-2 focus:ring-primary-500 focus:ring-offset-2 transition duration-200 ease-in-out dark:bg-primary-500 dark:hover:bg-primary-600 dark:focus:ring-offset-neutral-800">Send Message</button>
</form>