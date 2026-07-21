---
title: "Week 3 - Workshop Architecture, Infrastructure & API"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Week Topic

Study and implement the AWS workshop architecture for an online game backend, covering architecture overview, infrastructure setup, database layer, API Gateway, SQS/EventBridge integration, backup strategy, and verification.

### Week Objectives

* Understand the high-level architecture of the online game server system and identify the roles of compute, database, queue, and integration layers.
* Set up AWS foundational infrastructure and follow the workshop deployment workflow for resource management.
* Build the Aurora PostgreSQL database layer and configure AWS Backup with S3 storage for automated backups.
* Deploy API Gateway, Lambda backend, SQS FIFO, DLQ, CloudWatch monitoring, and EventBridge automation.
* Validate the workshop outcomes through testing and perform environment cleanup after completion.

### Daily Work Log

| Date | Day | Work Items | Lab / Project |
|---|---|---|---|
| 04/05/2026 | Monday | Review the workshop architecture overview, analyze the data flow of the online game system, and outline the compute, database, and integration components. | Workshop 5.1 - 5.2 |
| 05/05/2026 | Tuesday | Configure the AWS foundation layer, validate region/credentials, IAM permissions, and perform initial stack management activities for the workshop. | Workshop 5.2 |
| 06/05/2026 | Wednesday | Build the Aurora PostgreSQL database layer, configure RDS Proxy, and set up AWS Backup with S3 storage to create the backup strategy. | Workshop 5.3 |
| 07/05/2026 | Thursday | Deploy API Gateway, Lambda backend, and SQS FIFO/DLQ flow for event-driven processing, then monitor behavior with CloudWatch. | Workshop 5.5 - 5.7 |
| 08/05/2026 | Friday | Configure EventBridge integration, verify the workshop results through testing, and clean up all deployed resources after final validation. | Workshop 5.8 - 5.11 |

### Expected Outcomes

* Gain a clear understanding of the online game server architecture and the role of each service in the workshop.
* Successfully establish the AWS infrastructure foundation and complete the deployment workflow.
* Configure an Aurora PostgreSQL database with an automated backup process using AWS Backup and S3.
* Complete the API access layer with API Gateway, Lambda, SQS FIFO, DLQ, and CloudWatch visibility.
* Confirm the final system behavior through verification/testing and finish with clean-up activities.

### Week 3 References

* [Workshop 5.1 - Architecture Overview](../../5-Workshop/5.1-architecture-overview/)
* [Workshop 5.2 - Management and Infrastructure Setup](../../5-Workshop/5.2-management/)
* [Workshop 5.3 - Database Setup and Backup](../../5-Workshop/5.3-database/)
* [Workshop 5.5 - Amazon API Gateway](../../5-Workshop/5.5-API-Gateway/)
* [Workshop 5.6 - Amazon SQS FIFO](../../5-Workshop/5.6-sqs-fifo/)
* [Workshop 5.7 - AWS DLQ & AWS CloudWatch](../../5-Workshop/5.7-sqs-dlq-and-cloudwatch/)
* [Workshop 5.8 - AWS EventBridge](../../5-Workshop/5.8-eventbridge/)
* [Workshop 5.9 - AWS Backup](../../5-Workshop/5.9-aws-backup/)
* [Workshop 5.10 - Verification and Testing](../../5-Workshop/5.10-verification-and-testing/)
* [Workshop 5.11 - Cleanup](../../5-Workshop/5.11-clean-up/)
