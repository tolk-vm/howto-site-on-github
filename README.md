Demo of using github as a hosting, but content is more complex than just plain html. 
[**Here it is**](https://unserialize.github.io/howto-site-on-github)

## Purpose

This project shows **a minimal setup** for writing documentation for your github project.

Stored in the same repo **in /docs/ folder**, it is available on *&lt;username&gt;.github.io/&lt;project&gt;*.

Its content is not plain html/markdown — it is complicated, with same header/footer, variables usage, scss and so on —
but it remains a static site than can be hosted on github pages and easily tested locally.

So, finally it has **no server-side logic**, but client-side is much smarted than just bare html.

All this is done using [**jekyll**](https://jekyllrb.com/): github pages uses it under the hood. 

## Quickstart your project 

[Instruction](https://unserialize.github.io/howto-site-on-github/setup).

## Serving this website locally

1. `git clone` this repo
2. Make sure ruby, bundle and other [prerequisites](https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll) are installed
3. `cd docs`
4. `jekyll serve`, and *http://127.0.0.1:4000/howto-site-on-github/* should work  
