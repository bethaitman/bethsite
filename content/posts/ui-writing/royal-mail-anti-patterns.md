---
title: "Bad writing and anti-patterns on the Royal Mail site"
date: 2015-09-10
---

It’s a familiar part of signing up for a website or service: opting out of any marketing emails.

And the forms are often deliberately designed to make it hard to work out whether or not you’ve opted out. I assume it’s because they’re trying to trick you into consenting?

Here’s a particularly confusing example, from Royal Mail.

{{< figure src="/images/rm-before.png" alt="Royal Mail's opt in/out page" class="image-with-border" >}}

## The problem

There’s a lot of wordiness here, and it all seems design to obfuscate the meaning, making it hard for users to make a decision. 

I think that’s why there are so many unnecessary bits of text. It repeats itself a lot. It explains how to use the UI - eg “please tick the relevant options below”. 

“We will only send you information on these topics if you have opted in” - yes, that’s the point of the form, implied by “please send me information about”. It’s obvious. 

“Click on the Register button to submit this form and indicate your consent” is, superficially, explaining that these checkboxes are for opting out. But because it’s in a dense paragraph of text, it actually hides that information. You have to read it closely to find out what you need to do to **not** get sent anything.

The separation between the different “Keeping you informed” sections is pretty unclear. Are the “products, services and offers” in the second section the same as the “promotions” in the first section? As a user, it’s not obvious what you’re consenting to.

The worst part of the whole form is the use of both opt-in and opt-out checkboxes. If you select the middle set of checkboxes, you’re opting **out**. If you select the last set, you’re opting in.

That’s a nasty anti-pattern. Users expect a control to act in consistent way - that’s what you signal, as a designer, by using a control more than once. Doing it this way is deliberately confusing. 

“Keeping you informed” is very weaselly, too. It feels dishonest.

## The fix

This form boils down to something fairly simple: what can we send you information about, and how? 

Title: Contacting you

Can we send you information and updates about:

- Stamps and collectables
- Sending mail abroad
- Sending mail within the UK
- Promotions
- Other Royal Mail and Post Office products, services, and offers
- Third-party products, services and offers

Can we contact you by:

- Post
- Phone
- Email
- SMS

Eg:

{{< figure src="/images/rm-after.png" alt="Royal Mail's opt in/out page, with edits" class="image-with-border" >}}

## A caveat

I don’t work in marketing or sales. It’s possible that tricking your users into agreeing to get emails is an effective strategy for selling them things. I doubt it, but it could be true. 

But even if it is - forms like this treat your users badly. It’s disrespecting them and their wishes. And it leaves a bad taste in their mouths. 

<!-- https://uiwriting.tumblr.com/post/128776205669/bad-writing-and-anti-patterns-on-the-royal-mail -->
