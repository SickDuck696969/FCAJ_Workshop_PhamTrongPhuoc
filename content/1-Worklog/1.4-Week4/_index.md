---
title: "Week 4 - Auto Scaling, Route 53, DynamoDB & CloudFront"
date: 2026-04-17
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Week Topic

Study Auto Scaling, Route 53, CloudWatch, and high-availability design for the game backend API on AWS.

### Week Objectives

* Complete the core traffic and backend service design for the game API platform.
* Research Auto Scaling and Route 53 configurations for high-availability AWS deployments.
* Review cloud monitoring and operational readiness for the backend services.

### Daily Work Log

| Date | Day | Work Items | Lab / Project |
|---|---|---|---|
| 11/05/2026 | Monday | Review the main API flow of the game backend and identify which services need scaling and routing support. | API Architecture |
| 12/05/2026 | Tuesday | Learn Amazon EC2 Auto Scaling strategies to scale instances horizontally based on application load. Practice Lab 000006. | [Lab 000006 - Automate Application Scaling with Amazon EC2 Autoscaling](https://000006.awsstudygroup.com)|
| 13/05/2026 | Wednesday | Study cloud monitoring with CloudWatch and hybrid DNS resolution setups with Route 53. Practice Lab 000008 and Lab 000010. | [Lab 000008 - Create System Monitor with Amazon Cloudwatch](https://000008.awsstudygroup.com)|
| 14/05/2026 | Thursday | Install and verify AWS CLI commands on EC2 (Linux/Ubuntu) for automated resource operations. Practice Lab 000011. | [Lab 000011 - Using AWS CLI on Amazon EC2 (Windows/Ubuntu)](https://000011.awsstudygroup.com)|
| 15/05/2026 | Friday | Construct a multi-tier High Availability (HA) web application using ALB and RDS Multi-AZ to support the backend game API. Practice Lab 000021. | [Lab 000021 - Highly Available Web Application Workshop](https://000021.awsstudygroup.com)|

### Expected Outcomes

* Define the main traffic and service topology for the game backend API.
* Configure an Application Load Balancer (ALB) backed by an Auto Scaling Group.
* Deploy CloudWatch alarms and Route 53 DNS record sets.
* Write custom scripts utilizing AWS CLI to fetch cloud resource metadata.
* Understand HA architecture concepts including load balancing and multi-AZ database replication.

### Week 4 References

* [Project Repository](https://github.com/SuKem0703/BNGROUP_GAMEAPI) — Game Backend API
* [Lab 000006 - Automate Application Scaling with Amazon EC2 Autoscaling](https://000006.awsstudygroup.com)
* [Lab 000008 - Create System Monitor with Amazon Cloudwatch](https://000008.awsstudygroup.com)
* [Lab 000010 - Set up an integrated hybrid DNS system with Amazon Route53](https://000010.awsstudygroup.com)
* [Lab 000011 - Using AWS CLI on Amazon EC2 (Windows/Ubuntu)](https://000011.awsstudygroup.com)
* [Lab 000021 - Highly Available Web Application Workshop](https://000021.awsstudygroup.com)
