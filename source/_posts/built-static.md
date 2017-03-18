---
title: How and why I built followthe.click using JAMstack
date: 2017-03-18 11:32:35
---



This site has been built using JAMstack, which just refers to JavaScript, APIs and Markup. That means that there are no CMS behind this whole site.

The lack of CMS means that there are no databases which would serve the content. It also means that the way how I edit and build this site is err.... a little bit more nerdy.

In fact, I'm typing this all in an text editor:

![writing content in markup](/img/text-editor.png) 

In practice I'm just typing normal text in an editor. Then I have [Hexo](https://hexo.io/) as a framework, which provides me with the basic functionality. Of course I wouldn't necessarily need a framework, but I wanted to get my hands dirty with one of them as well.

So Hexo provides me with the layout and basic functionality, but without hosting or some sort you wouldn't be able to access this site. This whole site has been hosted using [Netlify](https://www.netlify.com/), which makes the site load fast.

Basically all the files are served from their CDN around the world.

The one missing link between Hexo and Netlify is Github. Basically the publishing process is like this:
1. I make pages on my computer using Sublime Text.
2. Once I'm happy with them, they are pushed to Github.
3. Since I've integrated Github and Netlify, Netlify picks the content from Github and publishes it.
4. You can read the content.

The process of getting this to work, especially using custom domain names and all is not that difficult, but you're most likely going to hit your head against a wall a few times. That's especially true if you have never used a command line or Git before, which I assume is the case for most people reading this.

Why on earth would I then put all this effort to publish some quite simple website when I could have used Wordpress or something like that.

Here's why:
1. Wordpress has been a default for very long time. It's time to challenge the status quo every now and then.
2. To improve my technical skills further. A project is a perfect way to accomplish that goal.
3. Sites built with JAMstack are faaaaast. As a fan of quick load times, but not a fan of AMP, this serverless structure just makes sense.
4. To better understand where the technology is going. This way I can better consult my clients at [OIKIO](https://oikio.fi/en/) and be more valuable asset for them when they make technological choices.

For me all of those reasons are pretty much as important. 

Here are a few good links for you to explore if you're interested in JAMstack or just building static (but not really) websites:
* [Go static: 5 reasons to try JAMstack on your next project](https://builtvisible.com/go-static-try-jamstack/)
* [New to JAMstack? How to make a site from A to Z](https://www.netlify.com/blog/2016/11/15/new-to-jamstack-how-to-make-a-site-from-a-to-z/)
* [A Little Surprise Is Waiting For You Here — Meet The Next Smashing Magazine](https://next.smashingmagazine.com/2017/03/a-little-surprise-is-waiting-for-you-here--meet-the-next-smashing-magazine/)


