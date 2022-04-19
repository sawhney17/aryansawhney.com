---
status: scripting
public: true
tags:
- logseq
- workflows
title: The Ultimate guide to Logseq namespaces
categories:
date: 2022-01-09
lastMod: 2022-04-18
---
## Script

Namespaces are a killer feature in Logseq and can transform the way you work within it. This is Aryan and in this video, I'll be walking you through _my_ workflow with namespaces and bring you the top tips and tricks on how to get the most out of them. This is meant to be a comprehensive video so it _may_ be a bit long. I've added timestamps so you can skip around and refer back. Don't miss the quick tips section though. I **guarantee** you'll find something new or useful there

Let's start off with what are namespaces.

I like to describe namespaces as  essentially a way to create order in the chaos of tags. Generally, there is thought to be two primary structures in note taking apps, hierarchy/folder based or tags based.

Hierarchy based being apps like evernote and onenote where notes exist in folder are the primary means for organization is via folders. While tag based apps include those like Roam Research.

Both of these approaches have their own advantages and disadvantages, and most notetaking apps fall squarely in one of these categories. Logseq, is primarily a tag based app with most of the organization occurring using tags, I'll link to a video here if you're interested in learning more about it, but let's get back to the topic at hand. Namespaces.

So like I mentioned, Namespaces are a way to create order in the chaos of tags. How exactly? Namespaces _essentially_ allow you to make a page inherit from another page.

There are three cases where I'd use namespaces. First, to enable inheritance, Second is if you have two or more pages with similar names and finally, as a way to categorize and get a visual look at the category as well.

Let's start with inheritance. Let's say I've got a page about a book called, say, The Daily Stoic which consists of all my highlights from that book. Now let's say, I decide to watch Tiago Forte's videos and realize that I should probably write a review or something to help me better understand the core message. Now, I might choose to add a section somewhere down below this page, but I quickly realize that this page is **way** too huge which can impact performance, and more importantly, takes **ages** to scroll down.

What's the solution here? To create another page strikes me as an great solution. But now another question comes to the fore. This content should still, fundamentally exist as part of the page. So now how do you handle this case? Of course you could name it something like "book review for daily stoic" and perhaps link to the main daily stoic page using a tag or something. But, namespaces are a very neat solution to this. To create a namespace, you simply create a blank new page. And just name it the name of the first page _followed_ by a slash and then whatver you want to call that page.

So in this case, I'd name the page `Daily Stoic/Review`. Now, what's powerful about this method is that when I go to the Daily Stoic page, there is now a section called hierarchy and over there, you can actually see the page in a tree like structure. Where at the top layer, there is the daily stoic and in a layer below, the daily stoic/review. We can probably go a step forwards and split the **notes**, into their own page as well, this block to page plugin is a lifesaver, and now we've essentially created a hierarchy. We start at a base daily stoic page, we may add a quick summary or review or something there that you would like to have from the hover tooltip, but also a notes page and review page that are _all_ intrinsically linked.

This also allows you to essentially have multiple review pages while still keeping each review separate and connected to their respective books. This directly bridges into the next use case which is naming and differentiating repeated pages. Let me explain. Using the previous model, you essentially have a bunch of review pages, and these show up on the source page as just review, but they are, interestingly, linked to by the parent followed by the child or The Daily Stoic/Review. This means you can have _multiple_ review pages in your databse, they all appear on the source as just review _and_ they can be referred to and exist as separate pages. Cool.

Perhaps the best example of this, is however, in programming notes. Normally when you're learning new languages, a lot of the concepts are fundamentally the same, well at least in name. Functions for instance is a feature of probably every language you've learned. But how do you handle functions of different programming languages? The way I take programming notes involves me having a page for every single high level language or framework, i have pages for Swift and Javascript for instance. Now lets's say I take a few notes on how to define a function in swift. So in this case, I would tag it with "swift/functions" and right the text under this block. Let's say the next week, I'm learning python and specifically, I'm covering python functions.

I would then create a page called python/functions. Let's look back at what I've done. I've essentially covered two very similar programming concepts, but put them in their own pages based on a specific nuance. What's even cooler is how when i go to the swift page, in the section for hierarchy, I've got literally data on _every_ single topic that I've taken notes on, all organized into a nice and small list.

This may already sound a bit familiar to those who've used Evernote or Onenote or another notetaking tool in that vein, because this is essentially a list illustrating the hierarchy of a note, but combined with the power of Logseq can lead to lead to sort of a best of both worlds formulaas you can still use all your logseq features, still heavily lin kand ebed data in different places, but also be able to talk about the

The final primary use case is, once again similar to to the previous one and is really just as a way to get, at a quick glance, what a note is about. A common practice is prefixing videos with V:, Articles with D:, Courses with C: and so on. Since before I've used logseq, I've been prefixing my notes with this and this allows me, to at a glance see of what content type my notes on a video or something are.

Now, this is an example of a workflow that can be supercharged with namespaces. By naming the page, perhaps `b/atomic habits`, what ends up happening is that

> Think of a namespace as an attribute you always want to be shown
