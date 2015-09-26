---
layout: default
title: RailsBridge September 2015 Review
---

A little over a week ago a handful of enthusiastic volunteers gathered to run [another RailsBridge workshop](http://www.meetup.com/RailsBridge-Cape-Town/events/222990646/). This one was a little different for us: we've run the [Intro To Rails](https://docs.railsbridgecapetown.org/intro-to-rails/) course many times now, but at this workshop we had a number of students doing the follow up course: the [Job Board](https://docs.railsbridgecapetown.org/job-board/). It was great fun!

The Job Board course is really interesting. It uses a manual Test-Driven Development kind of approach. Students view an error in their browser, then write code, bit by bit, that fixes the error. This also gets gets students used to seeing errors: they can be scary at first, but they (and Rails especially) try to give you information on the error: where to find and (sometimes) how to fix it.

## Sponsors

An extra large thank you to our fantastic sponsors [Platform 45](http://www.platform45.com/) (for the food and drink) and [Unboxed Consulting](https://www.unboxedconsulting.com/) (for the venue and drinks on Friday night). Our delicious Saturday breakfast and lunch was provided by [The Larder](http://www.thelardercafe.co.za/).


## Changes

We're continuing to use lots of ideas from [Training From The Back Of The Room](http://www.amazon.co.uk/Training-Back-Room-Aside-Learn/dp/0787996629/) in making the workshop more interactive, fun, and a better learning experience for our attendees. We've started keeping [a list of the activities we use](https://railsbridgecapetown.org/activities.html) on our web site, for easy reference and re-use.

For this workshop, we used:

* [What you know, and what’s your plan](https://railsbridgecapetown.org/activities.html#whatyouknowandwhatsyourplan) for a warm-up exercise, sent a few days before the workshop;
* [What does an engineer look like?](https://railsbridgecapetown.org/activities.html#whatdoesanengineerlooklike) on the Saturday morning while waiting for everyone to arrive;
* [Hey, buddy](https://railsbridgecapetown.org/activities.html#heybuddy) as a closing activity.

### Upstream

A big change for us was the way we handle changes and improvements to the documentation. Our docs are a fork (a copy) of the original (upstream) [RailsBridge docs](https://github.com/railsbridge/docs). Until recently, we've tended to make changes on our local copy, and pull in changes from the upstream docs. This meant two big things: we were being a bit lazy and not sharing our improvements to the rest of the RailsBridge community; we kept running into trouble with conflicts between our docs and upstream.

After discussing it for a while, we decided to do things The Right Way. Our docs a simple fork of upstream, and any changes that we make we get into the main documentation using [Pull Requests](https://github.com/railsbridge/docs/pulls) (so that everyone (including us when we pull in the accepted changes) shares in the benefits of what we've learned). Some things that we do differently and aren't so core, like [the presentations](https://github.com/RailsBridge-CapeTown/presentations), we keep in a separate repository so that we don't run into conflits again.

### The next one!

Our next Workshop will be around the middle of December. If you attended this workshop (as a student, organiser, or a teacher) we'd love to have you back. If you were a student this time, come back and help us teach more people! :)

---

**Steve<br />
Organiser Person**
