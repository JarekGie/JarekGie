# Jarosław Gołąb

Platform Engineer focused on AWS governance, infrastructure automation and delivery platforms.

I work mostly with production AWS environments: multi-account organizations, infrastructure as code, and the CI/CD platforms teams ship through. Most of what I do sits where infrastructure meets operational reality - making environments predictable, governed, and cheaper to run without breaking what already works.

AWS is my primary platform. The same governance, automation and operational principles often transfer across cloud environments. Around 20 years in IT, the last several focused on platform engineering and cloud operations.

## Learn more

[twoje.it](https://twoje.it)

---

## What I Work On

### Cloud Governance
`AWS Organizations` `Service Control Policies` `Tag Policies` `Security Hub` `GuardDuty` `AWS Config`

### Platform Engineering
`Terraform` `Infrastructure as Code` `CI/CD platforms` `ECS` `EKS` `Developer Enablement`

### Cloud Cost Optimization
`FinOps` `Rightsizing` `Architecture Reviews` `Cost Visibility`

---

## Selected Work

### AWS Governance Rollout
Took AWS Tag Policies in a multi-account Organization from defined-but-inactive to live in report mode, with enforcement blockers brought from 98 to 0. Every blocker was fixed at the infrastructure-code source so it survives the next apply, and harder enforcement was deliberately kept as a separate later decision after an earlier premature attempt had caused a production outage.

### Disaster Recovery, Measured
A platform's disaster-recovery environment is rebuilt from zero on Kubernetes. Rather than assume it would recover, I measured the cold start stage by stage and found the critical path gated by a single relational database - until it answered, the application crash-looped, and the data import alone was 53% of the rebuild time. The remediation (snapshot boot versus in-place import tuning, each with its own cost) is designed and not yet shipped, so I treat the 53% as a measured baseline, not a result.

### Cloud Cost Optimization
Reduced AWS spend by removing waste instead of capping usage: NAT Gateway consolidation, VPC endpoints to cut data-transfer cost, and trimming non-production redundancy such as idle resources and unnecessary Multi-AZ on non-prod. Paired with tagging and cost visibility so the savings stay observable over time.

---

## Certifications

- AWS Certified Solutions Architect - Associate

_(more in progress)_

---

## Technologies

`AWS` `Terraform` `ECS` `EKS` `RDS` `GitHub Actions` `Jenkins` `ArgoCD` `CloudFormation` `Python`

---

## Contact

- Website: https://twoje.it
- LinkedIn: https://linkedin.com/in/jarekgolab
- Email: jaroslaw.golab@twoje.it
