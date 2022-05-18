---
layout: post
title:  "Why I rebuilt my blog with Jekyll"
date:   2022-05-17 11:54:00 -0700
categories: writing development
permalink: /posts/building-jekyll-website
author: "Tim"
---

For the last 3 years, I used a crappy Wordpress website for my blog. Now, I'm using Jekyll, and you should too.

I paid Bluehost a $100 to host my website for three years, and I paid Namecheap another $12 a year for my domain name. However, I never got around to writing much because the experience sucked. 

My website had an ugly watermark at the bottom because I was using a free Wordpress theme, and I was too lazy to figure out how to customize a theme for myself. Also, the platform I was writing on (Wordpress.com) was bloated with features --- I had no idea what I was looking at half the time.

This year, I want to get in the habit of writing more, so I decided to use my 4 years of computer science education to build a better blog. 

Turns out making a clean-looking blog isn't that hard. You don't need to study CS for 4 years. Check out the [Jekyll docs][jekyll-docs] and about an hour of [video tutorials from Giraffe Academy][giraffe-academy-videos], and you'll have a new site up and running in an afternoon.

### **Why use Jekyll?**
- **It's free.** You can just host your website through Github pages (although you'll still need to buy a custom domain)
- **It's fast.** Jekyll is a static website generator. There's no backend server or databases to route through in order to fetch information to load the website.
- **It's simple.** There's not a million features you have to figure out before you can start writing. Uploading a new post is easy - create a new markdown file in the _posts folder and type away.
- **Nice (free) themes.** Jekyll has a ton of open-sourced themes that people have built over time that don't force you to display a watermark at the bottom. With a basic knowledge of html/css, you can easily customize the themes to your liking. Minima is the default (what I'm using right now), and it's clean and responsive. 

If you're interested in what led me down this rabbit hole, check out this post from Robert Heaton on his [Learnings from running a suprisingly successful blog][robert-heaton-link].

[jekyll-docs]: https://jekyllrb.com/docs/home
[giraffe-academy-videos]: https://www.youtube.com/watch?v=T1itpPvFWHI&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=1
[robert-heaton-link]: https://robertheaton.com/2014/07/26/lessons-from-a-surprisingly-successful-blog/