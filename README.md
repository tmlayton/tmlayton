[![Autonomy — Making frontier models more capable and more dependable.](https://meetautonomy.com/assets/og-image.jpg?v=2)](https://meetautonomy.com/)

Hi, I'm Tim. My background includes 5 years building tech teams at agencies and 15 years working in tech at Shopify, Amazon, and Boulevard. I spent about a decade at Shopify, working across its systems teams as it grew from roughly 50 engineers to a company of more than 11,000 people.

I love building software that puts exclusive capabilities within reach of anyone and automates tedious work (laziness is a virtue)—respecting both the developer in the code and the user at the interface. I think great software gets out of the way so people can do their best work through autonomy, mastery, and purpose. That’s where the company name, [Autonomy](https://github.com/autnmy), comes from: not autonomous AI, but human autonomy. The goal is to create extremely reliable, consistent, and high-quality autonomous AI operations—individually useful or composable into larger, more complex autonomous AI systems—that unlock a breakthrough in human autonomy by accelerating the positive impact of AI and making it affordable for everyone.

Right now, impactful AI is out of reach for most people—not because the models aren't smart enough, but because making them run reliably is brutal (80% to 95% of enterprise AI pilots fail to reach production). People are right to be skeptical of a technology that is ultra-powerful yet unpredictable. Relying on unstructured interfaces to do real work forces humans to constantly babysit and verify outputs while burning through massive API and compute costs. Being forced to choose between getting left behind or burning your own time and money wrestling brittle tools is the exact opposite of autonomy. Leveling the playing field with reliable systems that put real agency back in people's hands is the future I want Autonomy to contribute to.

If I'm lucky enough to see Autonomy flourish, its ethos will be a direct descendant of the 2012 Valve Employee Handbook.

**Our main project is [Descant](https://descant.run/).**

[![Descant — 82.3% on DeepSWE v1.1.](https://descant.run/og-image.png)](https://descant.run/)

Descant is a zero-config software factory with the goal of delivering high quality code consistently, affordably, and at scale.

**Latest evaluation: Descant, 82.3% on DeepSWE v1.1.**

[Explore Descant and join the waitlist →](https://descant.run/)

[**Issuegraph**](https://issuegraph.org/) is our open, vendor-agnostic specification for expressing work dependencies and ordering inside existing issue trackers. [Read the specification →](https://github.com/autnmy/issuegraph)

### OH HAI

We’re also building [**OH HAI**](https://ohhai.app/): a control room for your AI agents. Similar to a terminal multiplexer or a tool that lets you manage multiple screens in one place, OH HAI brings all your AI agents together—whether they run in your command line, a desktop app, or custom software, and across different AI providers. It untethers you from your desk so you can monitor and manage everything from a single inbox without losing your place if a window crashes:

* Works with Any Agent or Tool: Hooks into any MCP-enabled client, desktop app, or command-line (CLI) tool—unifying different AI stacks (like Claude Code, OpenAI tools, Cursor, and custom setups) under one roof.
* Event-Driven Webhooks: Automatically triggers your agents using alerts from tools you already use (like GitHub Actions, Stripe, or Sentry errors) so they can investigate issues without you manually prompting them.
* Unified Triage Inbox: Routes all your agent requests into a clean web or iOS app designed for fast human decisions (Approve, Reject, or choose between options).
* Smart Updates (Blocking & Async): Beyond just waiting for permission to run a command, it delivers important low-frequency updates—like token cost spikes, milestone check-ins, or overnight summaries—straight to your inbox.
* Two-Way Directives: Easily reply, ask follow-up questions, or send new instructions back to any agent using clean, human-friendly labels.
* Crash-Proof Message Queue: Survives computer crashes, internet drops, or sleep modes so your pending decisions and replies never vanish into an ephemeral terminal buffer.

Built on our open [**MA2H protocol**](https://github.com/autnmy/ma2h-protocol), it connects agents and humans across vendors and runtimes. Agents communicate directly through a real-time hub, using the CLI or MCP server when shell access isn’t available. People retain one place to supervise, respond, and intervene.

[Get the OH HAI app →](https://testflight.apple.com/join/PAVcSZEk)

### About the contribution graph

I build with the next generation of Descant—an skill-based R&D version used across projects and at increasing scale. The base R&D skill is created during Descant's build process using a significant amount of the same code, minus the parts that interact with Descant's database. While Descant is currently only available to use with credits, I'm planning to make a production build of the skill available to use for a small amount of credits or subscription. The production skill would interact directly with Descant through OAuth allowing Descant surface run data and provide many of the same benefits of the production pipeline (state machine management, issue dependency graph, software-enforced spec and quality verification) while using your subscription and model or models of your choice.

Those lessons feed directly into Descant. I remain responsible for the architecture, engineering principles, and software I ship, including the decision to establish protocols before their implementations.

Descant itself, [OH HAI](https://ohhai.app/), [TriviaPot](https://apps.apple.com/us/app/triviapot/id6783994272), and [Buildwell](https://getbuildwell.com/) are proving grounds for that work and future case studies. Most of the development happens in private; the public specifications and evaluation artifacts above offer a window into the approach.

### Get in touch

I welcome conversations with prospective Descant users, people building software factories and dependable autonomous AI systems, and investors interested in this direction.

[Descant](https://descant.run/) · [Autonomy on GitHub](https://github.com/autnmy) · [@timlayton](https://twitter.com/timlayton)

<div align="center">
  <a href="https://commit-history.com/tmlayton">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/tmlayton" />
      <img alt="tmlayton's commit history" src="https://commit-history.com/embed/tmlayton" />
    </picture>
  </a>
</div>
