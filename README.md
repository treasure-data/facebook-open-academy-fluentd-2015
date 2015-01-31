# Facebook Open Academy 2015 Winter: Fluentd

[![Join the chat at https://gitter.im/treasure-data/facebook-open-academy-fluentd-2015](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/treasure-data/facebook-open-academy-fluentd-2015?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

##Introduction

This is the "course page" for Facebook Open Academy's Fluentd "class".

Here are some ways in which it is like your university classes:

1. You are expected to learn new things, **including what's not explicitly listed on the syllabus**: Just like taking CS classes force you to pick up a new programming language/tool/etc. along the way, it will be the same here =)
2. You are expected to come prepared for our weekly meeting (TBD): It is a bit disingenuous for me to say this because I wasn't always prepared for my classes in college. However, I will be keeping track of everyone's progress because unlike classes where "participation" counts for ~5%, participation is everything for an open source project! But please don't be intimidated

Here are ways in which it is nothing like your university classes:

1. Most of our communication will be virtual: Apart from the hackathon, we will be in touch through mostly asynchronous communications such as email/mailing list/etc (Detailed info coming soon).
2. There will not be any exam or quiz: So no sweat! No need to memorize how to prove something runs `O(N*logN)`! You will be evaluated on participation. I know this is a very loosely defined rubric. I will make it more concrete in the coming weeks as I learn more about what everyone wants to learn/what their strengths are.

Finally, this is the very first time I am "teaching" a course in any setting. As this page's URL suggests, my day job is working at a startup called [Treasure Data](http://www.treasuredata.com) where I work in engineering/marketing. If you are interested in what it's like to work at a startup, etc., ask me anytime.

##Fluentd Overview

Fluentd is open-source software that helps software engineers create unified logging infrastructure.

Log data is an important source of information. You need log data to troubleshoot your software, measure its perforance and understand how it is used (=data analytics). Unfortunately, a lot of software has pretty bad logging infrastructure, and Fluentd tries to fix that.

Before Fluentd | After Fluentd
---------------|--------------
<img src="http://www.fluentd.org/images/fluentd-before.png"> | <img src="http://docs.fluentd.org/images/fluentd-architecture.png">
-----------------------------------

For more information, [the official website](https://www.fluentd.org) and [documentation](https://docs.fluentd.org) are a good place to start.

##Project Overview

The biggest goal of this class is **to experience what it is like to work on an open source project.** I firmly believe that "actually doing real stuff" is the best way to learn anything, so I will ask you to dive into projects. No worries. I will provide plenty of guidance along the day.

Here is a tentative list of potential projects.

1. Help us build out the [Store Heroku Logs](http://www.storeherokulogs.org) project: This projects aims to make it easier to use Fluentd on [Heroku](http://www.heroku.com) by building templates to stream Heroku app's logs into various backend systems.
2. Help us launch v0.12 documentation! Fluentd just launched a major new version, and we are working to improve its docs. Here are [the existing issues](https://github.com/fluent/fluentd-docs/labels/v0.12) related to the docs.
3. Run Fluentd on embedded Linux like Raspberry Pi, etc. to collect interesting data and do a write-up on www.fluentd.org/guides. This is fairly open-ended.
4. Work on improving Fluentd's logger libraries, or write a new one. See [here](https://github.com/fluent/) for all the official subprojects of Fluentd.
5. Improve Fluentd UI, the admin web-based GUI for Fluentd. I am less familiar with this subproject, so I might not be as hands-on with this. I know the main maintainer of this project well.

##Help Center

This is where I will put useful stuff =)