---
title: "Slack's error message"
date: 2015-04-22
---

Another from Slack, but this I’m less impressed by. Main issue? It’s way too long, and it doesn’t point out the solution very clearly.

{{< figure src="/images/slack/error.png" alt="Connection trouble. Apologies, we're having some trouble with your web socket connection. We tried falling back to Flash, but it appears you do not have a version of Flash installed that we can use. But we've seen this problem clear up with a restart of your browser, a solution which we suggest to you now only with great regret and self loathing." class="image-with-border" >}}

## The problems

The self-deprecation could be nice and characterful, except that an error message is a really bad time for this. See [voiceandtone.com/failure-message](https://web.archive.org/web/20170606041859/http://voiceandtone.com/failure-message/) - in general, when a user sees an error, they want to fix it quickly. They don’t want to wait around being charmed by your personality or laughing at your jokes.

Besides, self-deprecation can come across badly if your software has genuinely just done something crap. Imagine if restarting your browser didn’t work, and you got this message over and over again? It’d hardly seem cute then.

Also, you have to read quite closely to find out how to fix the problem. The solution’s, what, 4 words long? But it’s hidden in a 28-word sentence that doesn’t give you a clear instruction.

The stuff about Flash? Just not necessary. That’s a developer-written message if ever I saw one: telling you too much about what’s gone wrong. What the app’s done to try to fix the problem doesn’t really matter here, as it doesn’t affect the fix the user needs to try. 

So yeah, it could be shorter and simpler, and it doesn’t have to become robotic in the process.

## The fix

“Sorry - we’re having trouble with your web socket connection. Try restarting your browser.” Could add “We know it’s a pain, but” if you really want to be more chatty.

<!-- https://uiwriting.tumblr.com/post/117090077219/another-from-slack-but-this-im-less-impressed -->

