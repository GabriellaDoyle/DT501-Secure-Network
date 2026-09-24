# DT501 Secure Systems & Infrastructure — Part A

Secure network architecture for SAP Innovation Labs, deployed on AWS (us-east-1).

## Contents
- `cloudformation_template_v2.yaml` — CloudFormation template (VPC, subnets, ALB, ASG, CloudWatch)
- `network_topology_v2.drawio` — Network topology diagram (open at app.diagrams.net)
- `security_overlay_v2.drawio` — Security architecture overlay with ISO 27001 control mapping

## Sandbox Constraints
Built using AWS Academy Cloud Foundations Sandbox. Some features (ASG, EBS encryption, TLS) were designed in the template but could not be deployed due to IAM restrictions. See portfolio Section 5 for full critical evaluation.
