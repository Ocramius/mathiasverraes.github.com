---
title: Extract Till You Drop
slug: extract-till-you-drop
date: 2013-09-20
layout: post
published: true
tags: [talk]
abstract: "If I'm not afraid to refactor messy code in front of a live audience, you shouldn't be afraid to do it in the comfort of your office."
image: "https://speakerd.s3.amazonaws.com/presentations/3ce44050041f0131954556f7ac4f018a/slide_0.jpg?1392394580"
---

### Screencast

There are no slides for this presentation, it's all live demoing. [The code is on GitHub](https://github.com/mathiasverraes/extract-till-you-drop).
 I prerecorded a screencast. You'll notice I haven't managed to cram in everything I hoped to show, when I wrote the abstract.
 If plenty of people are interested, I'll record more videos of refactoring techniques.

<iframe width="420" height="315" src="//www.youtube.com/embed/S9pKJxOPmWM" frameborder="0" allowfullscreen></iframe>
[Watch video on YouTube](https://www.youtube.com/watch?v=S9pKJxOPmWM)

The title refers to a quote from [Robert C. Martin](https://sites.google.com/site/unclebobconsultingllc/one-thing-extract-till-you-drop) about applying Extract Method and other refactors until every element in your
  system has just one responsibility:

<blockquote>Perhaps you think this is taking things too far. I used to think so too. But after programming for over 40+
years, I’m beginning to come to the conclusion that this level of extraction is not taking things too far at all. In fact,
to me, it looks just about right. So, my advice: Extract till you just can’t extract any more. Extract till you drop.</blockquote>

I owe a lot to Sandro Mancuso, who did a similar, much more advanced presentation in Java, which greatly inspired me to try this in PHP.
Many of the ideas here are <strike>stolen</strike> borrowed from him.

### Events

- [Symfony Live](http://london2013.live.symfony.com/speakers.html#mathias) in London, UK, September 19-20, 2013
  - The Tokyo Symfony user group turned my video into [a mini workshop](http://phpmentors.jp/post/63422732564/symfony-meetup-tokyo)
  - Mentioned by [Carol Carini](http://www.infinity-tracking.com/blog/2013/09/infinity-at-symfony-live-london-2013/)
  - Reviews on [joind.in](https://joind.in/talk/view/9334)
- [PHP Benelux](http://conference.phpbenelux.eu/2014/) in Antwerp, Belgium, January 24-25, 2014
  - Reviews on [joind.in](http://joind.in/talk/view/10271)
- [Confoo](http://confoo.ca/en/2014/session/extract-till-you-drop) in Montreal, Canada, February 24-28, 2014
   - [Feedback collected by the organizers](/img/posts/2013-09-20-extract-till-you-drop/ExtractTillYouDrop-Confoo14-feedback.pdf)
- [PHP Tour Lyon](http://afup.org/pages/phptourlyon2014/) in Lyon, France, June 23-24, 2014


### Abstract

We’ve all seen them: applications out of control. Under the pressure of deadlines and endless change requests, with the
weight of years of legacy, the code has become unmaintainable. Adding features is a slow hit and miss process. You know
something needs to be done, but nobody knows how. To change the code safely, you need tests, but to make it testable,
you need to change it. Rebuilding the system from scratch is not an option.

With the right tools, techniques, and mindset, any codebase can be brought under test, and be refactored towards a better
architecture. All without affecting the behavior of the system, and allowing the business to continue.

This presentation is not for the weak of heart. We’ll skip the theory and dive straight into the spaghetti code. We’ll
wrestle in the mud, and we’ll tame the beast, whether it wants to or not. It’s live coding, and it may fail. But it will
change how you approach legacy code forever.

<script async class="speakerdeck-embed" data-id="3ce44050041f0131954556f7ac4f018a" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>

