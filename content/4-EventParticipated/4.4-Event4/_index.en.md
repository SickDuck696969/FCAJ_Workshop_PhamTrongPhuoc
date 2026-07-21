---
title: "Event 4"
date: 2026-06-20
weight: 4
chapter: false
pre: " <b> 4.4. </b> "
---

# Summary Report: "FCAJ Community Day - June 2026"

| Info | Details |
|------|---------|
| Date | 27/06/2026 |
| Location | 36th Floor, Bitexco Tower, 02 Hai Trieu Street, Saigon Ward, Ho Chi Minh City |
| Role | Attendee |

### Event Objectives
- Integrate AI into system operations.
- Optimize cloud infrastructure.
- Secure data at enterprise scale.

### Speaker List
- **Mr. Steve Tran** (Cloud Thinker) - Cloud Infrastructure Operations and the Agentic Platform Era.
- **Mr. Hieu Nghi, Mr. Kiet, Mr. Trung** - Building Voice AI Assistant for Enterprise.
- **Ms. Bao & Mr. Nguyen Nguyen** (Cloud Kinetics) - Implementing DevOps AI Agent on AWS.
- **Mr. Truong & Ms. Minh Anh** (Noventic) - Automating HR Processes with Amazon Q.
- **Mr. Toan Nguyen & Mr. Hieu Nghi** (Renova Cloud) - Private Security Model for Amazon Q and MCP Server.

### Key Content

#### 1. Cloud Infrastructure Operations and the Agentic Platform Era
- **Addressing 4 core problems:** Incident Investigation, Code Reviews, FinOps, and Security.
- **Single Agent vs Multi-Agent:**
  - A well-designed Single Agent can smoothly handle over 95% of tasks.
  - Multi-Agent architectures optimize context capacity and RBAC by decomposing tasks to Specialist agents.
- Helps Senior engineers resolve incidents faster, significantly minimizing system downtime.

#### 2. Building Voice AI Assistant for Enterprise
- **STT + LLM + TTS:** The optimal solution for Vietnamese, where Speech-to-Text handles input, LLM processes context, and Text-to-Speech responds.
- **Enterprise Advantages:** Intermediate text formats enable content control (Guardrails) to minimize misinformation, while supporting real-time Tool calling (e.g., API calls).
- **Production Challenges:** Reduced latency via Streaming, handling regional accents, integrating gender recognition, managing random user interruptions, and routing to human agents when needed.

#### 3. Implementing DevOps AI Agent on AWS
- **Automated Incident Investigation:** Fully automates the investigation process upon receiving alerts from systems like CloudWatch.
- **6 System Pillars:** Context Learning (Topology mapping), Control (strict permissions), Integration (via MCP), Collaboration (Slack, Jira), Convenient (AWS Console activation), and Cost Effective (priced per second).
- **Resolution Process:** Preliminary error classification, Root Cause Analysis (RCA), quick remediation recommendation, and long-term improvements. (The Agent only recommends, leaving execution to engineers).

#### 4. Automating HR Processes with Amazon Q
- **Automated Recruitment:** Amazon Q provides an intelligent, secure internal assistant platform, eliminating data leakage risks associated with public AI tools.
- **Connectivity:** Integrates via MCP with Microsoft/Google Workspace, Jira, Salesforce, and GitHub.
- **Workflow:** Generates specialized assistants from instruction files, automatically scans resumes (including OCR), matches candidate fit levels, and exports evaluation reports and salary benchmarks via a no-code application.

#### 5. Private Security Model for Amazon Q and MCP Server
- **Zero Trust Security:** Mitigates risks like DDoS and Man-in-the-middle attacks when public AI interacts with internal MCP Servers.
- **Architecture Solution:**
  - Completely isolate MCP Server inside a VPC's Private Subnet.
  - Establish a secure Interface Endpoint for Amazon Q via VPC Connection.
  - Route traffic through an internal ALB for TLS encryption, using ACM and Cognito for authentication.
  - Manage internal DNS with Route 53 Resolver to completely hide server addresses from the external internet.

### Application to Work
- **Understand AI's Role:** Treat AI as a powerful support and amplification tool, rather than a complete replacement for human engineering roles.
- **Secure AI Deployment:** Ensure strict Data Governance, Guardrails, and Private Security models are prerequisites before deploying AI to Production.
- **Optimize Operations:** Apply Agentic Platform and Multi-Agent concepts to internal monitoring systems to speed up incident investigation and optimize costs.

![Ảnh sự kiện](/images/4-EventParticipated/4.4-event4/evt41.jpg)

![Ảnh sự kiện](/images/4-EventParticipated/4.4-event4/evt42.jpg)