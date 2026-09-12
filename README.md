Hi, I’m Tim. I’m building [Autonomy](https://github.com/autnmy): deterministic control planes around frontier models that enable fully autonomous operations that are more capable, reliable, and are production-grade.

**Our main project is [Descant](https://descant.run/), a fully autonomous software engineering system.** My engineering background includes Shopify, Amazon, and Boulevard. I spent about a decade at Shopify, working across a wide range of its systems and infrastructure as it grew from roughly 50 engineers to a company of more than 11,000 people.

### Descant

Descant works through the engineering issues you make eligible in your GitHub repository. It plans changes, implements them, opens pull requests, and works with a separate reviewer until the work is approved. You set the scope, priorities, and merge rules. It continuously learns at both the repository and system level; support for other issue trackers and repository hosts is on the roadmap.

We’re building for the full software development lifecycle and work that spans many changes: preserving architectural intent, making dependencies explicit, checking correctness, and maintaining code for the long term. Disciplined engineering and rigorous review are part of the workflow, including review across models from different vendors.

**Original published evaluation: 633 / 731 tasks resolved on SWE-bench Pro’s public split — 86.59%.** The [results repository](https://github.com/autnmy/descant-swebench-pro-results) contains patches, recorded grades, and evaluation instructions. The Descant runtime remains proprietary.

[Explore Descant and join the beta waitlist →](https://descant.run/)

Autonomous engineering also needs a simple, vendor-agnostic way to understand what work depends on what. [**Issuegraph**](https://issuegraph.org/) is our open specification for expressing work dependencies and ordering inside existing issue trackers. [Read the specification →](https://github.com/autnmy/issuegraph)

### The human side of autonomy

We’re also building [**OH HAI**](https://ohhai.app/), a shared inbox where agents can reach a person with updates, decisions, and tasks—and receive an answer even after the original session has ended.

It connects ephemeral agent sessions through a real-time, hub-and-spoke system using server-sent events (SSE). Agents can address one another across vendors and runtimes, while people retain a single place to supervise the work. It’s built on [**MA2H**](https://github.com/autnmy/ma2h-protocol), our open protocol for durable coordination between agent fleets and humans: routing messages, preserving decisions, and carrying answers across session lifetimes.

The aim is seamless delegation across vendors, with clear human authority, visibility, and a practical way to intervene. [Join the OH HAI TestFlight beta →](https://testflight.apple.com/join/PAVcSZEk)

### About the contribution graph

**Approximately 40,000 GitHub contributions in four months, including nearly 10,000 in a six-day stretch.** September 2026 snapshot; includes private repository activity.

I build with the next generation of Descant—an R&D version I use across projects and at increasing scale. It combines explicit orchestration, disciplined engineering, and review across different vendors’ models. The lessons from that work feed directly into the product. The graph reflects that workflow’s activity, including agent-assisted work.

I remain responsible for the technical design, architecture, engineering principles, and software I ship. That includes the boundaries between layers, the choice of design patterns, and the decision to establish protocols before building their implementations.

The goal is useful products, maintainable systems, and foundations that work across model providers. Model diversity is part of how we improve the work: different models contribute implementations, challenge assumptions, and review one another’s decisions. Much of the product development happens in private; the public specifications and evaluation artifacts above offer a window into the approach.

Alongside Descant itself, [OH HAI](https://ohhai.app/), [TriviaPot](https://apps.apple.com/us/app/triviapot/id6783994272), and [Buildwell](https://getbuildwell.com/) provide concrete product contexts for developing and evaluating this engineering workflow. We plan to share them as Descant case studies, including the engineering practices and lessons that carry back into Descant.

### Get in touch

Autonomy is the company, and Descant is our main focus. I welcome conversations with teams interested in using it, people building dependable autonomous systems, and investors interested in this direction.

[Descant](https://descant.run/) · [Autonomy on GitHub](https://github.com/autnmy) · [@timlayton](https://twitter.com/timlayton)
