---
title: How to build a personal website
author: Joey Yu
layout: post
catalog: true
tags:
    - Website
    - CS
---
### Introduction

In order to build a personal website that is accessible worldwide, you'll need to do 3 things:

1. Create your personal website artifacts;
2. Create your own domain name for your website;
3. Host your website in the internet and point your domain name to the host/provider; 

And to achieve the goals above, I basically picked up the tools/frameworks below:

* Jekyll: a framework to create your website;
* Amazon Route 53: where I purchased my [domain name](http://goplusgo.me);
* GitHub Pages: yes! Now GitHub supports hosting personal websites!

### Jekyll
Jekyll is a simple, blog-aware, static site generator perfect for personal, project, or organization sites. And there're tons of themes you can find online. The theme I choosed is forked from [here](https://github.com/chrisbobbe/jekyll-theme-prologue).

### GitHub Pages + Amazon Route 53:
Follow this [link](https://medium.com/@benwiz/how-to-deploy-github-pages-with-aws-route-53-registered-custom-domain-and-force-https-bbea801e5ea3) to deploy GitHub pages with AWS Route 53 registered custom domain and force HTTPS.

> Note: as GitHub Pages only supporst limited number of Jekyll themes and the one I used is just not the lucky ones. Therefore, we need to switch to remote-theme to make it working, see [commit](https://github.com/goplusgo/goplusgo.github.io/commit/3f5cb7aa20c67d9cec0ace0be161e334e1d821f1).
