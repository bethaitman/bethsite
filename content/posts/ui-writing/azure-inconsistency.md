---
title: "Azure's inconsistent messages"
date: 2015-08-18
tags: ["ui writing"]
---

Some UI writing from Microsoft’s Azure platform:

{{< figure src="/images/azure/1.png" alt="You have no Traffic Manager profiles. Create one to get started!" class="image-with-border" >}}

{{< figure src="/images/azure/2.png" alt="You have no vaults. Create one to get started." class="image-with-border" >}}

{{< figure src="/images/azure/3.png" alt="No job collections have been created. To get started, click create." class="image-with-border" >}}

{{< figure src="/images/azure/4.png" alt="You have no BizTalk Services. To get started, create one!" class="image-with-border" >}}

{{< figure src="/images/azure/5.png" alt="You have no namespaces. Add one to get started!" class="image-with-border" >}}

## The problem

It’s just so inconsistent.

I wonder if it’s deliberate - an attempt to make it seem more human? It reminds me of the job my friend James used to do. He wrote dialog for video games: hundreds of different ways for a cop to say “Hey, you there! Stop!”

Most likely, this was created by a bunch of people who don’t talk to each other.

## The fix

Make them match, clearly. It won’t seem robotic if the phrasing isn’t too formal.

So which is the best permutation? “Create” sounds like the right verb, as it matches the action in the links.

I generally go for the style “To <achieve the thing you want to do>, do <this thing>” because it puts the user task first. This sentence is so short it doesn’t matter very much though.

But is the “get started” sentence even necessary? I feel that “You don’t have any somethings. Create a something ->” is enough to make it clear what you need to do next.

And of course, you don’t need to say “Create a *new* something”. New is implied by create, so it’s unnecessary.

<!-- https://uiwriting.tumblr.com/post/127001900889/azure-inconsistency -->

