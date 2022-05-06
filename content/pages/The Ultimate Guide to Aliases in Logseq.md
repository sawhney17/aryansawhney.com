---
tags:
- logseq
- aliases
- logseq features
- learn logseq
- logseq for beginners
- ultimate guide
category: logseq
title: The Ultimate Guide to Aliases in Logseq
categories: logseq
format: article
showtoc: true
date: 2022-04-12
lastMod: 2022-05-06
---
Aliases are a very powerful feature in logseq and can be used for a variety of workflows. This article will be divided into two parts: What is an Alias and How to use Aliases. Let's jump right in!

## What are aliases?

Let's dive right in! First and foremost, what is an alias? At it's core, an alias is essentially a way to _refer_ to something, be it a page link or a block reference, using another term. Let's say I've got a page called "newton's first law". It is common, that when writing, I use the term "the law of inertia". Sure these are essentially the same thing, but there is a pretty clear distinction between the terms and the context with which you would type these.

It's in these cases that aliases can come into handy.

> Aliases are for referring to a single page in more than one way

## How to use Aliases?

There are two ways to create aliases. The first is to navigate to the already existing page and simply adding a page property to the top of the page. This should follow the format of `alias:: newAliasName` and should be on the **first** block of the page. The new alias, should ideally be of an empty page so that if you click a link to ti, it will redirect to the original page, but in the case that a page by the alias name already exists, the references to that page will automatically be carried over.
![Screen Recording 2022-05-06 at 11.21.40 AM.gif](/assets/screen_recording_2022-05-06_at_11.21.40_am_1651822204933_0.gif)

_How cool!_

When linking, all you have to is use the simple double bracket syntax to bring up the auto complete menu, just as you would a normal link, and _bam_. The alias will **automatically** show up on the list of pages and you can click or hit enter on it to insert a link.

The second, is a bit cleaner and won't clutter your graph but is a bit more frictionful. For this method, you start off with the text you want your alias to show. Next, select the text and type command i. You'll see some text in the format of `[]()` be inserted, in between the square brackets should be the text you **want** to be displayed and in between the parenthesis should be the original page. You can either type the original page without any brackets or add brackets if you want auto complete.

![Screen Recording 2022-05-06 at 11.22.57 AM.gif](/assets/screen_recording_2022-05-06_at_11.22.57_am_1651822048236_0.gif)

Your syntax should finally look like: `[somePage](originalPage)` or `[somePage]([[originalPage]])`
### Aliasing Block References?

Now, this is neat and all. But is it possible to go a step further? Is it to alias a block reference? This is arguable more important than in the case of a page reference due to the fact that many times you paraphrase sentences such as while accounting for tense or the intricacies of the prose.


In these cases it would still be beneficial to link to the original block, but it's also important that the content be suited to the surrounding text + context.

So what's the solution? Similar to the second method above, you can actually just put command l on the block to insert a pair of brackets, and then link to the source block via the code `[this is a block that i am interested to write about](((62743714-2d24-4dc4-a2ea-abc8139c953f)))`

![Screen Recording 2022-05-06 at 11.29.04 AM.gif](/assets/screen_recording_2022-05-06_at_11.29.04_am_1651822353306_0.gif)

The steps are as follows

  + Select text

  + Command L

  + Inside the parenthesis, use `(())` to create a a block reference with autocomplete.

  + Done 🎉

## Final Notes

I hope this article was helpful and that there was a lot that you could learn from it. If you have any questions or feedback, feel free to contact me on twitter! Have a nice day!








