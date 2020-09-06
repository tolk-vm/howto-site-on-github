---
layout: post
title:  "Technical details and demo"
date:   2020-09-06 18:10:00 +0300
categories: jekyll demo
---

**First installation** seemed tricky, but 
[docs](https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll),
[docs2](https://jekyllrb.com/docs/) and googling finally helped. 

**Starting for your new project** instruction: <a href="{{ '/setup' | relative_url }}">here</a>.

**This project** uses [minima](https://github.com/jekyll/minima/) jekyll style (the default one). 

Everything must be **in /docs/ folder**, in **master branch**.

Notice that **header and footer** are the same on every page, without copy-paste.

You use *.md* files, but **insert html** just in place, for example <span style="color: red">this is red</span>.

There can be **any pages**, not only blog posts. <a href="{{ '/html-inside-md' | relative_url }}">For example</a>

**Top menu items** are configured in *_config.yml*. 

Be careful with **relative urls**, see source.

There can be just **blank pages** from scratch, without header/footer: 
<a href="{{ '/blank' | relative_url }}">demo</a>. 

You can store **parts of pages** in separate files and use them using *{{ "{%- include -" }}%}*:
{%- include demo_paragraph.html -%}

To insert **images**, just use `<img>` tag *(again, careful with relative urls)*:<br>
<img src="{{ '/img/lang.png' | relative_url }}" style="width: 80px"> 

**Custom css** is in `assets/main.scss`, for example 
<span class="demo-green">green</span> and <span class="demo-green">green</span>.

**Local testing**: `jekyll serve` in *docs* folder. File watching is on, very convenient.

**Code highlighing** is done automatically, many languages supported:
```js
setTimeout(function() {
  console.log("hello")
}, 10);
```

**Unknown links** are mapped to `404.html`.



 
