---
title: Quickstart your project
permalink: /setup/
---

> **How to start using jekyll: minimal setup**
>
> This steps combine [official documentation](https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll)
and my own experience.

1. Create a public repo `project-name` and git clone it

2. Make sure ruby, bundler and other [prerequisites](https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll) are installed

3. Create *docs/* folder and cd to it

4. Create new jekyll site:
```bash
jekyll new .
```

5. Edit *Gemfile*, comment gem "jekyll" and uncomment "github-pages". Then run
```bash
bundle update
```

6. Edit *_config.yml*, change:
```
baseurl: "/project-name"
url: "https://your-name.github.io"
```

7. Run `jekyll serve`, ensure `http://127.0.0.1:4000/project-name/` works

8. Git add docs, commit, push

9. In Settings of your repo enable Github pages. Source: branch master, /docs. Wait about 30 sec

10. Make sure `https://your-name.github.io/project-name/` works

11. Start writing your content, see jekyll docs and 
<a href="{{ '/jekyll/demo/2020/09/06/technical-details-and-demo.html' | relative_url }}">Technical details</a>  
