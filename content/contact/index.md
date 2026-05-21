---
title: "Ready to fly?"
description: "Book a discovery call"
---

**Book a discovery call** and we'll talk about what's holding you down.

{{< rawhtml >}}
<form name="contact" method="POST" data-netlify="true" action="/contact/" class="max-w-lg mx-auto space-y-6">
  
  <input type="hidden" name="form-name" value="contact">

  <div>
    <label class="block text-sm font-medium mb-2">Your Name</label>
    <input type="text" name="name" required style="width:100%; padding:14px; border:2px solid #64748b; border-radius:12px; background:#f8fafc;">
  </div>

  <div>
    <label class="block text-sm font-medium mb-2">Email Address</label>
    <input type="email" name="email" required style="width:100%; padding:14px; border:2px solid #64748b; border-radius:12px; background:#f8fafc;">
  </div>

  <div>
    <label class="block text-sm font-medium mb-2">Message</label>
    <textarea name="message" rows="6" required style="width:100%; padding:14px; border:2px solid #64748b; border-radius:12px; background:#f8fafc; resize:vertical;"></textarea>
  </div>

  <button type="submit" style="width:100%; padding:16px; background:#4f46e5; color:white; font-weight:600; border:none; border-radius:12px; cursor:pointer;">
    Send Message
  </button>

</form>
{{< /rawhtml >}}