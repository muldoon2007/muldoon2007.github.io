---
layout: post
title:  "Rules of thumb for a 1x developer"
date:   2020-04-17 10:00:00 -0700
categories: programming
---

# Contents
* TOC
{:toc}

# Preamble

I'm not a [10x developer](https://www.techopedia.com/definition/31673/10x-developer). I haven't been building websites since the days of dialup. I picked up programming a few years out of college because I was at a dead end in my career in government and politics.

So I've been writing code 9-5 for about five years, all of which have been at Amazon. And during that time, I also raised three kids -- who were aged 0, 0, and 2 when I started. So I was not That Guy overachieving on nights and weekends. I was taking care of my family.

I contributed to my first open-source project about a year ago. That was my first ever side project. And it was a conference website.

I have never read a book cover-to-cover on software engineering.

In summary, I am a 1x developer. I do enough to get by respectably.

## I have little to say that's of general value and haven't found the time to level up

Being a 1x developer, I make heavy use of conventional wisdom. I don't have much that's interesting or new to say about software engineering.

In general, I haven't found the time to take long stretches away from work, or to take on bigger side projects, or to read really extensively, or to dramatically overachieve. I have little pockets of time here and there.

But I'm feeling ambitious. I would like to become a 1.1x developer. I'm trying to figure out how to get there.

## My theory of bootstrapping

This post comes at a moment when I've got a bit more flexible time, due to COVID-19 and the quarantine and the fact that I'm taking some vacation days from work but can't actually go anywhere, while the kids are on "Spring Break" from our Pandemic Homeschool.

So I'm going to try to bootstrap my software engineering longbeard wisdom in the following manner:

1. Write out my inane thoughts on some software engineering topics.
2. Share out my thoughts to people smarter than me and invite vicious critique.
3. Update based on #2. 
4. Attempt to come up with a methodology for finding and prioritizing useful information to read about software engineering, or reflections based on new projects, and integrating into #1.

# The Rules

With no further ado, below are my Rules of Thumb for a 1x Developer.

## Meta

### Rule 1: Rules are good

My observation is that humans are by nature irrational, inconsistent, authoritarian pattern-seekers. That is, in general, most people will implicitly tend to set their goals in a way that pleases the Leader, that copies what other people nearby are doing, and that follows some existing pattern. Being rational and being consistent in a complicated world are both monumentally hard. Therefore, it's a really convenient shortcut to "do what your leader tells you" or "do what your peers are doing."

That strategy serves people pretty well in a lot of cases and does help build "team unity." But when your goals are really external -- something more than "team unity," but about accomplishing an objective outside of the team, then it is pretty valuable to try to be rational and consistent.

I think that rules of thumb (or if you'd like to dress them up, call them principles), help provide some guardrails, some structure, some scaffolding to allow people to step out of the pattern-following default mindset. They help reinforce a degree of logical consistency. They help focus conversations when there are a lot of competing priorities and values. And they help provide a more explicit, more thought-through shortcut when you're trying to figure out how to make a decision when there are endless options. 

Amazon, where I work, is pretty well-known for having a set of principles that are fairly ubiquitous and come up in hiring, in making tough decisions, in evaluating tradeoffs. And I think the company is better for having them. Not so much because they contain any special pearl of genius, but just because having principles in general is better than falling back to the follow-the-leader behavior.

Thinking is hard. Making decisions is hard. Having some thought-through rules to guide decision helps us be a bit better.

That all said, the rules of thumb below aren't really like Amazon's principles. They're mostly just rules of thumb that represent what's usually going on in my mind when I think about one of these topics.

## Productivity and learning

### Rule 2: Most of what I learn is useless outside of its immediate context

I sometimes hear people say the only thing that an IQ test measures is "how good you are at taking an IQ test." I agree with that, and with the general point that most knowledge is highly contextual. I've had about seven different "real jobs" since college, each one with a different job title. Within Amazon, I've worked on two totally different kinds of products and industries.

And what I have found is that most -- say, 90%, of what I learn at one job is completely useless for the next one. Even within the same career area. Not all of it. And that 10% might be a really important 10%, like how to be better at email or how to navigate office politics. But still most of what I learn is complete "throwaway work" when I start the next job. It's very specific knowledge about how a very specific organization operates.

Amazon is probably an extreme example, because developers here spend an enormous amount of time mastering internal tools and business concepts that literally don't exist anywhere else. I'm probably somewhat colored by that. I know that other developers have a different experience -- they master a specific technology and those skills actually do travel with them from job to job.

In education (where I did spend a few years working), there's just a fact that most knowledge is not transferable. Learning something in one domain generally does not help with any other domain.

So, selfishly, I tend to think this way: if 90% of what I'm doing today won't help me in the next job, then I should either reduce that 90% (for example, by focusing on general-purpose ideas, systems, abstractions, technologies), just not care as much about that 90% (as I used to), or find a job where I'm willing to sacrifice that 90% of my time because I think the cause is really important or the money is so good.

This rule is probably more specific to me, since I've changed careers a bunch. For other people, they've been able to transfer most of their skills from one job to the next.

### Rule 3: Focus "learning time" on things that compound

Compounding is a pretty important concept that shows up in compound interest, in Moore's Law, all over the place. It's about virtuous cycles. And so in the limited flexible time that I have, I think the rule of thumb is to focus on things that could trigger a virtuous cycle.

One perfect place to start is becoming a faster typer. I've spent a while in the past two months on keybr.com that teaches you pretty methodically how to type faster. Getting faster allows me to write more, to communicate more, to get more done in the same amount of time, because it makes almost everything I do on the computer faster.

Building lasting relationships is also a compounding activity because it gives you access to more people who can help you get things done more quickly.

Consuming media (books, blogs, whatever) is not inherently a compounding thing. Only if you have some kind of method to reflect, to digest, to incorporate your knowledge into your thoughts. If there is anything valuable in this post, you, reader, will probably not benefit from it unless you do something active to "process" it immediately.

## Programming languages

These will probably expose my ignorance pretty nicely.

### Rule 4: When to use Java or C#

Java is ideal for large enterprise applications, and it's hard to imagine Amazon, for example, running on anything else. That's because it's got the deepest libraries and community support, and the static typing makes it much easier to deal with zillions of internal data models inside a large company.

I view C# as a the Microsoft spin on Java and so would use it if I needed the some of the benefits of Java but was in the Microsoft ecosystem.

### Rule 5: When to use Python or Ruby

Python and Ruby seem to me to be pretty similar in that they're scripting languages and dynamically typed and seemed like the greatest thing in the 00's. You use them when speed is more important than legibility or debugging. And then Python for ML/AI applications.

When using Python, you should do type hinting to make life a little saner.

### Rule 6: When to use a hardcore language

I think of Go, Rust, Haskell, Erlang, Clojure, Kotlin, Scala as more hardcore languages. Out of these I've only ever shipped production code in Kotlin. 

But thinking hypothetically, I would maybe use Go/Rust if I was building a fresh web service where latency and performance were more important than community/library support. Haskell or Erlang maybe I would use if I were doing something that required a very elegant or mathematical functional approach without a lot of business logic. I don't know when I would use Clojure -- I thnk it'd be if I really came to know and love Lisp. I know that Clojure is a functional paradigm that compiles to JVM bytecode, but I'd use Kotlin for that. Since Kotlin works with Java and also has nice IntelliJ support. Same deal with Scala -- I would take Kotlin first.

### Rule 7: How to do Javascript

The worst code I ever wrote was in Javascript. I was working on a mobile shopping experince for Amazon and nobody in my group know much about JS frameworks. So we went with vanilla JQuery. At first it was pretty simple, but then we got a lot of new frontend requirements and in no time, managing the front-end state was a total nightmare -- think, components are disappearing and reappearing and we don't know why, so we're logging out every variable to the console.

So I'm one of the many who's had a bad experience. But I think it was mostly of our own doing. Now, a couple of years later, my guidelines for JS are: 

1. Use Typescript instead. It'll make life saner.
2. Try to push as much logic as possible to the server. If the front end weren't super complex, I would consider something like [Phoenix](https://www.phoenixframework.org/) instead which actually pushes everything to the server.
3. Use a framework like Vue or React if you need front interactivity.
4. Don't skip unit tests.

### Rule 8: When to use C or C++

I feel like you don't choose C -- it chooses you. There are classes of applications -- operating systems, language design, low-level programming and hardware, where you have to use C. 

C++ is an interesting one. It seems to be useful for applications like robotics and video games and high frequency trading where the performance gains from no garbage collection make it preferable to Java.

### Rule 9: Use PHP or Hack if you want to test server changes without rebuilding

PHP is banned at Amazon due to security reasons, but its successor, Hack, runs a lot of Facebook and Slack's backends, at least of 2020.

I've never considered when I would use PHP or Hack until writing this. Maybe because it's so taboo at Amazon. I know that Slack and Wikipedia use it. The Slack people claim that it's got a really developer-friendly programming environment, where for example, you don't need to restart a local server to view your changes, and that it's got web-native support for concurrency.

## Technologies

### Rule 10: When to make a microservice

I would use a microservice when I have a relatively small and simple chunk of code that needs to run every once in a while.

### Rule 11: Which database technology to choose

Choose SQL when you need to do ad hoc queries and/or you need support for ACID and transactions. Otherwise choose no-SQL. Though noSQL is [getting better with transactions](https://aws.amazon.com/blogs/aws/new-amazon-dynamodb-transactions/) and PostgreSQL (I'm familiar with the AWS Aurora flavor) is [getting better with availability, scalability, and durability](https://aws.amazon.com/rds/aurora/postgresql-features/#High_Availability_and_Durability), which have traditionally been the strengths of noSQL.

## Testing

### Rule 12: When to write a unit test

I try to write a unit test any time the expected value of a defect is non-trivial. Expected value would be: `Likelihood of a defect * Cost of a defect`. This is a sort of a copout since I can never really compute these values precisely. But at least with the code I write and the requirements I'm usually given, there's almost always a very real chance of a costly defect.

But every chunk of code should have a trivial unit test around it -- this verifies that the code is written in a testable way, which indeed is extremely important.

But I'm not the guy who thinks that every line and branch must be covered. That's a policy to apply if you can't trust yourself (or others) to do a good approximation of the expected value equation above.

### Rule 13: When to write an integration test

I'm defining an integration test as a test where you're calling code that you don't own, rather than mock it out.

I try to write an integration test whenever I can't trust the code I don't own -- especially, if it could change without me knowing.

### Rule 14: When to write an end-to-end test

I'm defining an end-to-end test as a test that simulates a complete "user session" with my product. The user could be a human or another computer that's trying to accomplish something through multiple iteractions with my code. These are usually supersets of integration tests as defined in Rule 12.

1. When I don't fully understand how the product works, and can't fully unit test a change, so I want a way to feel a little better that I didn't break everything. Mostly like a "smoke test."
2. When I need regression test cases to verify functionality in the case of a future refactor.
3. When the results are hard to know ahead of time, for example, doing a complex computation, and I want to test the effects of some code on them.

Case 1 should be avoided, but 2 and 3 you can't really get around.

## DevOps

### Rule 15: When to bring on a dedicated support engineer

At Amazon, by default, you support your code, so if something in your system goes seriously wrong, one of your peers is going to get paged and is expected to work around the clock until it's resolved.

It can be brutal. But there are pockets at Amazon (for example, my current team) and definitely at other companies, where they bring on a Site Reliability Engineer (SRE) whose job it is to be online outside of normal business hours to troubleshoot serious production problems.

After many years of dealing with this (and pushing for this on my team), I've come to believe that as a programmer, you should **always** advocate for having a dedicated SRE if there's any real risk of after-hours pages that are out of your control. A prime example is if you've inherited somebody else's code and could be paged for existing defects.

It tends not to be hard to find people in different time zones who can be trained to support your system. It's all about finding the money to pay them. Engineers on a team together need to work together to make this message clear to management.

## Security

### Rule 16: If you delegate all your IT security to the InfoSec, they will come up with draconian rules

InfoSec is a tough job. And the game theory just works out in a way that they're inevitably going to err on the side of caution. So I think the rule is that if you can do at least some of your own security, you're going to avoid the wrath of draconian restrictions. 

One great example of this is the debacle of the Amazon internal wiki migration. Back in 2015, the Amazon InfoSec team banned PHP at the company. Our internal wiki used MediaWiki, which in turn was written in PHP. Rather than question this decision -- Facebook, WordPress, and Slack were all using PHP, for example, and Facebook building the cleaned-up Hacklang to replace it -- the internal wiki team just took this InfoSec mandate as an order. To replace out MediaWiki with a Java-based alternative (XWiki) ended up taking a total fo 24 dev-years over 4+ calendar years for the team, not counting the interruptions to pretty much every other team at Amazon as their pages were getting constantly migrated and un-migrated. Had they pushed back on the PHP ban or done some more of their own research on Hack, they might have avoided this catastrophe.

## Designing and Whiteboarding

### Rule 17: Make the design session about input, not approval

There are plenty of meetings where the purpose is to "get signoff" or to "get buyin." You should avoid those and only agree to do one if you're forced to. You don't want to need "signoff." You want to be able to make your own decisions and determine what degree of agreement you need from other people.

Instead, design meetings or conversations should be about getting input and answering questions.

## Project management

### Rule 18: Estimates serve more for creating pressure than for project planning

I have been part of a lot of estimation sessions, both as a developer and as a product manager trying to ship products.

What people will say is that estimates are for planning -- that their purpose is to figure out how long some piece of work is going to take, so that everybody can plan accordingly.

In all my five years shipping stuff, I can only recall one project where things really worked that way. It was a very simple Android app -- no external dependencies, no technical complexity, just a local mySQL database and some views on it. And in that specific case, estimates were really accurate because there were very few unknowns. And we could accurately predict when things would be ready, within a day or two, and that was helpful because we had an extremely hard deadline.

That was the only project I've been a part of where we could accurately quantify our velocity and project it foward towards milestones.

In all the other projects, the main purpose of estimates was to apply pressure, to force the "but you said it would only take 5 days" kind of conversation, which in turn pressures people to work faster or harder or longer so they can avoid those conversations in the future.

I'm not against pressure per se. But I think it's important to recognize that that's the primary purpose of doing estimates.

### Rule 19: Be explicit about the difference between hard deadlines, soft deadlines, internal deadlines, and expected completion dates

**Hard deadline:** Something seriously bad to the business will happen if the deadline isn't met.

**Soft deadline:** Somebody will look bad if the deadline isn't met.

**Internal deadline:** This is a target internal to the team that will not affect anybody outside of the team.

**Expected completion date:** This is when the team currently predicts that work will be completed.

I've seen a lot of pain caused by getting these conflated. Any time you're given a deadline, ask which one of these it is. Of course, it's often the case that internal deadlines are required to be "on track" for hard deadlines. But what you want to call out is when internal deadlines are presented as hard deadlines for the sake of pressuring people to work longer.

One other trick to keep in mind: it can often happen than an engineer offers an expected completion date but then somebody else casts it into a hard deadline. That's a no-no.

### Rule 20: When somebody says Agile, push for Kanban, not Scrum

When somebody says that "we do Agile," to me, that means that there is a team meeting every two weeks. That's all that Agile means to me.

Then some people will get into the difference between two "flavors" of Agile, which are Scrum and Kanban. In my mind, Scrum means that "you have to get certain things done with those two weeks." Kanban means "do what you can do in two weeks." If it's not explicit to you whether the team follows Scrum or Kanban, you should have that conversation explicitly -- and you should push for Kanban. Given the difficulty of estimation (see Rule 18), Scrum can easily mean that you'll get pressured to work extra hours to complete something within that arbitary two-week horizon.

