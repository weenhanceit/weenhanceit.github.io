---
layout: post
title:  "Time for No-Pants Software"
date:   2016-06-07
categories: "posts"
---
# No-Pants Software
A friend of ours manages a middleware team at a medium-sized business.
One of his goals for this year is to sign a contract with a "no-pants"
company.

A No-Pants company is a small team of good people,
who get the job done without the usual ceremony of enterprise IT companies.
The name comes from the image of some people sitting at home
in their bathrobes,
cranking out good code.

Some of us who have been in IT for a long time
will remember when a lot of IT was done but just such teams.
IT was complicated and very detail oriented.
The type of people who were good at it
were maybe a bit eccentric,
especially considering the dominant corporate culture at the time.
If you wanted to get something really amazing done,
you _had_ to look outside the usual list of suspects
for people who could get it done.

But as the goals of IT became more ambitious,
projects became too complicated for just one or two people to deliver.
You needed teams,
and the same people who were excellent with technology,
weren't so great at working with a big team.
Unfortunately,
the people who were great working with a big team,
weren't so great working with technology.
And frankly,
there weren't a lot of people out there
who could get a big team to produce positive business outcomes.

The result,
if we're uncomfortably honest,
is 30 years of cost overruns,
schedule slips,
and systems that cause more problems than they solve.

But something good has been quietly happening over the last 20 years.
IT people have been quietly building software,
sharing it amongst themselves,
and honing it based on feedback from users.
The result is tools, processes, and communities
that enable a small team
to produce results quickly and with low risk.

Here are some of the things that make now
the time to go back to small teams
(forgive me if some of this sounds geeky.
We'll humanize it all in a minute.):

* Automated testing
* Code sharing platforms
* Peer reviews
* Web Development Frameworks
* Continuous integration, delivery, and deployment
* Open source software

## Automated Testing
In the old days,
the only way to test software was to have humans use it.
As projects got more ambitious,
the number of testers you needed grew.
The amount of effort for testing was huge.
Since the nature of software is that a change in one place
might cause a defect in another place,
we had to batch a whole bunch of software development
into one testing cycle.

But that meant the customer went months or sometimes years,
without seeing working software.
So way too often,
the development team would go way off track.
And since so much money had been spent already,
the temptation to just press on,
instead of fixing the problems,
was great.

About 25 years ago,
some programmers started using computers
to do their testing for them.
(If you're not in the IT business,
you may think it funny that we IT folks
don't use computers to help us do our work.
But it seems to be the case.
The cobbler's children often go barefoot.)

There are many advantages of having the computer do the testing:

With the computer doing the testing, it's relatively fast and cheap to test everything after every change. There are at least three big advantages in this:

* For the programmers, it's easier to figure out their mistakes
if they didn't change much since the last time they tested
* For the business,
it means the software is almost always in a working state
so you can look at working software at almost any time.
This means the programmers won't stray far
from what the business needs
* Once the application is released and in use,
it's much easier,
and less risky,
to deploy new features quickly.
So if you have a new idea that will make you an extra $10,000 a week,
you can releast that feature sooner,
and start making that return on investment that much sooner.
It also means you can release bug fixes much faster

## Code Sharing Platforms
Sharing and reusing code has been a dream
since the beginning of the IT industry.
In the last decade or so,
some of these dreams have become reality.
There are two broad categories
of code sharing breakthroughs:

* Source code control
* Package sharing

### Source Code Control
Historically,
having more than one person working on a system
was a logistical problem.
It was way too easy for one person to overwrite
their colleagues changes.

Software to address this problem has been around for a long time,
but it took a long time for that software to mature
into something really useful for modern software development.
Around 2005,
git appeared on the scene.
It built on more than 30 years of experience
in attempting to build code sharing software,
but challenged some of the long-standing assumptions
about what would work.
git caught on like wildfire,
and many other systems adopted some of the git assumptions.

Beyond just the tool,
a whole workflow sprung up,
fostered by public code sharing sites like [Github](github.com),
that is widely shared by most programmers.
This makes it much easier to find people
who can work with your team without a lot of training first.

### Package Sharing
Perl was the programming language that had the first
widely adopted
way of freely sharing standalone components
that could be incorporated relatively easily
into any program that needed them.
Since then,
other programming languages have followed suit.
Whether they're called Gems, or plug-ins, or modules,
it's easier than ever for programmers
to find some common elements that they don't have to write.

And the benefits aren't just for programmers.
When these shared components are used for the user interface
of browser-based or Web applications,
the user gets a consistent and predictable experience
across applications developed by different programmers.
It wouldn't be far-fetched to say
that modern web applications
developed by completely different teams
have a more consistent look and feel
than applications developed by large teams in the old days,
with their style guides and attempted enforcement
of user interface design.

## Peer Reviews
It's big long known in the software business
that two sets of eyes and two brains
were better than one.
Years ago,
some programmers practices "structured walkthroughs",
where two more more programmers
would read over someone's code,
and make comments.

As all these other tools became available
to speed up software development,
walkthroughs became a bottleneck to productivity.
But other practices emerged.

One of those practices is pair programming.
Pair programming is what it sounds like:
two people sitting at one keyboard.
Believe it or not,
many people are convinced that two programmers
at one keyboard produce as much or more,
than two programmers at two keyboards.
It's proven hard to design real experiments
to prove that,
but the fact that some many people do it
has to mean something.

Another practice is the review of the "pull request."
Part of the workflow of the "Github" way of source code control,
involves sending a pull request,
which is a way of saying to the team,
"Here's what I've done. Shall we include it in the product?"
There are mechanisms to return comments
to the programmer, who can then modify the code based on the comments,
or ignore them (depending on the team's rules).

There are other practices as well,
but the key point is that no-pants operations
because they're small and generally high-communication teams,
inherently take advantage of the power of peer review.

## Web Development Frameworks
In the early days of web development,
there was a lot of tedious, repetitive work.
Web frameworks emerged to reduce this burden on the programmer.
Unfortunately,
the early frameworks brought their own tedium and overhead.

Starting early this century,
and again building on the learning of the earlier attempts,
new frameworks like [Ruby on Rails](rubyonrails.org) appeared.
One of the goals of Ruby on Rails is to make it so a single programmer
can development a real application.

Rails was famous for its introductory tutorial,
which had someone develop a work blog web site
in 10 minutes.

This rapid development is key to allowing a small team
to provide working software
to business experts for review
very quickly.
Like many of these other tools and practices,
that quick business feedback is crucial
in reducing risk,
keeping projects on schedule,
and on budget.

## Continuous Integration, Delivery, and Deployment
Amazon pushes a code change to real users
on average every 9 seconds, down from 11 seconds a few years ago.
They don't do that by having teams of people
hand-configuring servers and gently installing software on them.
They, and other modern shops, use
continuous integration,
continuous delivery,
and continuous deployment
software and practices.

Continuous integration just means combining each programmer's pieces
into the whole system
almost as soon as the programmer adds each little feature.
Combined with the automated testing discussed above,
this ensures that the impact of
the inevitable misunderstandings between programmers
are minimized.

Continuous delivery means making a usable version of the system available
with each litte change.
Obviously this relies on good automated testing
and continuous integration to be successful.
Most often the product of continous delivery is available
to the business decision makers,
who decide when to give the users or customers
access to the new features.
Sometimes, however,
an organization may even choose to use continous deployment.

Continuous deployment is simply the automated deployment
of fully-tested, working software to end users,
as the software is developed.
It's the final step
in the whole cycle of reliable,
repeatable,
low-risk software release processes
that are commonly used by modern programmers.

## Open Source Software
Almost all the software we've mentioned above is open source.
For the business,
open source software means more than less cost.
The lack of up-front investment to use open source software
means you can try something,
and if it doesn't work,
you simply drop it and try something else.
You've lost a little time,
but you're not tied to justifying the big up-front investment
you have to make with commercial software.

Also since you're not making a big investment,
you don't need a big procurement process to choose the product.
Since it's not really a mistake to try a few different products,
you don't need a process the "ensures" you make the "right" decision.

But open source is more than just the software the programmers use.
It's a practice.
Many of the practices and tools that make modern software development possible,
emerged from the sharing ethos of open source developers.
Perhaps it's a bit counter-intuitive,
but experience has shown that businesses benefit more from sharing software,
than from trying to keep it to themselves.
You benefit from the sharing of answers to technical questions
on sites like [Stack Overflow](stackoverflow.com),
other companies fixing bugs for you,
and a world-wide group of people
using the software to solve problems similar to yours.

## Conclusion
In our next post,
we'll discuss how to find the right No-Pants team.

We Enhance IT provides small, focused, senior teams.
For more information, go to <{{ site.url }}>.
