---
layout: post
title: Wednesday, Week 6
date: '2014-03-06T01:27:00-08:00'
tags:
- Phase 2
- week 6
- dev bootcamp
- frustration
tumblr_url: http://mknudsen01.tumblr.com/post/78728719531/wednesday-week-6
---
Guuuuuys, today was not the superbest.

I was really tired, and we were learning OAuth. You know how you can sign into websites using your Twitter or Google or Facebook accounts? That happens with OAuth, and we had a heck of a time trying to get it set up. Here’s a diagram of what’s going on:



We used Twitter today for our OAuth. Our goal was to create a site on which a user could log in and write tweets to their accounts on our site.

And I just had a lot of trouble with it today. That, coupled with not getting enough sleep put Matthew in a cranky mood.



We got the basic version working this afternoon, and then we had to add more complexity. We tried to make the site run faster by using background jobs. That would mean that we would tell the user that we were going to post the tweet, and we would put the tweet into a queue that would run later. That way users wouldn’t have to wait for one tweet to send entirely before they could tweet again, freeing them up to tweet every 200 milliseconds or so. Because who doesn’t want to tweet every 200 milliseconds?

We used some gems called Sidekiq and Redis. Unfortunately, this is where the wheels fell off the wagon. I spent a couple of hours dealing with the same error and never really figured it out.

That was making all of the feels worse, soooo I decided to give up on it for this evening. I’ll get some sleep tonight and come back to it tomorrow, bright-eyed and bushy-tailed.

It’s important to know when to let a problem go. The whole idea of timeboxing is stressed here at Dev Bootcamp, and it’s been a godsend. Without timeboxing, I tend to keep at a problem until I want to shake my hairbrush and aggressively flare my nostrils.



That doesn’t happen with timeboxing. If we run into an problem on something, we can timebox it instead of spin our wheels on it the entire day. We pick an arbitrary time—half an hour or so—and really throw ourselves into the problem. If we get it, awesome. If not, we can let it go.

I spent far too long on my problem today, and it put me in a sour mood.

After I let it go, I called Grace, talked to Roy about music, watched this video, and got in a way better mood. And now I’m writing!

I think I’m going to head home before eleven this evening. Even though it’s only Wednesday, it’s been a long week. I’m starting to feel a bit of burnout creeping in, so I want to go home and read for fun instead of code/read about code. This coding thing is really awesome, but I don’t want to work myself too much and get sick of it.
