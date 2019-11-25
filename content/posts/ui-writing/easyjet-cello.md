---
title: "A flight for Mr Seat Cello"
date: 2015-09-19
---

This week I came across the hilarious page that is [EasyJet’s policy for carrying musical instruments on board](https://www.easyjet.com/en/terms-and-conditions/music-instruments):

{{< figure src="/images/easyjet/before.png" alt="Easyjet musical instrument policy" class="image-with-border" >}}

## The problem

This is so wordy, and difficult to follow. A lot of the content is being defensive about their strange policy - tons of words are wasted trying to justify it. I’m not sure this is necessary. “Rules is rules”: all big instruments have to go in the hold, except cellos. If that’s the policy, that’s the policy. 

But what a bizarre system - Mr Seat Cello? Really? What happens at when I check in online - do I have to make up passport details for my cello?

Clearly the way of doing this is stupid. But I’ve been in situations where I’ve had to write about something stupid, and there’s no way of fixing it. Take the example of a searching tool I worked on. The [advanced search syntax](http://documentation.red-gate.com/ss2/how-to-search#Howtosearch-AdvancedsearchsyntaxAdvancedsearchsyntax) was a ridiculous way of supporting Boolean operators. The implementation wasn’t my decision, but that didn’t matter - I still needed to explain how it worked in a way that our users could understand.

Sometimes the stupid is out of your reach, and you won’t be able to change it. Sometimes you have to write about things that you know are ridiculous.

## The fix

I had a quick go at rewriting it. I added headings (to help users skip to the section that applies to them), simplified the language, and cut it down by about 40% (from 340 words to 195).

{{< figure src="/images/easyjet/after.png" alt="My edit of Easyjet's musical instrument policy" class="image-with-border" >}}

It could still be improved - I’m not sure about a couple of things:

- I’m not sure about removing the list of instruments - that could be the thing that’s most useful to users, rather than a set of dimensions. That’s something that could be worked out in user testing, though.
- Should I have left the insurance recommendation in? It didn’t seem to add anything.
- The ‘one item of hand baggage’ bit could still be clearer, but that’s mostly because I didn’t understand what the policy actually is. Do they get to carry an extra bag or don’t they?

## Conclusions

Writing explanations of stupid things can be really frustrating, because it’s often obvious how the thing could be made less stupid. But it’s a useful exercise in writing clearly in all circumstances.

EasyJet probably won’t make a better system for booking a seat for a cello. So in the meantime, they could at least explain clearly how you’re supposed to bring your instrument on a plane.

<!-- https://uiwriting.tumblr.com/post/129429996954/a-flight-for-mr-seat-cello -->
