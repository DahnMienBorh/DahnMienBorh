# Dahn Mien Borh

**Forward Deployed / Solutions Engineering · Founder, BORH**

I build and operate production agentic AI systems. A governed runtime in Python and FastAPI, operational memory on Postgres and pgvector, evaluation gates that score every answer before it ships, and MCP servers exposing governed tools. All of it helps run my company daily.

Eight years in engineering operations before this. Now looking for forward-deployed and solutions engineering work at AI-application companies.

Start here: [governed-agent-runtime](https://github.com/DahnMienBorh/governed-agent-runtime), a runnable public slice of the production system, with its eval harness and approval gate.

## The story

I spent eight years in AV integration, on the operations side of engineering. I managed a 16-person team and worked across much larger cross-functional groups, owning the standards, workflows, governance, QA, and tooling that kept projects moving. As I led teams and built that tooling, AI became a natural part of how I worked, and by the end of my tenure it ran through everything I built. In January 2026 I took that work full time.

What started as workflow improvements became operational intelligence, systems that remember decisions, coordinate work, and adapt as the company changes. Agentic systems are where I've done my deepest work, and the systems below run every day.

## What I've built

Every system below exists because I encountered the operational problem firsthand. They began as practical solutions and continue to evolve through daily use inside BORH.

**An operational memory system.** A 22-table Postgres store with six retrieval lanes, an entity graph, and human-governed writebacks. My systems remember decisions, clients, corrections, and context across months of work, and everything they recall traces back to its source.

**A multi-agent operations runtime with human-gated actions.** Agents draft, route, research, and prepare. Approval gates let me confirm quality while the system runs, learns, and improves, and email, publishing, and money always wait for a person's yes.

**An evaluation layer that grades the systems' own work.** A quality gate scores every memory packet on coverage and grounding, an LLM-as-judge eval grades generated summaries against the source records, and A/B baselines are checked in for comparison.

**MCP is how my systems expose their tools.** Agents get read-only or write access by capability tier, so every tool call is scoped on purpose, and approval-gated actions are unreachable from surfaces that should never touch them. The same pattern runs the core runtime and the customer-facing marketing and CRM workflows.

**A proposal factory.** A prospect opens a working, interactive kit already wearing their brand. Their booking flow, their operations, their world, built before anything is signed.

**An AI engineering pipeline for the built environment, intake to delivery.** It reads a construction RFP end to end, extracts the bill of materials, matches every line against a Revit family library, and checks the documents against each other and against the project's own record, including what was said in meetings. On a real public RFP it surfaced seven discrepancies inside the documents themselves. Once the narrative is approved, the pipeline drives Revit itself by script: the specified equipment is placed in the model and documentation views render without a human at the keyboard. Clash detection, QC plots, and engineer-ready submittal packages are the stages in build now. The same operational memory that runs my company runs the pipeline, so a requirement raised on a kickoff call is still enforced weeks later at review.

A public demonstration is live: the [Meridian Conservatory kit](https://github.com/DahnMienBorh/meridian-conservatory), a complete interactive proposal kit for a fictional institution. Deeper writeups and a demo film are next; the client systems themselves run private.

## Now

BORH is built on a simple idea. Organizations already have the people, knowledge, and systems, and AI-native tooling can help them keep context, make better decisions, and improve how work gets done over time.

BORH is where I built that and run it for client engagements. I'm looking for the right seat on a strong team, in forward-deployed and solutions engineering, or in applied AI for the built environment where I've spent my career, somewhere solving the right problem matters as much as building the right solution.

## Contact

mien@borh.ai · [borh.ai](https://borh.ai) · [LinkedIn](https://linkedin.com/in/dahnborh)
