---
layout: post
title:  "Every Software Project is a Startup That Will Probably Fail"
date:   2023-09-06 -0700
categories:
---

It dawned on me today. Maybe most software fails. Not in the sense that "it eventually dies after a long and respectable life." In the sense that it never actually achieves flight, never catches on, never produces more value that it cost to develop.

If you look at the level of the company, I think this is a totally uncontroversial point. We all know that most software startups fail. The stuff is hard to get right, it's prone to massive delays and hidden complexity, and finding a product-market fit is hard. Blah, blah, blah. Hence the logic of venture capital funding: let a thousand flowers bloom, and expect that 1 or 2 will turn into enormous fat-margin cash-flowers, while the rest die off.

I'm starting to wonder if it's not just the startup/VC world that experiences these dynamics. I think it's everything.

In my eleven years doing software, the majority of projects I worked on were money-losers. And this is across a range of companies and industries -- education tech, Amazon logistics and physical stores, aerospace -- and company sizes. A few of them were huge money-makers, and a good number were in the neutral-to-positive range.

To clarify, by "project," I'm talking about something that's large and customer-facing. Not a back-end Unicode migration or new integration test system or a plumbing job to redirect data flows or some incremental new feature on an existing product. I'm talking about something that requires or forces the people who use to change the way they accomplish some non-trivial task. Something that would be listed as one of the few "big rocks" on your yearly product roadmap.

Anyway, some of the projects I worked on were part of startups, but most weren't. They were projects or initiatives that were part of medium-to-large sized companies, and they didn't (usually) bankrupt the companies when they didn't work out.

Related: I had a colleague once who passed on this piece of wisdom: "All software development is R&D. As soon as it's no longer research, it can be automated and the human work goes away." That's a simplification, because there are projects that do require regular human work just for maintenance - but I think the basic point stands. 

Makes total sense, but not enough of us appreciate it. Because if you accept it, it also really changes the way you view *any* new software project regardless of whether the company itself is a startup.

If I were an executive sponsor of software initiatives, for example, I'd want to take some of the lessons from the VC world. I'd expect, and plan for, projects to just "not work." I'd bake that into expectations all the way up. And more importantly, I'd want the developers of the project to *have skin in the game* to compensate for the risk. I'd want them to share in the upside risk, just like early startup employees do with their stock options. Because in the absence of that kind of incentive and risk management structure, what I see is sort of the worst of both worlds (software and corporate politics): new software products usually fail but nobody wants to take the blame, resulting in pervasive fraud and willful ignorance and shame and scapegoating and bitterness. 

I'm sure that many software execs already take this view. Certainly at Amazon, there was plenty of talk about "willingness to fail" and operating like a federation of startups, sometimes in direct competition with each other.

I think they just miss the part about "letting the developers share in the upside." That never really happens. You might get a bonus or promotion that year if your product launched, but not on a 2-year time delay once we figure out whether your project was actually an enduring success. On the flip side, if your project fails, you might start to dislike your job, or the company, or your career path, or just sort of get numb to it and stop caring -- and I don't think those are healthy outcomes. You might be tempted to look for another job or an internal transfer, but you feel uncomfortable talking about your recent failure and so you just wait it out where you are, hoping maybe you'll have better luck on the next project. Whereas I think you want to take stock of the lessons learned and move on to the next project, and hope that it'll finally be the 1 in 10 that pays you back for the other failures.
 
I know some people live this out by changing jobs frequently, and getting meaningful equity stakes. But not everybody can change jobs all the time, and not every company can offer meaningful equity. I guess all I'm trying to suggest is that we find a better way to model that incentive structure at a "microeconomic" level within companies as well. If it's not equity stakes, maybe it's parking lot priorities, or profit-sharing, or long-term bragging rights.

This would imply that individual developers have a choice on projects to work on within a company. So I think the ideal "roadmapping" structure for a company with a non-trivial software development staff is as follows:

1. Take all the effort to maintain existing software systems. Assiduously optimize for the least amount of human effort to maintain this stuff.
2. Relentlessly document domain knowledge so that software developers don't get tied to projects just because they have specific tribal knowledge. (I know, I know, everybody always wants this, but maybe the soon-coming automated transcription of every meeting will actually help)
3. Executives maintain a list of approved projects that go through some basic sanity checking.
4. For any "new initiative" or "new project", the project proposers recruit software developers from within the company, from anybody not working on #1. The initiative is assigned an estimated value. Developers (and everyone who works on it, for that matter) ultimately get a meaningful slice of the actual value.

Yeah, yeah, I know that this is too simplistic and too messy in practice. I leave it as an objective function for the AIs to optimize for us.