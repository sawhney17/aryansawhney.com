---
tags:
- custom css
- logseq
- logseq workflows
- logseq features
- logseq for beginners
category: logseq
showtoc: true
date: 2022-05-09
title: Page Links vs Tags in Logseq
description: Learn about the tips and tricks about the types of tags and page links. Also learn how to customize them via CSS.
categories: logseq
lastMod: 2022-05-09
---
If you're _anything_ like most people who first come to [[Logseq]], you may be wondering what's the difference between a `[[page link]]` and a `#tag`

Truth be told, the difference is **primarily** visual. For the most part, they are both the exact same in functionality. They both link to another page. If you click one it will take you to another page and both will appear on the linked references of that page as well.

So then where does the difference lie? Well the first is small and it's that a tag can only be a single word, while a page link can be more than one word. Of course it's also possible to have a multi word tag using `#[[somepage]]` which renders this point fairly insignificant.

They are, very similar but there are two cases in which they can be very different from each other.

## Visual Distinction

A signficant difference between the two forms of linking is the difference in aesthetics. Most themes, by default, have some kind of special styling applied to the tags and this can differ wildly between themes. The fact that the tags are so visually distinct and can look very different from the text means that it's typically better suited for essentially _describing_ the contents of the block while page links are better for blending in with the text and linking to things while you're writing in the middle of sentences.

By turning off brackets, using the shortcut `mod+c mod+b`, you can blend it in even further with the text.
### Customizing the appearance

Different themes come with different styles for tags by default, you should definitely take a look at a few themes to find one you like, but in the case the theme you like doesn't have the best tags design, you can always customize it!

Another very useful perk is that it is easy to customize a link that goes to a specific page, for instance, you can make all tags to the twitter page have a blue background. Below is the CSS code that you can add to your Custom.css file.

#### Customizing a page link

```css
.page-ref {
    color: teal;
}
```

#### Customizing a tag

```css
a.tag {
    font-size: 1em;
    background-color: teal;
    border-radius: 30px;
    padding: 0px;
    color: antiquewhite;
}
```

#### Customizing a tag _to_ a specific page

```css
a.tag[data-ref="twitter"] {
    font-size: 1em;
    background-color: blue;
    border-radius: 30px;
    padding: 0px;
    color: antiquewhite;
}
```

#### Customizing a page link _to_ a specific page

```css
.page-ref[data-ref="twitter"] {
    color: red;
}
```



## The tags plugin

Sure they're essentially the same, but there _is_ an extension by Gidong Kwon called, simply ["tags"](https://github.com/gidongkwon/logseq-plugin-tags). This extension, installable from the marketplace, adds an interface which you can trigger from the toolbar which gives you a glance of _all_ the tags that you have used across your entire database _and_ classify it based on the total links (only `#tags`).

![Screen Shot 2022-05-09 at 10.33.48 AM.png](/assets/screen_shot_2022-05-09_at_10.33.48_am_1652078065674_0.png)

You can see references to them and even sort based on tags with the most or least references. It's a super neat and powerful plugin which can definitely influence the way you structure your workflow.

## Special Case: Page Tags

Well there is another type of tag, and this is a page link. Similar to Aliases, as seen in [The Ultimate Guide to Aliases in Logseq]({{< ref "The Ultimate Guide to Aliases in Logseq" >}}), a page tag is something that you add to the first block in any page. You follow the syntax of `tags:: tag, anotherTag`so that it ends up looking like this.

![Screen Shot 2022-05-09 at 10.51.22 AM.png](/assets/screen_shot_2022-05-09_at_10.51.22_am_1652079086781_0.png)

What's special about these tags is that it's a property of page and is therefore associated with the entire page and not a block in particular. If you go to any of these sections, you will _also_ now see a _special_ section called "pages tagged with" which, at a glance shows you all the pages that you have tagged with it. Cool!

![Screen Shot 2022-05-09 at 11.00.40 AM.png](/assets/screen_shot_2022-05-09_at_11.00.40_am_1652079646573_0.png)

## Conclusion

Overall, my general recommendation to anyone using Logseq is to use page links, primarily in cases where you're linking as part of a sentence, for instance like the text `According to [[Dr. Brad Schoenfeld]] adding resistance training to a dietary regimen is associated with reduced body fat percentage if calories are controlled`

In the same case, if I'd like to relate it to an overarching topic of weight loss, I'd add a tag of `#[[weight loss]]` to the end of the line. This also blends in well with the tags plugin as with that plugin, you will be able to easily visualize this relationship.

Finally, you can use page tags which are my preference if the **entire** page is about a specific topic and I'd like to be directed to this page whenever I want to revisit the said topic. 

I hope this article was helpful and you could take something away from it. If you've got any feedback, requests or suggestions, feel free to write me on twitter! ¡Hasta luego!
