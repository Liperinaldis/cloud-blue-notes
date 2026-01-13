# Week 1 — AWS Basics (Security)

## Region vs Availability Zone
- Region: the geographic area of the server
- Availability Zone: data center inside a region
- Why it matters:

## Shared Responsibility Model
- AWS is responsible for: security of the could
- Customer is responsible for: security in the could
- Example: data, identities

## Root vs IAM user
- Root should be used for: just to controll other account
- IAM user should be used for: day to day task
- My rule: never create root access keys

## MFA
- What it is: second factor, to authentication of a password
- Why it matters: adds more security to the account
- Where I enabled it: Root user + IAM user

## S3 basics
- What S3 is: Online storage
- What “public” means: means anyone can see it
- One common risk: exposing data

- ## Extra
- If a bucket is public, what could happen?: Data will be exposed
