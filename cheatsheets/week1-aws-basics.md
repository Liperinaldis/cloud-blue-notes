# Week 1 — AWS Basics (Security)

## Region vs Availability Zone
- Region: a geographic area that contains multiple AWS data centers
- Availability Zone: one or more data centers within a Region, isolated from other AZs
- Why it matters:you spread resources across AZs for resilience; Region choice affects latency/compliance

## Shared Responsibility Model
- AWS is responsible for: security of the could
- Customer is responsible for: security in the could
- Example: data, identities

## Root vs IAM user
- Root should be used for: rare account-level tasks (billing, account settings)
- IAM user should be used for: daily work
- My rule: never create root access keys

## MFA
- What it is: a second factor in addition to a password
- Why it matters: stops password-only account takeover
- Where I enabled it: Root user + IAM user

## S3 basics
- What S3 is: object storage (files/objects)
- What “public” means: anyone on the internet can access it (if permissions allow)
- One common risk: sensitive files exposed or downloaded

- ## Extra
- If a bucket is public, what could happen?: Data could be publicly accessible and downloaded by anyone.
- How to prevent it: Use S3 Block Public Access, and grant access only to specific IAM principals (least privilege).
