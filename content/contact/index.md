---
title: "Ready to fly?"
---

**Book a discovery call** and we'll talk about what's holding you down.

{{< rawhtml >}}
<form name="contact" method="POST" data-netlify="true" class="max-w-lg mx-auto space-y-6">
  
  <input type="hidden" name="form-name" value="contact">
  <input type="hidden" name="bot-field" style="display:none;">   <!-- Honeypot spam protection -->

  <div>
    <label class="block text-sm font-medium mb-2">Your Name</label>
    <input type="text" name="name" required 
           style="width:100%; padding:14px 16px; border:2px solid #64748b; border-radius:16px; background:#f8fafc; font-size:1rem; color:#1e2937;">
  </div>

  <div>
    <label class="block text-sm font-medium mb-2">Email Address</label>
    <input type="email" name="email" required 
           style="width:100%; padding:14px 16px; border:2px solid #64748b; border-radius:16px; background:#f8fafc; font-size:1rem; color:#1e2937;">
  </div>

  <div>
    <label class="block text-sm font-medium mb-2">Message</label>
    <textarea name="message" rows="6" required 
              style="width:100%; padding:14px 16px; border:2px solid #64748b; border-radius:16px; background:#f8fafc; font-size:1rem; color:#1e2937; resize:vertical;"></textarea>
  </div>

  <button type="submit" 
          style="width:100%; padding:16px; background:#4f46e5; color:white; font-weight:600; font-size:1.1rem; border:none; border-radius:16px; cursor:pointer; transition:all 0.2s;">
    Send Message
  </button>

</form>
{{< /rawhtml >}}