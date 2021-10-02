---
layout: post
title: Maria Vula "From Fiji to China"
featured-img: shane-rounce-205187
---

Maria, 2021 cohort of GBJ, is from Fiji Islands. She is the business editor working at [Fiji Sun](https://fijisun.com.fj/) based in Suva,Fiji. 
In this interview, while communicating with her, I can come closer to her 

![Maria](https://drive.google.com/file/d/1wZ6xqddqgr0MOkyVa8m9bJ0M6oZt6WM4/view?usp=sharing)

## Global, Business, Journalism 


[GitHub Pages](https://pages.github.com) can automatically generate and serve the website for you.
Let's say you have a username/organisation `my-org` and project `my-proj`; if you locate Jekyll source under `docs` folder of master branch in your repo `github.com/my-org/my-proj`, the website will be served on `my-org.github.io/my-proj`.
The good thing about coupling your documentation with the source repo is, whenever you merge features with regarding content to master branch, it will also be published in the webpage instantly.

1. Just download the source from [github.com/janczizikow/sleek](https://github.com/janczizikow/sleek/) into your repo under `docs` folder.
2. Edit site settings in  `_config.yml` file according to your project.
3. Replace `favicon.ico` and `img/logonav.png` with your own logo.

## Writing content

### Docs

Docs are [collections](https://jekyllrb.com/docs/collections/) of pages stored under `_docs` folder. To create a new page:

**1.** Create a new Markdown as `_docs/my-page.md` and write [front matter](https://jekyllrb.com/docs/frontmatter/) & content such as:

```
---
title: My Page
permalink: /docs/my-page/
---

Hello World!
```

**2.** Add the pagename to `_pages/docs.yml` file in order to list in docs navigation panel:

```
- title: My Group Title
  docs:
  - my-page
```

### Blog posts

Add a new Markdown file such as `2017-05-09-my-post.md` and write the content similar to other post examples.

### Excellence 

When I ask her to define GBJ as one word, without hestiation, she said "excellence" 

### Images TODO

Introduce gulp optimization

Breakpoint | Image Type | Width | Retina
------------ | ------------ | ------------- | -------------
xs |Post Thumb | 535px | 1070px
sm |Post Thumb | 500px| 1000px
md |Post Thumb | 329.375px | 658.75px
lg |Post Thumb | 445.625px | 891.25px
xl |Post Thumb | 353.125px | 706.25px


Breakpoint | Image Type | Width | Retina
------------ | ------------ | ------------- | -------------
xs |Post Hero | 535px | 1070px
sm |Post Hero | 500px| 1000px
md |Post Hero | 329.375px | 658.75px
lg |Post Hero | 445.625px | 891.25px
xl |Post Hero | 353.125px | 706.25px

Happy hacking!
