# AWS Troubleshooting – Common Operational Issues

This repository documents **real-world AWS operational issues** and how to troubleshoot and resolve them.  
It is focused on **Cloud Operations and Support scenarios**, not architecture theory.

## What This Project Demonstrates
- Practical AWS troubleshooting methodology
- How to isolate root cause using logs, metrics, and AWS tools
- Clear, step-by-step resolution documentation

## Scenarios Covered
- EC2 instance unreachable (SSH / RDP)
- Failed system and instance status checks
- IAM permission errors causing service failures
- Security group and NACL misconfigurations
- Disk full and memory pressure on EC2
- Application failures traced via CloudWatch logs

## Tools & Services Used
- AWS EC2
- CloudWatch (metrics & logs)
- IAM
- VPC (Security Groups, NACLs)
- AWS CLI
- Linux system commands

## Why This Matters in Production
These are the same issues handled by:
- Cloud Operations Engineers
- NOC teams
- AWS Support Engineers
- SRE-adjacent roles

The focus is on **speed, accuracy, and documentation**, which are critical in production environments.

## How to Use This Repo
Each folder contains:
- Problem description
- Symptoms
- Investigation steps
- Root cause
- Resolution
- Prevention notes

This mirrors how real incidents are documented internally.

## Audience
- Hiring managers and recruiters looking for candidates with **hands-on AWS operational experience**, not just certifications.
- Learners or junior engineers looking for real solutions to their production issues.
