# IAM Least Privilege - Project 2
AWS IAM project implementing least privilege for 3 roles.

## Policies Implemented
1. **Billing ReadOnly** - Can view bills only, no changes. [Code](./billing-readonly.json)
   - Why: Finance needs to see cost but not modify resources

2. **Developer EC2 Limited** - Can manage EC2 only in us-east-1, cannot touch IAM/billing. [Code](./developer-ec2-limited.json)
   - Why: Devs can build but cannot escalate privileges

3. **Intern S3 ReadOnly** - Can read S3 objects only. [Code](./Intern-ReadOnly-s3.json)
   - Why: Interns need to learn from data but cannot delete

## Proof
- 4 screenshots show IAM policies attached
- 3 JSON files show custom least privilege policies with region lock and Deny

Date: 26 Aug 2026
