---
title: "Event 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---

# Summary Report: "FCAJ Community Day 23/05/2026"

| Info | Details |
|------|---------|
| Date | 23/05/2026 |
| Location | 26th Floor, Bitexco Tower, 02 Hai Trieu Street, Saigon Ward, Ho Chi Minh City |
| Role | Attend |

### Event Objectives
- Share practical insights on GenAIOps and the importance of context in Generative AI applications.
- Explore the internal workings of LLMs and the non-determinism of supposedly deterministic settings in production.
- Introduce Amazon Quick Suite for business process automation and AI agentic capabilities.
- Present real-world case studies of building multi-agent systems and hackathon product development.
- Understand how to leverage Amazon CloudFront as a foundational security and performance layer with predictable pricing.

### Speakers
- **Mr. Tinh Truong** (Platform Engineer, GoTymeX) - Context is Everything.
- **Mr. Duc Dao** (Solution Architect, Cloud Kinetics) - How LLM actually works.
- **Mr. Hai Anh** (G-AsiaPacific Vietnam) - Friendly AI Assistant w/ Amazon Quick.
- **Team VIB** - Building UTMorpho from Idea to Reality.
- **Ms. Vy Lam** (Senior Business Systems Analyst, VPBank) - Enterprise-Grade Multi-Agent System.
- **Mr. Nguyen Tuan Thinh** (DevOps Engineer, First Cloud AI Journey) - CloudFront as Your Foundation.

### Key Highlights

#### Context Is Everything in GenAIOps
- AI models are powerful, but poor context leads to generic, inaccurate, or overly verbose answers.
- Good context turns a vague request into a solvable task by explicitly providing goals, situations, constraints, and relevant evidence.
- Usage is evolving from single prompts to a "Second AI Brain" that utilizes a continuous pipeline: Store → Retrieve → Generate → Learn.

#### LLM Non-Determinism
- Even with Temperature set to 0, LLM outputs can still be non-deterministic due to floating-point arithmetic parallelization on GPUs and inference batching.
- This uncontrolled variability heavily affects high-stakes applications like medical information retrieval and financial planning.
- Developers must apply mitigation strategies, such as running multiple queries and applying majority voting to ensure reliability.

#### Amazon Quick Suite Automation
- Empowers business users to automate routine tasks and gather information across multiple sources seamlessly.
- Capable of acting as a PM assistant by automatically creating Minutes of Meeting (MoM), sending emails to stakeholders, and scheduling follow-up meetings.

#### UTMorpho (LotusHacks 2026)
- Team VIB showcased their 36-hour sprint at LotusHacks, building UTMorpho—an AI UI generator that allows inline editing directly on the canvas (WYSIWYG).
- It successfully solves the problem of AI overgeneration and context drift by allowing isolated, token-aware edits without requiring a full re-prompt.

#### Enterprise-Grade Multi-Agent Systems
- Traditional credit scoring models fail for startups due to a lack of historical data, structured reporting, and physical collateral.
- Relying on a single AI agent for scoring suffers from severe context limits, expertise dilution, and a lack of checks & balances.
- Adopting a Multi-Agent Paradigm simulates a Virtual Credit Committee (e.g., Financial Analyst, Market Analyst, Team Evaluator) to provide specialized expertise, auditable reasoning, and fault tolerance.

#### CloudFront as a Foundation & Flat-Rate Pricing
- Amazon CloudFront is not just a CDN; it is a foundational layer for protecting and optimizing applications through a redundant global network with over 700 Points of Presence.
- To solve the financial risk of sudden bill spikes caused by DDoS attacks or viral traffic, AWS introduced flat-rate pricing in November 2025.
- The flat-rate plans provide predictable monthly costs by combining CDN, WAF, Anti-DDoS AMR, Route 53 DNS, and S3 storage credits into single packages suitable for small sites to enterprise usage.
- CloudFront fights distributed attacks with distributed defense by blocking unwanted traffic near the source and utilizing request collapsing to shield origin servers.

### Applying to Work
- **Improve Prompting:** Avoid feeding the model random, unstructured data (the "Internet Puller" problem) and establish clear constraints and expected formats.
- **Manage LLM Expectations:** Acknowledge the inherent non-determinism in LLMs and construct robust mitigation strategies for enterprise environments.
- **Adopt Multi-Agent Architecture:** Utilize specialized agents with rigid guardrails and compliance checks for complex, high-stakes decision workflows.
- **Optimize Infrastructure Costs:** Evaluate application traffic predictability and consider shifting to CloudFront's flat-rate pricing tiers to eliminate financial risks and consolidate security features.

![Image Event](/images/4-EventParticipated/4.2-event2/evt2.jpg)