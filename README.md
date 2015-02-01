# Facebook Open Academy 2015 Winter: Fluentd

[![Join the chat at https://gitter.im/treasure-data/facebook-open-academy-fluentd-2015](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/treasure-data/facebook-open-academy-fluentd-2015?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

##Introduction

This is the "course page" for Facebook Open Academy's Fluentd "class".

Here are some ways in which it is like your university classes:

1. You are expected to learn new things, **including what's not explicitly listed on the syllabus**: Just like taking CS classes force you to pick up a new programming language/tool/etc. along the way, it will be the same here =)
2. You are expected to come prepared for our weekly meeting (TBD): It is a bit disingenuous for me to say this because I wasn't always prepared for my classes in college. However, I will be keeping track of everyone's progress because unlike classes where "participation" counts for ~5%, participation is everything for an open source project! But please don't be intimidated

Here are ways in which it is nothing like your university classes:

1. Most of our communication will be virtual: Apart from the hackathon, we will be in touch through mostly asynchronous communication channels such as email/mailing list/etc (see [Getting Help](#getting-help)).
2. There will not be any exam or quiz: So no sweat! No need to memorize how to prove something runs `O(N*logN)`! You will be evaluated on participation. I know this is a very loosely defined rubric. I will make it more concrete in the coming weeks as I learn more about what everyone wants to learn/what their strengths are.

Finally, this is the very first time I am "teaching" a course in any setting. As this page's URL suggests, my day job is working at a startup called [Treasure Data](http://www.treasuredata.com) where I work in engineering/marketing. If you are interested in what it's like to work at a startup, etc., ask me anytime.

##Fluentd Overview

Fluentd is open-source software that helps software engineers create unified logging infrastructure.

Log data is an important source of information. You need log data to troubleshoot your software, measure its perforance and understand how it is used (data analytics). Unfortunately, a lot of software has pretty bad logging infrastructure, and Fluentd tries to fix that.

Before Fluentd | After Fluentd
---------------|--------------
<img width="300px" src="http://www.fluentd.org/images/fluentd-before.png"> | <img width="300px" src="http://docs.fluentd.org/images/fluentd-architecture.png">

For more information, [the official website](https://www.fluentd.org) and [documentation](https://docs.fluentd.org) are a good place to start.

##Project Overview

The biggest goal of this class is **to experience what it is like to work on an open source project.** I firmly believe that "actually doing real stuff" is the best way to learn anything, so I will ask you to dive into projects. No worries. I will provide plenty of guidance along the day.

Here is a tentative list of potential projects.

1. Help us build out the [Store Heroku Logs](http://www.storeherokulogs.org) project: This projects aims to make it easier to use Fluentd on [Heroku](http://www.heroku.com) by building templates to stream Heroku app's logs into various backend systems.
2. Help us launch v0.12 documentation! Fluentd just launched a major new version, and we are working to improve its docs. Here are [the existing issues](https://github.com/fluent/fluentd-docs/labels/v0.12) related to the docs.
3. Run Fluentd on embedded Linux like Raspberry Pi, etc. to collect interesting data and do a write-up on www.fluentd.org/guides. This is fairly open-ended.
4. Work on improving Fluentd's logger libraries, or write a new one. See [here](https://github.com/fluent/) for all the official subprojects of Fluentd.
5. Improve [Fluentd UI](https://github.com/fluent/fluentd-ui), the admin web-based GUI for Fluentd. I am less familiar with this subproject, so I might not be as hands-on with this. I know the main maintainer of this project well.

## Course Logistics

- We meet at 18:00 ET virtually over Google Hangout (link to be shared).

##Paraphernalia

###Getting help

1. The mailing lists: [this mailing list](https://groups.google.com/forum/?hl=en#!forum/fluentd-foa-2015) is where I will make announcements. Also, it's a place for anyone to ask questions, share ideas, and help one another. Also, note that there is a [separate mailing list](https://groups.google.com/forum/?hl=en#!forum/fluentd) for Fluentd, which is used by Fluentd users and maintainers around the world. Feel free to participate in the discussion over there as well.
2. For questions specific to each task, it's best to ask them on the task's GitHub issue.
3. For real-time, more interactive communication, we have a [gitter room](https://groups.google.com/forum/?hl=en#!forum/fluentd-foa-2015).
4. You can always email me (I will give out my email in person). I am always willing to help, but depending on the question, it might be faster to ask on the above venues.

###Git

You need to know (or learn quickly) your way around Git. There is a lot of resources on Git online. My favorite is ["Git from the Bottom Up"](https://jwiegley.github.io/git-from-the-bottom-up/). Also, definitely check out Git's official [website](http://www.git-scm.com). Some of you might be new to the whole idea of version control system. For that, [this is a good article to learn why it's important](http://git-scm.com/book/en/v2/Getting-Started-About-Version-Control).


There are several ways to interact with GitHub:

1. One is to use the `git` command line + GitHub's web interface. This is my workflow.
2. GitHub offers GUI clients for [Mac](https://mac.github.com) and [Windows](https://windows.github.com) although I've never tried either.
3. Atlassian offers [SourceTree](https://www.atlassian.com/software/sourcetree/overview), which I use time to time on Windows (they have a Mac version too).

Knowing your way around Git will help you at 99% of the software jobs/internships that you will have. That said, the usual 80-20 rule applies: knowing 20% of its functionality gets you 80% of the way. If you have tough time doing anything, feel free to ask any of us =)


###Recommended Readings on Open Source in General

- ["How to be an Open Source Gardener"](http://words.steveklabnik.com/how-to-be-an-open-source-gardener) - Steve Klabnik
- ["The Cathedral and the Bazaar"](http://www.catb.org/esr/writings/cathedral-bazaar/) - Eric S. Raymond

###Getting Started with Fluentd with a Windows host machine

- [Vagrant](https://www.vagrantup.com/downloads.html)
- [Vagrant Boxes](http://www.vagrantbox.es/)
- [PuTTY to SSH into your VM](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html)
