At the root level, SCPs will enforce boundaries for all accounts. These are the key ones we will propose:

Deny Root Account Usage

Deny disabling GuardDuty, CloudTrail, Security Hub

Region restrictions (only allowed regions like us-east-1, us-west-2)

Deny unapproved services

Enforce encryption (S3, EBS, RDS)

Deny public S3 buckets

Restrict IAM role/user modifications outside SSO

Deny deletion of logs

Enforce mandatory tagging policy.”



Step 3: Explain IAM Roles & Accounts

English:
“For IAM, Control Tower gives us a baseline, but we need to define required roles:

Admin Role (for infra admins, emergency)

Audit Role (read-only for security team)

NetworkAdmin Role (for VPC, TGW, Direct Connect)

DevOps Role (for CI/CD pipelines)

ReadOnly Role (for developers/auditors)

Automation Role (for Terraform/Ansible)

Break-glass Role (emergency only, MFA protected).

And accounts will follow Control Tower standard:

Management, Log Archive, Security, Shared Services, Dev, QA, Prod, Sandbox.”
