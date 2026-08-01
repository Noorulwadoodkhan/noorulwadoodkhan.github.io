---
layout: post
title: "The First Principles of Agent Economy"
date: 2026-08-01
---

*Note to the reader: this essay is written in the context of B2B agent companies. Its purpose is to understand the true nature of agents, the Agent as a Service model, pricing strategies, value accrual and moats.*

Agents do the work.
Every time they do, it incurs a marginal cost (inference).

These are the two basic premises of the agentic world. In the SaaS era, software was used by humans to get the job done. The work was more or less manual. Agents are a big leap forward. You now summon labour directly from the machine. It's a shift from human labour to machine labour.

Before agents, the cost of replication was near zero. With agents, every time you ask them to do something for you, it comes at a cost. This cost depends on the quality, scale and complexity of the work they're doing. These days, we call it 'token spend'.

This implies a few things for the startup world. Every agent startup is now de facto selling work (machine labour). As of now, there are primarily two ways for them to sell it. The first is usage-based, where they charge the customer for tokens consumed; the second is outcomes-based, where they charge only for successful outcomes (tickets resolved, job well done). Any hybrid model is essentially an abstraction on top of one or both.

It also implies unpredictable spend. Since agents have significant marginal cost dependent on the factors mentioned above, unpredictability in spend is inherent to the nature of agents. However, we have dealt with technologies of a similar nature before and soon companies will come up with robust pricing instruments to tackle that. A good example is that of electricity consumption and a more recent example is AWS's pay-as-you-go model. This will allow CFOs inside orgs to model and forecast budgets and ROI effectively.

Then comes the question of value. Until recently, the value of these agents was benchmarked against human labour. All ROI calculations were based on that. I believe this assumption will soon break. When customers are already using agents, your agent will get compared to your competitor's agent or whatever the customer is using. Hence the value essentially becomes 'performance delta': how good your agent is compared to your competitor's agent.

This gives birth to another question: how do you figure out the performance delta? The answer is 'verification'. This is probably the most important aspect of AI. Generation is now abundant, but without verification it's just random combinations of plausible-looking work. You need a grading logic that verifies how well the agent performed the task against the original intent. Without it, there is no trust. This is the hard part about agents, and for judgment-based work it doesn't scale yet. You can't let an LLM grade its own homework; the grader shares the generator's blind spots, so the errors that matter sail right through. Real verification needs an independent signal, a different judge, a ground truth, a customer confirming the job was done. This lets you and your customer measure the performance delta.

I believe whoever builds robust verification infrastructure for their own industry will develop a durable moat. Everything else is simply a matter of the model getting better. What the model companies can't do is verify the work your agent did for your customer; they don't have the ground truth. As generation gets commoditized, the durable work left is verifying it. To me, agent startups will eventually become agent arbiters, where the real work they do will be verifying outputs.
