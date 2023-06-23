# How Notion Does Product

Chief Product and Technology Officer Michael Manapat.

## How far out do you plan in detail, and how has that evolved over the years?

I make the joke that we change how we plan every planning cycle and that we need to plan for planning. Historically, we didn’t really look beyond what we wanted to do in a given half. And that’s actually something we have recognized is a bit of a problem, in that we’re always solving for what we can do in a few months and not thinking as holistically as we could be about the long term. We’re figuring out how we can both maintain the coordination rigor and discipline that regular planning provides while also making sure we have the room to think more broadly about the future.

All that said, we roughly plan for each half, with differing resolutions for the two quarters. As an example, at the beginning of this year, we said for Q1, list out all of your projects in detail with a prioritization of the roadmap, and for Q2, just give some high-level bullet points of what you think you’ll be working on. We then did planning for Q2 as the quarter started, taking those bullet points and making them concrete, with some added guidance for things that changed in the company strategy between Q1 and Q2.

In terms of how teams operate within each quarter, one thing philosophically is that I don’t like mandating organization-wide process approaches—at least in terms of how teams run themselves. (We do have org-wide processes for product review; see below.) We generally leave it to individual groups or teams to figure out what type of cadence makes sense for them. These days, however, it is the case that all product teams operate on two-week sprint cycles, and those cycles are all aligned across the organization. This last sprint just started yesterday, actually, across the whole company.

What individual teams do for sprints varies a lot. Some are quite disciplined and precise—they actually write down all of the commitments they think will get done, and at the end of the sprint they will assess what exactly got done that sprint. For the teams that are, say, doing longer-term work on infrastructure, sprints are more just a unit of time and not an accountability mechanism. So the only thing that’s really shared is this two-week cycle, but there’s a lot of variation in what people do within their team.

I’m always wondering—we’re not that large a company, at 550 people—can we just be a bit more dynamic? We know what the strategy is and what our goals overall are, so can we do something a bit more continuous? The whole “we’re going to stop the whole world to figure out what to do for the next half”—it’s really important, especially for coordination with our go-to-market teams and other cross-functional ones, but within the product org it’s not clear to me that it suits our needs particularly well. But I also don’t have a better approach yet.

## How many PMs do you have?

Under 15. Out of 550 people. Our product management team is tiny. As you probably know, we waited a long time to hire product managers. We didn’t have PMs until two years ago, at around 50 or 60 engineers. I’m not sure this was actually ideal. Both Notion and my former employer Stripe are both very engineering-driven to start, and both companies have a very product-minded engineering core, which I think is a great thing. That said, there is a difference between engineers who think about product, and product managers who are out there talking to users and bringing in user feedback constantly, coordinating closely with go-to-market teams, and thinking deeply about product strategy. And I think that was missing at Notion early on. So I’m glad we have PMs now and that we’re growing the product management team.

One thing that’s interesting about Notion is that no part of the product can really be isolated. At Stripe, there were a number of essentially completely independent product lines. In the group that I managed, the products were only linked by the competencies needed to build them (beyond general product work, there was a need for machine learning and AI depth). For example, there was Radar, the fraud product. And there was Capital, a lending product. And they were linked by being ML- and AI-powered products, but they were otherwise independent—very little that Radar did would affect Capital and vice versa. You can’t decompose Notion into individual products. So if you’re working on the Project Management offering at Notion and you change how databases work, or you change how pages work, that has implications for the use of Notion as a docs tool or a wiki tool. So there is a bit more of this central planning and product coordination problem here to make sure that things are considered holistically and that people aren’t stepping over each other in a way that makes the product worse

## Do you use OKRs in some form?

Yes, we use OKRs at the company level as part of planning. The output of each of these twice-yearly planning cycles is a set of company objectives and a set of key results.

There’s more variation below the company-level OKRs. Some teams or groups do have OKRs; for example, teams working on product-led growth. In other areas, things are sufficiently nascent that a lot of our key results end up being like “ship this thing,” and it has frankly been a journey for us to figure out when so much of what we’re trying to do is zero-to-one work, and how we actually measure success. What does that look like? What is the right framework for it? I would say we’re certainly far from Google, where they have OKRs at the company, the group, the team, and the individual level.

## How do your product/design review meetings work?

This is another area where we’ve been iterating a lot. We used to have something that we called “working sessions.” They would be between 30 and 45 minutes and relatively unstructured. When the team wanted to discuss something with product leadership or we had something we wanted to discuss with the team, we’d actually just ask to meet and the prompt would be something high-level. And these ended up being basically brainstorming or ideation sessions.

What we found was we needed a bit more structure to make sure things were moving along. We also wanted to make sure that feedback from [Notion co-founders Simon Last and Ivan Zhao] and me was coming at known moments, and not just, for example, two days before launch, seemingly out of nowhere.

So what’s happening now is that we have a process where at four points in the product development process, we have a “check-in.” The four points are:

1. The statement of the user problem
2. A discussion of possible directions—what are the three or so high-level possible approaches to solve the user problem, and what does the team recommend?
3. The full solution, with high-fidelity designs and everything scoped out
4. The ship candidate, ready for a final quality check

All of these are predominantly asynchronous. At each of these steps, an engineer, designer, PM, or EM will send an email describing where they are, and then we’ll review and give feedback asynchronously. We’ll talk about everything from “What exactly is the user problem?” to “How does this thing interact with this other thing?” to sometimes nitpicky details of the product.

We’ve discovered, though, that async check-ins don’t work for some types of discussions. What are all the options you explored, and how do you think about each of them? Why did you choose them? Putting that in a doc and explaining that in writing takes a lot of time. People were spending way too much time documenting this stuff, and then when you take into account the email exchanges and then the responses and all of that, the process would drag out for quite a while.

So we’re tweaking our approach right now. For the exploration-of-the-directions step, we’re going to start focusing on in-person discussions with the team. Come in and let’s stare at Figma together, discuss the pros and cons of each variant, ask questions, and align on reasoning. We normally schedule those types of synchronous check-ins for half an hour. Sometimes they’re faster and sometimes they take longer (we had one yesterday, and it went a little bit over, to 40 minutes).

We only began doing this four-stage check-in process in February. To start, we asked for essentially all product work to go through that. By “all,” I don’t mean every single change, of course. But any project with meaningful product impact goes through this. And it has been helpful for me, as I’ve ramped up relatively recently on working with our product team, to get a sense of everything that’s going on. But as part of our next iteration, we’re also going to introduce tiering so only P0 projects get reviewed by me.

## Are product and design part of the same org? And who do PMs ultimately report to? Has this changed over the years?

We have a unified product and technology organization—engineering, product management, design, data, user research, and security all roll up to me. Our data lead, design lead, research lead, engineering and product management group leads, user research lead, plus the person working on our overall technical approach and our CISO—they’re all peers and my directs, and we frequently meet and plan together.

I personally really like this, because you get a lot of crosstalk and exposure to what’s going on with all of those people in the same room. If you go back a year, Janna, who leads user research here [and who Lenny worked with at Airbnb for many years!], and Daniel, who leads Data, weren’t frequently in the same forums even though both of their functions involve our learning about our users, their needs, how they behave, etc.

But now everyone has visibility into what the organization overall is working on, and Fatemeh, who manages our Core Product engineering group here (who Lenny also worked with at Airbnb!), can hear our Enterprise PM lead Birkan talking about plans to work with users at a particular scale and figure out what’s needed on her end. I think more gets surfaced proactively when you have a mixed leadership group like this.

## How do you structure your product teams?

Right now there are essentially four layers of teams. There are teams working on user-facing use cases or stories or workflows—for example, the project management team, or the docs and wiki team. And they own making sure that the user problems around that use case are solved well by Notion through a combination of leveraging existing primitives in the product, extending them as needed, and developing custom functionality. And then below that, figuratively speaking, there are teams that own what you might call underlying primitives, things like databases in Notion. Databases actually power both the wiki and also project management, so the team that is thinking about wikis and the team that is thinking about project management are both “clients” of this databases team (which we call “Collections” internally).

And then below that there are Notion-wide systems, like search, notifications, the sidebar, and so forth, with a PM lead—Ekin—who oversees all of these. And then below that is Infrastructure. That’s sort of how our grouping is right now. (To be clear, these layers are metaphorical and don’t correspond exactly to org structure.)

Sometimes things don’t always map cleanly onto any of these single teams. We have a product team that is thinking about the enterprise segment overall, though their day-to-day work is generally focused on what a particular persona (the enterprise buyer or admin) needs. But with that overall segment focus, they need to think about things like—okay, what do companies with 20,000 users need from a wiki product? Well, they need something like verification of pages. And then they’ll go and advocate for that even if another team builds it (which is what happened here). And also, what do they need from a data residency standpoint and data locality or security? That PM lead is also talking to Infrastructure. Large companies also need Notion to work well with other tools, which necessitates work on our API and integrations—part of the middle layers. So Birkan, that PM lead, is really just working all over Notion and doesn’t map cleanly to a single team.

## What’s in your product-team tool stack?

We use Notion for almost everything—writing, project management, presentations, etc. And we hope at least for product teams that it really can be (almost) everything for them. The “almost” here is a reference to the fact that some important things you do in product—for example, design (we use Figma), experiment setup and analysis (we use Statsig), or data analysis (we use Hex) you can’t do in Notion, and these aren’t use cases that would make sense in Notion—at least for a while. You can embed your work from many of these tools in Notion, of course, which helps keep Notion the “hub” for all our work.

Unsurprisingly, project management is a big deal for us, both in terms of how we run projects internally and how Notion can enable users to run projects as part of a connected workspace with their other knowledge (their docs, wikis, meetings, etc.). Traditionally you needed to do a fair amount of setup to get the sort of project management framework (with projects, tasks, subtasks, etc.) in Notion that you might in another, project management-specific tool. It was possible given the generality of Notion’s primitives but not always easy. We have a big launch this week that we’re very excited about—it’ll be much easier to use Notion for project management, whether for general use or for issue-tracking for engineering and product teams, and there’ll be direct support for things like sprints. Starting on the 31st, you’ll be able to add our new project management tools to any teamspace.

Notion AI is also getting extended so that it’ll automatically infer and complete information for you—by keeping project properties updated as other information changes automatically. We think this will be a big advance for how people use Notion for project management.




