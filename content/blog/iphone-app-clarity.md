---
date: 2026-05-25T18:57:26-04:00
draft: false
title: "Productivity with iPhone Clarity App"
---

**I Built an iPhone App Called Clarity — And It’s Becoming Part of My Workflow**

[Clarity on GitHub](https://github.com/Gripping-Relic/clarity)

A while back, I realized I was repeating a lot of actions associated with capturing ideas and discussion. I like to walk around Manhattan with my AirPods in, brainstorming by speaking into my iPhone's Voice Memos app. Turning those ideas I captured into good notes I could act on involved a lot of the same actions over and over again: transcribing, copying, pasting, summarizing, saving a file. I wanted to simplify that workflow and maybe apply it also to discussions over lunch with colleagues or meetings with clients.

So I decided to build an app that would help me with this.

I called the app **Clarity**.

### The Original Vision

The goal was straightforward: I wanted to be able to hit one big button, talk for as long as I needed — whether it was a 45-minute monologue about product ideas or a full client strategy session — and have the app transcribe everything, giving me back a clean, useful summary. No more manual note-taking to divide my attention during important conversations. Just speak, stop, and get organized thoughts delivered back to me.

I built it in Xcode using SwiftUI, Apple’s on-device recording tools, and Grok’s API for transcription and summarization.

### What Actually Happened
The app works beautifully for short voice notes — circa 5 minutes in duration. It transcribes reliably, gives me a fine summary, and lets me share natively on my iPhone. It’s genuinely better than the built-in Voice Memos app.

However, when I tried using it for the original intended purpose — long meetings and extended monologues — it fell short. The transcription would often cut off after several minutes with no warning. Apple’s peech recognition tools have some limitations with extended conversations, and even with Grok taking over, the results on long recordings aren’t always complete.

So I pivoted. Clarity turns out to be genuinely useful in a different way from what I originally planned. I use it for **short, focused voice notes** — quick ideas while walking, marketing thoughts that pop into my head, or random sparks about applications I’m developing.

Having Clarity is a boost for me. It’s noticeably better than the built-in Voice Memos app because it doesn’t just transcribe — it gives me a smart summary and lets me share the results natively on my iPhone. I like to send them to a file on my Proton Drive. That automation saves me friction every single time.

### Lessons Learned

- **Apple’s public APIs vs. their own apps**: There’s a gap between the two. The IOS app, Voice Memos, can handle long recordings beautifully because it uses newer, internal frameworks (SpeechAnalyzer) that aren’t fully available to third-party developers.
- **Existing apps**: Other apps can do more than Clarity. But the one thing it can do is something I want frequently, and I don't have to pay for more than I need.

*Sufficient to purpose* at *low cost* are driving ideas behind our client work at Gripping Relic.
Clarity lowers friction in my work every day and at a low cost. Those are wins.

### What’s Next

I’m already thinking about future improvements. I’d love to make long-form recording more reliable and add different context modes for summarization.

If you think out loud or have ideas while moving through your day, you might enjoy using Clarity, too. The project is open source on GitHub. Feel free to try it, fork it, or improve it. I’d love to hear what you do with Clarity.

[Clarity on GitHub](https://github.com/Gripping-Relic/clarity)
