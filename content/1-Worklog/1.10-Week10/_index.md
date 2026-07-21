---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Harden system security using IAM, WAF, and standard authentication protocols.
* Integrate asynchronous AWS services to handle background processing.
* Conduct comprehensive testing to ensure system stability.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | --------------- | ------------------ |
| 2 | - Configure stringent IAM roles and policies following the principle of least privilege. <br> - Implement JWT/OAuth2 for secure API authentication. | 06/22/2026 | 06/22/2026 | https://github.com/vinhpham2808/J2EE |
| 3 | - Set up Cloudflare WAF (Web Application Firewall) to protect against common web exploits. <br> - Configure SSL/TLS certificates for encrypted data transit. | 06/23/2026 | 06/23/2026 | https://github.com/vinhpham2808/J2EE |
| 4 | - Integrate SQS queues for asynchronous messaging. <br> - Set up EC2 worker nodes to consume messages from SQS. | 06/24/2026 | 06/24/2026 | https://github.com/vinhpham2808/J2EE |
| 5 | - Create AWS Lambda functions to handle background tasks (e.g., uploading files to S3). <br> - Test the async flow: SQS -> Worker -> Lambda -> S3. | 06/25/2026 | 06/25/2026 | https://github.com/vinhpham2808/J2EE |
| 6 | - Write and execute comprehensive integration tests for critical business logic. <br> - Review security settings and complete the Week 10 worklog. | 06/26/2026 | 06/26/2026 | https://github.com/vinhpham2808/J2EE |

### Expected Outcomes
- System security robustly configured with IAM, Cloudflare WAF, and JWT/OAuth2.
- Asynchronous processing pipeline (SQS -> EC2 -> Lambda -> S3) functioning smoothly.
- Solid test coverage achieved for main APIs and critical background jobs.
