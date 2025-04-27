---
title: "How human do you want your chatbot to be?"
date: 2016-06-10
---

<!-- https://uiwriting.tumblr.com/post/145703370514/how-human-do-you-want-your-chatbot-to-be -->

I’ve seen a few examples recently of people frustrated with chatbots that just don’t understand what they’re trying to say. 

Because a chatbot’s UI is conversational, people building them want their bots to be bursting with personality - and to seem like real people. Conversation gives the illusion of humanity: it makes users feel like they can speak and be understood. But the more your users feel like they’re talking to a human, the more they’ll talk like they talk to other humans. 

And that’s a problem for bots. Most of them have a very limited range of what input they can understand, and aren’t very tolerant of variation:

{{< x user="benedictevans" id="720702664552480768" >}}

It turns out the secret is to say “unusubscribe”, but nothing else. That’s a discoverability problem. The great advantage of a graphical (rather than conversational) user interface is that users can see what’s possible. To replicate this with a bot, you would need a list of options - sort of like a call centre. “Press 1 for today’s forecast, 2 for tomorrow’s, or press 3 to unsubscribe.”

Now, a bot like that doesn’t give you the illusion of humanity. What it does give you are decent odds of user success. Even if your user doesn’t reply “1″, and instead says “Today’s forecast”, you’ve given them language that they’re likely to mirror - language you can add to your list of things your bot recognises. 

In the CNN example, the bot had an unsubscribe feature - it just didn’t tell users that it existed, or how they could access it. Bots need to communicate their capabilities - and their limitations. It’s a trade-off between conciseness and usability, and between perceived humanity and user success.

To try to help, you can:

- remind your users that they’re talking to a bot, not a person
- tell your users what the bot can (and can’t) do
- give your users the language you want them to use, to make them more likely to say things your bot can understand

If you’re building a conversational UI, consider: do you want your bot to come across as human? Or do you just want to help your users get stuff done?

Other posts I thought were interesting:

- [Dan Grover on the limits of conversational UIs](http://dangrover.com/blog/2016/04/20/bots-wont-replace-apps.html)
- [Amy Thibodeau on other reasons to be careful about adding lots of personality](https://blog.prototypr.io/how-to-build-and-care-for-your-own-chatty-quirky-funny-interface-robot-5d0be81a0f50#.y5xcqnjev)
