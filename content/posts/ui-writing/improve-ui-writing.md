---
title: "4 practical things you can do to improve the writing in your UI"
date: 2015-09-04
tags: ["ui writing", "conferences"]
---

I gave a talk at Write the Docs this week, about how to write well for user interfaces. The video of it should be up soon - I’ll share it as soon as it gets posted. *(Edit - video is now [here](https://www.youtube.com/watch?v=LemM9PHDX6w&t=3s)!)*

In the meantime, if you want some immediate steps you can take to make your user interface better, here are four ways to do it.

## 1. Don’t name things in your UI after things in your codebase

Or at least, be really careful before you do it. What your code does internally is rarely the same as what it does for users. 

Take [this Cascade example](https://www.slideshare.net/BethAitman/before-the-docs-writing-for-user-interfaces/22?src=clipshare). Internally, this button is adding a record. But for users, it’s letting them book a holiday.

Or [this Google Drive example](https://www.slideshare.net/BethAitman/before-the-docs-writing-for-user-interfaces/29?src=clipshare). Call something what it does for users, not how it works internally.

## 2. Explain what’s going on out loud

It’s hard to get phrasing right the first time, especially if you’ve not got much space. And if you’re not careful, it’s easy to write in a way that sounds robotic.

So start by explaining what your feature does out loud, in a sentence or two. How would you tell it to a person? Then write that down.

Because people speak like this:

{{< figure src="/images/if-sign.jpg" alt="If you hit this sign, you will hit that bridge" class="image-with-border" >}}

Not like this:

{{< figure src="/images/confirm/form-resubmission.png" alt="Confirm form resubmission" class="image-with-border" >}}

Once you’ve got the meaning right, you can start cutting it down to the right size. Or if you need to, you can put your sentence into the UI, as embedded help.

## 3. Work out what’s blocking your users

Embedded help can get your users past obstacles. Work out what they need to know to complete their task, and put it in the user interface. 

If it’s essential information, and you’re leaving it out - how are they going to get past that point?

## 4. Write error messages that help users recover

The most important job of an error message is helping users move on from the error.

So tell them what they can do to fix the problem. If it’s just refresh or retry, say that. And don’t hide it away like [this](https://www.slideshare.net/BethAitman/before-the-docs-writing-for-user-interfaces/78?src=clipshare) - make it clear like [this](https://www.slideshare.net/BethAitman/before-the-docs-writing-for-user-interfaces/79?src=clipshare). 

Be specific if possible - tell them exactly what they need to know to fix, avoid, or work around the problem. 

## That’s not all

These are just a few tips, but there are so many more ways you can make the writing in your user interface better. I’m trying to put together as many examples as I can. 

So if you’re interested, take a look at the rest of my blog. If there’s something you’d like me to cover, [get in touch on Twitter](https://twitter.com/baitman) and let me know!

<!-- https://uiwriting.tumblr.com/post/128339130079/4-things-to-improve-ui-writing -->

