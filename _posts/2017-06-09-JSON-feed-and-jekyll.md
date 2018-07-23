---
layout: post
title: JSON feed and jekyll
---

[JSON feed](https://jsonfeed.org/2017/05/17/announcing_json_feed) is an alternative feed format, made by Manton Reece and Brent Simmons, with the aim of reducing the complexity inherent to XML and Atom. 

The JSON feed project came to my attention after [reading John Gruber of Daring Fireball](https://daringfireball.net/linked/2017/05/17/json-feed) express his delight with the format, and how enjoyable it was to work with. For those who don't know, John is the creator of Markdown, and as he says in his own post >" I’ve got a good feeling about this project — the same sort of feeling I had about Markdown back in the day."

This, along with my desire to play around with some programming projects over the summer inspired me to try and implement a JSON feed on this blog. Now, this site is built on GitHub pages, which uses Jekyll to serve static sites. I know zero JSON, and the extent of my programming to date has all been in Java, but with a few hours to kill on a train during a family holiday, and armed with an iPad and a spotty 3G connection, it seemed like the kind of thing that could be fun to tackle.

As it stands, there seems to be a lot of buzz around JSON feed, and finding resources online to help was fairly straightforward. The first stop is obviously the [spec](https://jsonfeed.org/version/1) in order to get a sense of what's going on. Then I did a bit of searching to see how to go about implementing the feed on my site. 

[This GitHub Repo](https://github.com/vallieres/jekyll-json-feed) was a great start, as it gets the basic JSON structure in place, and honestly, within a few minutes I was able to ping [jamxf.github.io/feed.json](/feed.json), and get back usable data. At this point in time, I'm going to have look at the implementation in greater detail, the post excerpts are basically mirroring the entire article, title's and authors don't seem to report correctly, but it's a start.

This is exactly the kind of project I was hoping to get stuck into whilst on this holiday, something straightforward to get up and running, and that I can tweak whenever I have a few minutes of downtime between cities. 