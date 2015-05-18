---
layout: post
title: VPS Provisioning for Rails
---

Recently I have been researching solutions for Ruby on Rails deployment by provisioning my own VPS.

This post will not outline my solution entirely as I have not finalized the route that I will take. I will simply discuss some of the resources that I currently have and a few high-level ideas. 

I am currently using <a href="https://www.dreamhost.com/hosting/vps/">DreamHost's VPS</a> plan. I figured that I could start with them as they have been good to me in the past. Currently, I have root access to my VPS, etc. I have begun initiating installs to compile the production stack that I would like to have on my VPS. It should mirror my development environment as closely as possible.

But, after reading a few things about <a href="https://www.chef.io/chef/">Chef</a> that entail using various recipes and cookbooks I might provision the VPS now with their helpful tools.

Going the <a href="https://www.heroku.com/home">Heroku</a> route might end up costing me a lot in the long run. For now, I will keep some testing and development apps on there still. 

Of all the online deployment learning materials, one that I would like to praise is <a href="https://leanpub.com/deploying_rails_applications">Reliably Deploying Rails Applications</a>. So far, so good. Go check it out.

I'll be back with more details soon.