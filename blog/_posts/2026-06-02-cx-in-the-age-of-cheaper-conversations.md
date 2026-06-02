---
layout: post
title:  "CX, In the age of cheaper conversations"
date:   2026-06-02 10:00:00 
---


This piece is about CX in the era of agents. I've spent the last 6 months building in the CX space, talking to founders, operators and CX leaders to figure this out in real time. These are my findings, if you're one of those mentioned above, this is for you.

---

## The Automation Fallacy

Let's start with the most expensive mistake you can make right now: confusing deflection with experience.

[Zendesk ran a campaign](https://www.newswire.com/news/sparrowdesk-responds-to-zendesk-s-call-your-mom-campaign-with-a-human-first) not long ago with the line: *"Want to talk to a human? Call your mom."* It was meant to be bold, AI-first support as the new default. It landed as dismissive. When customers push back on full automation, they're not rejecting technology, they're rejecting the feeling of being abandoned at the exact moment they needed help. Those aren't the same thing, and conflating them is costing companies real money.

Klarna is the more expensive lesson. Between 2022 and 2024, they eliminated approximately 700 [customer service](https://finance.yahoo.com/news/firing-700-humans-ai-klarna-173029838.html) positions and replaced them with an AI assistant built in partnership with OpenAI. The early numbers looked compelling. The bot handled two-thirds of customer queries. The CEO celebrated it as proof that AI had finally arrived. Then the CSAT data came in. Customers reported generic, repetitive responses on anything nuanced. Complex issues stalled. Brand perception took a hit. By mid-2025, Klarna was quietly rebuilding its human support team. Sebastian Siemiatkowski was explicit in his Bloomberg interview: *"From a brand perspective, a company perspective, I just think it's so critical that you are clear to your customer that there will always be a human if you want."*

Guinea pig to cautionary tale in eighteen months.

The answer isn't hard: **agents handle the 80% that's well-defined, the routine, high-volume, low-judgment tickets. That frees your human reps to own the 20% that actually matters.** Edge cases. Emotionally loaded situations. The call where a customer is two seconds from churning and one rep who actually gets it can turn it around. When that call comes in, there are no hold times, because your agents aren't buried in tickets they shouldn't be handling in the first place. That's what exceptional CX feels like.

*If you're running CX:* resist the pressure to report headcount reduction as proof of AI ROI. Focus on topline revenue and the resolution quality on your hardest tickets, these are the right metrics. Two years from now, when everyone in the industry is using agents, your agent will get compared to my agent and not the human rep. The 'cost reduction' thesis is a temporary bubble that is about to burst.

---

## Chat Agents > Voice Agents

A customer picks up the phone when every other channel has already failed them. If they reach an AI there too, you've failed twice, and a double failure is harder to recover from than the original issue.

Chat has different psychology. Chatbots existed before agents. Customers have already calibrated their expectations. They'll engage productively with a chat agent if it actually works. Most inbound traffic via chat and email is noise anyway: duplicates, low-intent queries, things that resolve themselves with a decent FAQ. Chat agents deflect that cleanly, leaving your human reps for the signal that's left. The productivity story here is clean and real.

The voice AI ROI story is messier. Despite billions flowing into voice AI, call center employment hasn't declined. It keeps [growing](https://www.a16z.news/p/charts-of-the-week-it-was-a-good#:~:text=Demand%20for%20customer%20service%20reps%20has%20perked%20up%2C%20more%20so%20than%20the%20field%3A). Voice AI hasn't displaced the industry. It's largely added [cost and complexity](https://www.a16z.news/p/charts-of-the-week-it-was-a-good#:~:text=humans%20v.%20AI%20call%20center%20reps) on top of it. The deployment overhead is real, the behavioral resistance from customers is real, and the failure modes on complex issues are more visible on a phone call than in a chat window.

*If you're building in this space:* chat agents have faster time-to-value, less implementation friction, and a customer behavior curve that's already been bent. Voice will get better and cheaper. The models are moving fast. But changing how customers feel about AI on a phone call is a longer game than most voice agent vendors are pricing in right now. The priority stack matters.

---

## Agents as Orchestration Layer, Not Replacement

[SoRs are going headless](https://www.salesforce.com/news/stories/salesforce-headless-360-announcement/). As agentic AI matures, systems of record don't disappear. Their interaction model changes. The agent becomes the primary interface; the CRM, the subscription management tool, the loyalty platform, the comms stack all become the plumbing it runs on top of. The UI dies, the logic survives.

This reframes the builder opportunity entirely. You don't need your customer to rip out their Zendesk or Salesforce. You need to wire into it. The agent orchestrates their existing stack, querying the CRM, updating the ticket, triggering retention workflows, without the overhead of a platform migration. Builders who position as an orchestration layer on the customer's existing tool stack will move faster, encounter less enterprise friction, and close deals that stack-replacement plays will lose.

*If you're a CX leader:* this means you can deploy intelligent agents today without a system migration. The integration surface is what matters. Your existing stack doesn't become a liability. The agent makes it smarter.

---

## The Pricing Model That Changes Everything

Here's the most important structural shift in the era of agents, and most people are sleeping on it: **the outputs of AI support agents are measurable and directly attributable to business outcomes in ways traditional SaaS never was.**

Think about what that means for pricing. Traditional SaaS sold access, not results. Seat-based licensing made sense when software was passive tooling. You paid for licenses whether they worked or not. Usage-based pricing was the first correction, but it leaves value on the table and still misaligns incentives: the vendor gets paid whether the agent resolves the issue or creates a new ticket. Your incentive is volume. Their incentive is resolution. Those aren't the same thing.

**Outcome-based pricing** is where incentives finally align. You charge a premium only when the desired result is achieved. The vendor has skin in the game. The customer pays for value delivered, not tokens consumed.

[Sierra](https://sierra.ai/blog/outcome-based-pricing-for-ai-agents) is the clearest proof that this model works in CX. They crossed [$100M ARR in under 21 months](https://finance.yahoo.com/markets/stocks/articles/sierra-raises-950m-15-8b-154125641.html), hit $150M+ entering year three, and raised at a $10 billion valuation. Half their customers have revenue exceeding $1 billion, 40% of customers are Fortune 50. Their explicit thesis, you only pay when the AI achieves a predefined result, is also their sharpest competitive weapon against incumbents. Legacy CX vendors can't offer outcome-based pricing without cannibalizing their own seat revenues. Every effective AI agent they deploy reduces the number of licenses their customer needs. That conflict doesn't get resolved easily and only [few](https://x.com/eoghan/status/2028522852044206258) would cross the chasm.

Here's what outcome-based pricing requires on the builder side: **you have to own the workflow end-to-end.** You can't charge for outcomes you don't control. Generic tooling, giving CS teams an AI sandbox to configure themselves, won't get you there. You need to be an applied AI company that takes ownership of business processes, not a platform company that sells affordances and hopes someone makes it work.

This is what makes room for the [Palantir FDE model](https://www.ycombinator.com/library/Mt-the-fde-playbook-for-ai-startups-with-bob-mcgrew). Scope each customer's workflows deeply through forward-deployed engineers. Pre-negotiate a price per outcome. Build to that spec. The scalability tradeoff is real. This isn't a PLG motion, and it requires a specific kind of hire who can operate embedded inside a customer's org. But it enables wallet-share focus over market-share focus, and it builds the kind of operational trust that compounds. Palantir [delivered 640% returns over five years](https://www.mindstudio.ai/blog/palantir-forward-deployed-engineer-model-anthropic-openai) on the back of this model. [Anthropic and OpenAI just announced major enterprise deployment ventures explicitly copying it.](https://www.mindstudio.ai/blog/anthropic-openai-copying-palantir-forward-deployed-engineer-model) The pattern holds.

*If you're building for enterprise and mid-market:* the FDE path is harder to staff and slower to scale. It's also the path where you can charge what your outcomes are actually worth.

---

## The Lifecycle Agent: What Comes After Support

The cost of an AI-driven customer conversation is collapsing. That's the fuel for what comes next.

When marginal conversation cost approaches zero, the entire customer lifecycle becomes a real-time, continuous interaction, not a series of discrete touchpoints. This is what makes proactive agents possible: systems that don't wait for a support ticket, but monitor customer behavior, anticipate friction before it becomes churn, push personalized retention offers, and close the loop from initial purchase recommendation through post-purchase support.

The architectural insight here is important: **every one of those is a customer-facing agent.** That's not five different products from five different vendors. It's one coherent system that owns the relationship. The artificial separation between marketing, sales, support, and retention is a legacy of organizational silos, not customer reality. The customer doesn't experience these as different functions. Soon, the technology won't either. The economics of CX (cost per conversation, resolution rate, lifetime value impact) will collapse into a single ledger. And whoever owns that ledger will own a category.

![A layered diagram of the unified CX lifecycle. The top row shows five lifecycle stages — Discovery (Awareness), Pre-sales (Qualification), Purchase (Conversion), Support (Resolution), and Retention (Loyalty) — feeding into a single Unified CX Agent Layer (one vendor, full lifecycle, outcome-based). That layer sits on top of the systems of record it orchestrates: CRM (customer data), Comms (email, chat, voice), Loyalty (rewards & points), and Subscriptions (billing, renewals). A dashed feedback loop runs from the systems of record back into the agent layer — the data flywheel, where every interaction trains the intelligence layer.](/blog/images/lifecycle-architecture.svg)

*For CX leaders:* the vendor who owns your full customer lifecycle will own your most valuable interaction data. How that relationship gets defined, on your terms or theirs, is worth thinking about now, before the category firms up.

---

## The Moats That Aren't Being Built Right Now

Nobody has a defensible moat in this space yet. That's both the problem and the window.

The companies that commit early to outcome-based pricing and lifecycle ownership will build data flywheels that compound fast. Every resolved ticket, every saved cancellation, every successful retention interaction is a training signal, not just for the AI, but for the intelligence layer that learns what interventions work, when, and for which customer segments. That data wheel is the moat. And it can only be built by companies that own workflows end-to-end, not by those selling tooling on top of them.

The incumbents have the data in theory. Their incentive structures won't let them build toward outcomes. That gap is the opportunity, and it won't stay open indefinitely.

---

*Six months of conversations and building went into these pages. If any of it lands, or if you think I've got something wrong, I'd rather argue about it than sit on it. Reach out on [LinkedIn](https://www.linkedin.com/in/noorulwadoodkhan/) or at [noorulwadoodkhan@gmail.com](mailto:noorulwadoodkhan@gmail.com).*
