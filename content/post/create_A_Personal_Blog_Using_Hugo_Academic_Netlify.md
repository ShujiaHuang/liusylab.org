---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Create A Personal Blog Using Hugo Academic Netlify"
subtitle: "Create your own personal blog using Hugo Academic and Netlify"
summary: "If you are tired of maintaining a blog on popular blogging websites and looking for a simple and easy to use blogging platform then read on ! "
authors:
    - Shujia Huang
    - Siyang Liu
tags: [blog,hugo,academic]
categories: [Technology]
date: 2019-12-13T11:12:27+05:30
lastmod: 2019-12-13T11:12:27+05:30
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Hugo Academic and Netlify"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

![cover](https://static.fungenomics.com/images/2021/07/pexels-photo-262577.jpeg)

Having a space to express your thoughts or share your knowledge is a soul satisfying endeavour for many. Hence there are multiple blogging platforms like Blogger,Wordpress etc… where we can easily create a website and start writing. I previously used Wordpress(hosted) and Blogger but eventually moved to having a platform which is more flexible to my needs and requirements.

## Issues with hosted Wordpress solution
If you are using wordpress hosted solution you need to constantly update your plugins and your wordpress core from time to time

Another big problem is of managing TLS certificates. Renewal , payments and configuration everything has to be done manually and to be honest just for a simple blog it was an overkill.

## Issues with Blogger

Blogger was definitely a notch better than wordpress as i did not have to worry about managing the application and it also provided a TLS certificate with integration with LetsEncrypt. However the customization options and theming options were very much limited.

I tried to customize my blog adding HTML and CSS but then it becomes difficult to manage the content.

## Hugo,Netlify and Academic

This blog is built using Hugo,Netlify and Academic.

[Hugo](https://gohugo.io/) is a simple framework written in Go which basically converts Markdown files into static HTML and [Academic](https://themes.gohugo.io/academic/) is a templating theme for the same.
[Netlify](https://www.netlify.com/) is a hosting platform where we can deploy our simple markdown files which would then run a build and deploy our website.

The basic advantage of using this approach are

1. We get a simple static website with no overhead of maintenance or updates.
2. Plenty of [themes](https://themes.gohugo.io/) and customization options available.
3. You are simply creating content in Markdown and Hugo+Netlify do all the magic in the backend
4. You get to preview your website locally before pushing changes to production
5. Netlify provides HTTPS service be default for its subdomain as well as any customized domain, provided your NS records point to Netlify more on this later.



> NOTE : Before doing this please ensure you take a backup of your DNS Zone records from the earlier NS provider.

> We have completed the most basic steps to start and run our own blog using Hugo,Netlify and Academic.Hope that helps you to create your own blog which is simple to maintain and easy to configure.
