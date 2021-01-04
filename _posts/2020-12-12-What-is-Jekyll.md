---
title: What is Jekyll?
author: Achyuta Pataki
date: 2020-12-29 21:15:00 +530
categories: [Jekyll]
tags: [jekyll]
math: true
pin: false
---


## History of Jekyll:
Jekyll was first released by Tom Preston-Werner in 2008.Jekyll was later taken over by Parker Moore, who led the effort in releasing *Jekyll 1* and has been the new maintainer since then.

Jekyll started a web development trend towards static websites.from 2017, Jekyll is the most popular static site generator, largely due to its adoption by GitHub.

## Features of Jekyll:
Instead of using databases, Jekyll takes the content, renders Markdown or Textile and Liquid templates, and produces a complete, static website ready to be served by Apache HTTP Server, Nginx or another web server.Jekyll is the engine behind GitHub Pages, a GitHub feature that allows users to host websites based on their GitHub repositories for no additional cost. 

Jekyll is flexible and can be used in combination with front-end frameworks such as Bootstrap, Semantic UI and many others. 

Jekyll sites can be connected to cloud-based CMS software such as CloudCannon, Forestry, Netlify or Siteleaf, enabling content editors to modify site content without having to know how to code.

## What is Jekyll?
Jekyll is a parsing engine bundled as a ruby gem used to build static websites from dynamic components such as templates, partials, liquid code, markdown, etc. Jekyll is known as "a simple, blog aware, static site generator".

## What does Jekyll do?
Jekyll is installed as a ruby gem local computer. Once installed you can call `jekyll serve` in the terminal in a directory and provided that directory is setup in a way jekyll expects, it will do magic stuff like parse markdown/textile files, compute categories, tags, permalinks, and construct your pages from layout templates and partials.

Once parsed, Jekyll stores the result in a self-contained static _site folder. The intention here is that you can serve all contents in this folder statically from a plain static web-server.

You can think of Jekyll as a normalish dynamic blog but rather than parsing content, templates, and tags on each request, Jekyll does this once beforehand and caches the entire website in a folder for serving statically.

If you want to make your own jekyll site then go ahead and make it here [Make your jekyll site]({% link _posts/2020-12-12-website.md %})



