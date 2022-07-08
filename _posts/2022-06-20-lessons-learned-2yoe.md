---
layout: post
title: "Opinion: 2YoE Round-Up"
subtitle: at least lessons were learned.
cover-img: /assets/img/banners/2yoe-banner.png
tags: [opinion]
---

# Introduction
So I can finally say that I have wrapped up a nice and tidy 2 YoE so far, working in the same company. I thought I'd write up a post on what things I have learned thus far.


## Estimations
G*ooooooooo*d old estimations...The core of softwarer development! When estimating things it's always important to:

#### be realistic, no matter how rushed you are
Developers, especially junior ones, tend to estimate tasks based on their deadline, and not the actual time the task will take them. It is important for the estimations to reflect the time **you need** for the task to be completed, and not the time you need *for the project to be completed in time*. Otherwise you might yourself with an misplanned project and a rushed task in your hands. That's a no-no.

#### estimate for quality, not time
When you give an estimate, make sure that it reflects the time needed to **complete** the task. You might think "of course it does, dufus"...well, no it doesn't always. So let's make it clear, a task should always reflect a piece of work from start to end, not something half-assed. If you are writing code for a new feature for example, the task and its estimation should be about implementing, functional testing, unit testing, code reviews...the whole package.

## Language / Lingo
#### make terms official
You're building code happily for a while, using abbreviations for internal services like `AS` and `RGM`, writing them into commit messages, using them with your coworkers, writing them into tickets, into the code itself - and one day a stakeholder comes along during a presentation and asks you "wait...what is 'AS' and what is 'RGM'"? You happily explain what those mean, like "duh, stupid stakeholder, how can you not know", and then you get smacked with a "Those are wrong". Boom. Day ruined. Ok, maybe not ruined, but moments like these can be very frustrating for a developer so its best to prepare ahead of time and protect yourself in advance. 

When building the product or technical specifications for a project, make sure that there is a section dedicated to the language used to describe itself and its components. After these have been reviewed (with the rest of the document) you should be good to go!

On an alternate scenario, if a piece of language changes for some reason then make sure to go back to these documents and update them, and perhaps even let the team know that A = B now.

## Tasks
#### create many and create them now
If you every ask yourself "Should I open a ticket for that?" The answer is always "Y E S.". Do it. And do it now. That thing you just thought is valuable and chances are it's gonna be lost in the ever-bottomless pit of things you were sure you would remember. You won't. So just open a ticket, and worst-case scenario it's gonna be obsoleted.

But, ok, for serious, there have been a lot of times where me or a coworker would hunt down a ticket we were "sure" existed only for it to never be found. Guess what, it was probably stuck in this "Maybe we should open a ticket for this" stage, without anyone actually ever creating the damn ticket.

#### make them descriptive 
A proper ticket should contain enough details to give enough info even to someone unfamiliar with the project. Give an overview, specify the problem and its impact, give pointers to the solution (code/pseudocode, links to the affected files or the responsible piece of logic, anything).

A ticket should:
- Contain info for the ones doing the planning (impact, components affected, criticality)
- Contain info on the problem in question (what is there to be done, how did it arise, what is the current state)
- Contain info on the solution (propose a solution, highlight culprits, specify next steps)
- Contain criteria for when the task can be closed (success criteria)
- Contain metadata-like information like images/links/files etc.

## Protect yourself
Being a software engineer is a dangerous profession. Noooo don't laugh, come back. Okay, it's not very dangerous (if you ignore all the back pains & vision problems) but it can be very frustrating for yourself. There are a lot of times where due to a mistake, a misstep, a fault here or there, some bad communication or lack thereof, you damage your standing within a project or the company itself, and avoidable friction is created.

#### keep things public
Oh yeah, it's true - no secrets allowed, put all the dirty laundry out. You thing you're gonna miss a deadline? Share it, and share it publicly - not in any private channel. You *have* missed a deadline? Dear god almighty what are you doing here? Send a message already! And do it in a public channel! You just made an architectural decision when you discussed a problem with a coworker. State. It. Publicly. 

I could on, I swear. There have been a lot of times where you think "ok, this is clear" but the thing is, that it is clear to *you* and maybe only you. So, protect yourself, state it publicly so that it doesn't come back to bite you in the ass - because it will.

But it's not just that. It might be that one day an architect is gonna tell you `x=1` and the next day support the idea that it is stupid to have a design where `x=1`. Having a message or a previous thread to point to always helps :)

Making sure that a lot of transparency is involved is so freaking healthy it's unbelievable. It creates the proper image of an actual functioning team and it elevates the level of quality that can be delivered. Be transparent people.

#### make any problems known
You picked up some work for this sprint and mid-way through you realize that the tickets are crappy, or perhaps that the amount of work is too much. Well, you should very quickly state as much to your Product Owner, your Scrum Master, your team, your mentor, someone (and do it in a public channel). A developer shouldn't try to rush their work to accommodate for bad planning, and they should make it clear whatever their trying to work on is not well defined. It might not feel important at the time, but it's definitely important for the stakeholders, the managers, and anyone who cares about the quality of the team & the work that is produced and/or given to them.

#### echo the things you decided upon
Sometimes you may come out of a meeting and think that you decided on following path A, but others may have understood differently. Always make sure to clarify on "fuzzy" meeting results, and don't do anything if you're not sure whether a decision was actually taken. Even more, if during a meeting you see that a lot of buzzwords are being thrown around but no action points are being talked about - try to push for them. A meeting where nothing comes out of it is completely unfruitful and could have probably been a thread in your messaging system.

But even if the decisions were clear, after the meeting is over, it's good to post meeting notes somewhere public and tag its members, so that it's clear what was discussed and what the actions moving forward are.


## Team Character
#### create a team identity
I think it's part of a company's lifecycle at some point to have multiple teams, generating value either for other teams or for externals. The moment teams are separated I believe that each team should aspire to create its own identity. Create a logo, get a name, maybe get some goodies with the team's name/logo on them. Most importantly of course, there should be clear quality & community standards within a team, as well and clear-cut mission & vision (although those should already be clear from the moment it was created).

I believe that all of these are necessary for a team to feel like a proper team, it makes every member feel like a member of something bigger, it makes them want to uphold a level of quality, and it makes for a more fun workplace.

#### organise team events
Team events are a nice way to give to each team the time to socialize, discuss things out of the workplace, feel appreciated, and make them feel like they are part of something bigger. These don't have to be status-quo events like Easter/Christmas dinners. They could be organized to celebrate a big success, or for some quality team-building while having fun.

#### celebrate
That's it. Just celebrate. Celebrate the good things. Celebrate new members. Celebrate old members. Celebrate amazing designs. Celebrate service launches. 

Positive feedback & reinforcement are so damn important and yet often are lacking. A simple "amazing work guys" goes a long way.

## General words of wisdom
- Concurrency is never a problem, until suddenly it's a big problem.
- 'Planned' refactorings are almost never actually planned properly. (In general try to take it very slow with refactorings, they're never as easy as you think.)
- Your clients don't know what they want.
- Your project managers don't know when they want it.
- Your product owners don't know how they want it.
- Try to maintain naming consistency.
- Being 'agile' probably does not mean what you think it means - just because you have Sprints, it does not mean that you are agile.
- Salary matters, get over it.
- It's more likely that people will leave over bad higher-ups than anything else.
- Higher-ups should have the spine to admit their wrong-doings.
- Changing jobs is part of the process.
- Gathering feedback but not acting on it is extremely tiring.
- Higher-ups should lead by example.
- If a team member is encouraged to follow a different set of rules, they probably shouldn't be a member of the team.
- Creating rules and not following them yourself reflects very poorly on yourself.