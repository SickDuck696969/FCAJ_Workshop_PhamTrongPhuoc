---
title: "Week 8 - AWS Well-Architected, SAM & Architecture Design"
date: 2026-04-17
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Week Topic

AWS infrastructure design meeting and architecture review for the game backend API.

### Week Objectives

* Draft the detailed AWS cloud architecture diagram for the game backend API aligned with AWS Well-Architected best practices.
* Review the VPC, ALB, EC2, RDS, SQS, and S3 service interactions used by the backend workshop.

### Daily Work Log

| Date | Day | Work Items | Lab / Project |
|---|---|---|---|
| 08/06/2026 | Monday | Team session mapping out the custom VPC configuration (multi-AZ subnets, CIDR boundaries for high availability). | Cloud Architecture |
| 09/06/2026 | Tuesday | Design public/private subnet routing, placing the ALB in public subnets and backend EC2 instances in private subnets. | Networking |
| 10/06/2026 | Wednesday | Design asynchronous background pipelines using SQS queues and Worker containers for backend game processing. | Asynchronous Jobs |
| 11/06/2026 | Thursday | Review the interaction between backend services, storage, and ingress controls for the game API. | System Review |
| 12/06/2026 | Friday | Evaluate the drafted architecture against the five pillars of the AWS Well-Architected Framework. | Well-Architected |

### Expected Outcomes

* Completed VPC network diagram detailing subnets, route tables, and gateways across two AZs.
* Clear security policy defining access routes through the Application Load Balancer.
* Defined SQS queue specifications and message schemas for backend asynchronous jobs.
* Technical architecture notes aligned with AWS Well-Architected pillars.

### Week 8 References

* [Project Repository](https://github.com/SuKem0703/BNGROUP_GAMEAPI) — Game Backend API
* AWS Well-Architected Framework
* Cloud Architecture tools (Draw.io)
