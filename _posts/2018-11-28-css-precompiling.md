---
layout: post
title:  "CSS precompiling"
date:   2018-11-28 01:00:00 -0600
categories: jekyll update
comments: true
---

## **I have to speed up** 

Hello. Time keeps moving forward and I have to get a grip and answer my remaining questions for this exam. It's about CSS precompiling.

#### **CSS precompiling**
\- ***Compare to regular CSS*** 

By precompiling CSS we save time coding as well as headaches. By having variables to use (by using $), there's no real need to remember what, for example, color we used before for this or that. Instead, we can assign a variable like $color-blue: #accee7; and later on, maybe miles down on the css file, we might want to use the same color but instead of trying to find that particular color-code, we simply put background: $color-blue;. 

If we had used regular CSS we instead would have to scroll and lose precious time looking for that certain code. 

Another difference is that instead of having to write bunch if properties in the same namespace (such as font), we can write:
`#main {
    font: {
        family: sans-serif;
        size: 12px;
        weight: bold;
    }
}`
Instead of, as in regular CSS:
`#main {
    font-family: sans-serif;
    font-size: 12px;
    font-weight: bold;
}`


\- ***Which techniques did I use?***

I use SCSS, which is sassy CSS. Sass itself stands for *Syntactically Awesome Stylesheets* which speaks for itself. It uses variables, mixins, and so forth and creates possible shortcuts. 

\- ***Pros and cons?***

Other than what I've already said, saving time and headaches, pros could as well be such as it is easy to learn and use. You could say it simplifies complex CSS code. 

Cons with using CSS preprocessors are for an instance that debugging becomes harder. As we compile our code with preprocessors, it is not as obvious where the bugs are if there are some. To help with this, we should use source maps. For me it's also a bit harder to learn but that is because I am more used to write regular CSS code. 

