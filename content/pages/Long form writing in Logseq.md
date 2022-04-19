---
public: true
status: published
category: logseq
tags:
- writing
- workflows
- plugins
title: Long form writing in Logseq
categories: logseq
date: 2022-02-20
lastMod: 2022-04-18
---
An area that has traditionally been described as one of Logseq's weak points is long form writing, with the right setup however, you can get very good experience. Hey guys, this is Aryan and in this video, I will be walking you through my long form writing setup and help you optimize the physical process of writing.

While writing long form text, such as while scripting videos, I love the experience of using both IA Writer and Ulysses. They're some of the best designed apps I've ever used and offer an unparalleled editing experience. At the same time, I absolutely love using Logseq and all mynotetaking and outlining for videos happens there.

A few months ago, I discovered a series of tweaks that made Logseq into a surprisingly polished and adept experience which has actually replaced iA writer, a dedicated writing app, in my workflow. (B: Roll)

My setup for this involves a few css tweaks and plugins. The first component of my system is the Logseq Focus Mode plugin. It's an amazing plugin which contains multiple utilities to make the editing experience in Logseq nicer. You can install it from the marketplace.

You can access the plugin settings from this icon in the toolbar and configure the actions that you want to have occur. You can configure the plugin to enter focus mode on startup or rather, which is what I use, simply click the button to enter the focus mode. To configure focus mode, simply select the options you'd like to have. I've personally enabled `hide page properties`, `line highlight`, `hide top bar` which I actually submitted as a PR to the plugin. I've also enabled the options for hide left sidebar and right sidebar just for convenience sake.

On its own, you can already see the **massive** impact this can have, with the. entire screen already looking so much neater and conducive to writing.

This already looks very nice and clean, but there's more that can still be done.

Document mode is an in built feature in Logseq which essentially allows you to treat the page as a regular Obsidian style document. You'll notice that bullets disappear and also, importantly, that clicking enter doesn't create a new block but rather a new line in the block you are already writing. This makes it so much easier to write longer paragraphs and in the case that you, like me, prefer splitting individual paragraphs into their own individual pages while still maintainging this even bulleted look, you can just use shift enter to create a new block.

_Neat!_

Makes for a great experience with the line highlighting from the previous step.

The next step are some css tweaks. The first is removing the help button on the bottom right corner. While this is normally pretty useful, you're unlikely to be trying new features while writing a long form article and it therefore makes sense to hide it to reduce the clutter on the screen.

The next tweak is going to be removing the references section. While they are amazing features, when writing in a distraction free environment, they can often distract from what is supposed to be the main focus, the text that you are making. To hide this, type the following code into your custom.css file. Both CSS tweaks that I've mentioned will be written down in the description.

Finally comes themes. iA writer is one of my favorite distraction free writing apps and I love the way it's interface is structured and designed. The amazing alexander rink has actually created an iA writer style theme for Logseq and this is the one I personally use for longer form writing sessions. Another one of my favorites for longer form writing in the Bear Theme, also by Alexander Rink.

Plugin Ideas: Something that makes the experience _even better_

[The Ultimate guide to Logseq namespaces]({{< ref "The Ultimate guide to Logseq namespaces" >}})

Hope this video was helpful and I'd love to hear more about your workflow and whether this video helped you down in the comments. If you liked this video you may like this video about task management in Logseq.

![Screen Shot 2022-03-23 at 9.40.24 AM.png](/assets/screen_shot_2022-03-23_at_9.40.24_am_1648014027584_0.png)
