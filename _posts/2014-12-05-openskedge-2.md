---
layout: post
title: OpenSkedge 2
author: Max Fierke
---

OpenSkedge development began on Decemeber 23, 2012. This was almost two years ago. During that time, I was working as an hourly technical support worker for the Carlson School of Management. I started writing OpenSkedge as a sort of challenge from my then-supervisor to replace the aged Employee Scheduler, which had begun to deteriorate.

OpenSkedge was my first modern web project. I was armed with 2007-era PHP skills honed from my experiences running Wordpress blogs, Joomla sites, and various forums during junior high and high school. It was my first project to use a mature framework, the first to use an ORM, the first to leverage things like Memcached. A lot has changed since then. I've now had almost two years of solid, modern web development experience through two different jobs in web development & devops, including development and maintenance of production systems used by a handful of people to systems used by thousands.

Between these experiences, my continued development of OpenSkedge, work on a number of other open source projects, and constant attachment to [HackerNews](https://news.ycombinator.com/), [/r/programming](https://reddit.com/r/programming), and [/r/webdev](https://reddit.com/r/webdev), I've matured significantly as a developer, particularly within the realm of web development.

## Limitations of OpenSkedge

Through my continued learning, it has become clear that OpenSkedge can become so much more. However, the current platform and architecture are not conducive to continued development. The data model was very much derived from Employee Scheduler and is a pain to work with. As a result, much of the code is needlessly complex, difficult to test, and difficult to maintain. The frontend JavaScript code is limited and was adapted directly from Employee Scheduler. When I began OpenSkedge, I had little practical JavaScript knowledge, so I opted to stick with working, legacy code, despite throwing out nearly all employee scheduler backend code. Almost two years later, JavaScript is now one of my main strengths and one of my most used tools. I've gone from using jQuery as a crutch to not being afraid of prototypical inheritance.

Additionally, in the past year and a half or so, I've been collecting feedback from a number of users and others interested in OpenSkedge. It is clear that OpenSkedge fulfills many requirements other solutions do not, but it is also clear there are many limitations and missing features.

## Development

This last summer, I began planning OpenSkedge 2, intended to be a full rewrite to support more scheduling patterns, use cases, and offer increased extensibility. The details of OpenSkedge 2 are still being worked out, but development will begin this Decemeber, following the completion of finals at the University of Minnesota.

Alongside me, there will be a few other developers helping out for at least the next few months.

Throughout this time, I'll try to provide updates as development progress. Please stay tuned and do not hesitate to contact me with questions.
