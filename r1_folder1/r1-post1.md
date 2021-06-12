---
title: "R1 - post 1"
post_status: publish
---

As we launch our public website, we want to share a bit about how it was built, and how we're managing it while building a game.  The point isn't to document the build, or to publish general tech tutorials.  More, it's meant to show how we're solving the problem of running and maintaining a public website, when *really* you're trying to build a video game.

Hint: we're doing it live in production.

And to be abundantly clear about this this series of posts (and this blog), there won't be any affiliate links, no advertisements — no attempt or possibility for us to make money or sell your data here.  That's just never something we're going to do.  This is really just to help someone who finds themselves in the same spot we were.

## The challenge

I've spent nearly all of my professional career leading server-side teams on the back-end.  UI, UX, anything in the same *room* with JavaScript — I really very interested in it, and didn't have a knack for it.  I also wasn't impressed by the technology.  It (mainly ASP.NET, jQuery, page builders,e tc.) just didn't seem to be able to keep people from having to spend hours doing trivial things like minor CSS adjustments.  Any time I had to be involved in something that would have a UI component, I would define an API, give it to the front-end developers, and run away
screaming before they could trap me in their world of Javascript-fueled insanity.

With a small studio, we really can't afford to lose time on things like that.  And as a perfectionist, it's dangerous because I will totally get sucked in if no one is there to pull me out.  So when we started building this website, being able to scale the management of it was an important consideration.

This is an edit 2