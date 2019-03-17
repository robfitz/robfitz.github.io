# robfitz.github.io
Personal site and blog with a focus on newsletter signups and deep content

## Tech
* jekyll with overwritten theme/styles
* github pages
* html boilerplate
* medium css (modified)

## Content instructions

New articles go into either /_drafts or /_posts and must have a filename of `yyyy-mm-dd-title.markdown`

Front matter:
```
---
layout: post
title:  "The three types of startup partnerships"
categories: learn
---
```

Common categories include:
- learn (longer-form knowledge base)
- articles (shorter-form and opinion pieces)

The main writing panel (`.content`) is 900px wide (890px + 5px side padding)

When viewing articles with room for sidenotes, text is restricted to 690/700 for a 200px sidebar

When the browser width goes below 920, the sidebar is removed and sidenotes appear on hover/press of their main text word

Sidenote syntax:
```
<a class="has-fn">
  <span>
    sidenote text goes here and will either go into the sidebar or--on narrower screens--appear on hover/press
  </span>
  highlighted excerpt
</a>
```

## Running locally

```
bundle exec jekyll serve --drafts

http://localhost:4000
```

## Deploy

It goes live once you push to master, so deploy is just:

```
git status -s
git add *
git commit -m "commit message"
git push origin master
```
