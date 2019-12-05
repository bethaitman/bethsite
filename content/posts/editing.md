---
title: "Editing"
date: 2019-11-10
---

I wanted to write about some of the things I look for when I'm editing. There are a bunch of simple ways to make your writing more readable - and I'm usually thinking about technical documentation, but this can apply to emails and other stuff too.

These things are about being clear, and I'm a bit less concerned with grammatical correctness. Glaring errors are distracting, but overall good communication is far more important than perfect writing. Once the information content is right, this post should help you make sure it's presented clearly and concisely.

Everything in this post is a guideline, not a rule: "Break any of these sooner than say anything outright barbarous." That is to say: use your common sense.

## Writing for readability

Use structure so readers aren't struggling to get to the information. This boils down to a lot of ways to avoid walls of text, and help your readers get to the information quickly.

### Use headings

Helps readers understand what's on the page at a glance, and skip to the bit that's relevant to them.

More hints on the marvellous [GOV.UK style guide](https://www.gov.uk/guidance/content-design/writing-for-gov-uk#titles).

### Use bullet points and numbered lists

If you find yourself writing "Do this, and then do this", you probably want to use a numbered list. If you find yourself writing "You need x, y and z", you probably want to use a bulleted list. They help readers understand the structure of the information you're presenting to them.

As a rule of thumb: if the order of the items matter (eg a set of instructions), it should be a numbered list. If the order doesn't matter (eg a list of prerequisites you can gather in any order), it should be bulleted.

### Use code formatting, bold etc

Especially for developer docs, code formatting can help readers skip to the bits they care about. Bold can do a similar job. But use them both sparingly - too much can get overwhelming.

### One idea per paragraph

I tend to err on the side of pretty short paragraphs. If you have just one main idea in each paragraph, they'll probably be a good length. Avoiding the wall of text.

### Sentences shorter than ~25 words

Another one I learnt from the GOV.UK team. Sentences longer than about 25 words tend to be harder to take in. Sometimes you need a long sentence for a good reason; but usually you should see if you can split it up.

### Link to relevant context

Rather than re-explaining everything everywhere.

### Use WIIFM

"What's in it for me?" ie your reader. Why should they read this page, this paragraph? How will the information be useful to them? If you tell them explicitly, much easier for them. (From [this talk](https://www.youtube.com/watch?v=IMdyx4YJ0hQ) by the inimitable Kelly O'Brien.)

## Writing concisely

Concise isn't always better, but it often helps. If you can phrase something more briefly without losing information, it's usally easier on your reader.

This section has a bunch of techniques for making your writing briefer. (See, there's the WIIFM: that's what you'll get out of reading the next bit.

### Say things directly. Instruct.

Before | After
--- | ---
"X can be done" <br> or "It is possible to do X" | "Do X"
"There is a Y that can be used to do X" | "Use Y to do X" <br> or, better, "To do X, use Y"
This applies to headings too. "Custom code generation" | "Writing a custom code generator"

### Remove tautologies

A tautology is where you say the same thing twice.

Before | After
--- | ---
"a short summary" | "a summary"
"create a new" | "create a"
"a necessary requirement" | "a requirement"

### Avoid saying it's easy or simple

Saying something is simple doesn’t actually provide any value to the user. If it’s easy, you can demonstrate that by showing there aren’t many steps to do it. Show, don’t tell.

### Use simpler tenses when you can

Often you don't need to explicitly use the future tense, or sometimes past tenses either. The present is pretty good and usually shorter.

Before | After
--- | ---
"After A has finished, B will start" | "After A finishes, B starts"

### Front-load sentences

Lead with the most important thing - usually the user goal, or a condition.

Before | After
--- | ---
"You need to do X if Y is the case" | "If Y is the case, do X." (instruct!)
"You can use A to do B" | "To do B, use A"

### Think about what's obvious from context

eg: Question talking about time. Do you need to say something is "currently" the case? Usually that only matters if you're emphasising that it'll change soon.

eg: "I think that..." It's your document, of course it's what you think. Just say the thing.

eg: "in the code you write" -> "in your code"

### Find briefer ways to say the same thing

Before | After
--- | ---
"Our belief is that" | "We believe that"
"Few things are more important than X" | "X is important"

