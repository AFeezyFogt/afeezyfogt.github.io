---
layout: post
title: Switching to Jekyll
description: "Moving my site from WordPress to Jekyll."
modified: 2015-03-15
tags: [web design, jekyll, wordpress, ghost]
image:
  feature: jekyll-ghost-middleman-wordpress.jpg
  credit: 
  creditlink: 
share: false
---
##Switching blog platforms

When I launched my new website, I decided to reevaluate the platform I was using. With my awesome job, I had to learn to be comfortable with [Github](http://www.github.com) and taken a course to learn Ruby, so I thought I'd look at a few other options. I've used Blogger (which I found limiting) and then moved to WordPress, which I had been using for various projects for about 9 years now.

###Out with the old

Don't get me wrong, WordPress is a great and has several perfect use case scenarios. With a small learning curve, it's easy to get people on board with and to get started. There is no shortage of themes and plugins available to do whatever it is you need to do.

If I were to need an option for a client who wanted a website that he/she could update or have a team working on, WordPress would be a great CMS that I would still recommend. Several of the sites that my wife and I use are still WordPress. So why not here? I moved from WordPress for a few reasons.

  1. *WordPress becomes bloated and slow.* There are a ton of plugins for WordPress, which is convenient for several use cases. On the flip side, the plugins can slow down. Even when utilizing cacheing, optimizing images, and upgraded hosting, WordPress still gets bogged down.

  2. *Want to move away from MySQL and PHP.* Not really such a big deciding factor for me, but I everything on WordPress is stored first and foremost in a database. Like I said, not a huge deal, but there are other options that don't require databases or server-side language. Moving from WordPress opens up and simplifies hosting.

  3. *Markdown isn't native.* Again, not make or break, but not convienent. I like markdown - it's easy to learn and simple and fast to use. I can add it to WordPress.

  4. *Over Plugins.* Plugins take time. Sure they offer solutions, but you have to keep up with them. Plus, as we've learned from the [recent SEO by Yoast vulnerability](http://thehackernews.com/2015/03/wordpress-seo-by-yoast-plugin.html), plugins *can* expose your site to some vulnerabilities. I'd rather not expose my site to those issues. Not to mention, I don't want to upgrade those and check compatability every few weeks. WordPress is a growing target for hackers.

  5. *WYSIWYG is not WYSIWYG.* What you see is what you get editors don't work. They just don't. I still end up needing to use the HTML editor to make my posts look *exactly* like I want them to with WordPress. I know I can get markdown in WP, but I really don't feel like dealing with it. 

##What I looked into

Like I said before, WordPress is great. It's just not for me right now. So I looked at Jekyll, Middleman & Ghost. 

###Middleman
I've worked with Middleman for work and we were looking at starting a Middleman blog. It's a great static site generator which can blog, kind of like WordPress, which is a blog platform that can generate sites. To build a blog in Middleman, you have to add a blog gem, but it works. Middleman is great for building a site *with* a blog. 

###Ghost
Ghost is really cool and I like the philosophy behind it. Ghost has one goal:
>Ghost is a platform dedicated to one thing: Publishing. It's beautifully designed, completely customisable and completely Open Source. Ghost allows you to write and publish your own blog, giving you the tools to make it easy and even fun to do.

Pretty cool, huh? They use the MIT open-source license, giving the user freedom to do just about anything.

The down side? Ghost is built on Node. I don't have anything particular against Node, but I'm much more comfortable in Ruby. You have to use a Node.js capable server and if you make small changes on your server and you have to restart Node. I want to keep working on making Ruby magic and I'm not ready to jump into Node.

Before I jump in to why I chose Jekyll, a quick note about [Medium](http://www.medium.com). I'm  watching the development of Medium and waiting to see where it goes. I like the community that's developing around Medium, but I'm not sure I'm ready to commit to it for the long term. Plus, I can't host my own Medium blog, so I'm out (for now).

###Jekyll
I'm pretty excited by Jekyll to be honest. It's fast, simple and writing really couldn't be any easier. Not to mention, I'm running [Octopress 3.0](https://github.com/octopress/octopress) which brings quite a bit of simplicity to the already easy-to-use Jekyll like easily creating and publishing drafts, unpublishing posts, and creating new posts from the command line. Not to mention, Jekyll 3.0 is just around the corner with the promise of upgrades like Liquid 3, incremental regeneration and integrating basic hooks through Octopress. Like Ghost, they use the MIT open-source license, which I really dig.

I really like it so far. It's nice to not deal with server-side software, which, for me, means it just works. I load the page, and it does what it's supposed to. Since you write your posts for Jekyll in Markdown, you I can use [Sublime Text 3](http://www.sublimetext.com/3) for blogging.

I like the fact that Jekyll doesn't have a database. It simplifies things. Developing and testing locally is simple. When I push something live to my site, it works the way I want it to. Couple that with the free hosting option through [GitHub Pages](https://pages.github.com/) and I'm sold. Time will tell, but that's been my though process behind the switch.  

