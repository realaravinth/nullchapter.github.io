---
title: "Blog1"
date: 2020-11-03T18:41:58+05:30
description: "This post demonstrates features of the blog."
images: ["/imagesfile/filename.jpg"]
draft: true
math: true
series: ["Theme", "Hugo"]
authors: ["Shashank Aluru", "Alan Alexander Thomas"]
---


## Style Demo

# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


---

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Deleted text~~

This is text with inline math $\sum_{n=1}^{\infty} 2^{-n} = 1$ and with math blocks:

$$
\sum_{n=1}^{\infty} 2^{-n} = 1
$$

| Heading | Another heading |
| :----:  | :-------------: |
|  text   |      text       |
|  text   |      text       |
|  text   |      text       |

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.

Some text, and some `code` and then a nice plain [link with title](https://github.com/nullchapter "title text!").

and then

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
+ Alright then!
vs.

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

## Code

Inline `code`

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## shortcode for figure

{{< figure src="/fff.png" caption="your caption goes here, \"Null Infosec.\" by null/team" >}}